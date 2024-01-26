# Zendesk End-User Template

Theme. This repository hosts the customizable theme for our Help Center, enabling users to efficiently manage and track their support tickets.

## Repository Overview

Contained within this repository are the theme templates for our Zendesk User Help Center. These templates are designed to provide a seamless and intuitive user experience. Access the live Help Center here.

## Installation 

1. Install Zendesk CLI (zcli) globally using npm:

```npm install -g zcli```

This tool is essential for theme testing and deployment.


## Testing the Theme

1. Start the theme preview server:
```zcli themes:preview```

2. Access the local theme preview using an Admin account at:
[Zendesk Admin Local Preview](https://ringba.zendesk.com/hc/admin/local_preview/start)

This link allows you to view and interact with your theme changes in real-time.

## Deploying the Theme

This section provides a step-by-step guide to deploying updates to the Zendesk End-User Help Center Theme.

### Accessing the Theme Workbench

1. Log in as an admin to the Zendesk portal.
2. Navigate to the theme workbench by visiting [Zendesk Theme Workbench](https://ringba.zendesk.com/theming/workbench).

### Updating the Theme

Before deploying a new version of the theme:

1. **Update the Version Number:**
   - Open the `manifest.json` file in the theme repository.
   - Increment the version number. This is crucial for tracking different versions of the theme and for ensuring that the latest version is deployed.

2. **Deploying the Theme:**
   - Within the Zendesk Theme Workbench, locate the option to update the theme.
   - Select the option to 'Update theme from GitHub'. This will pull the latest version of the theme from the GitHub repository, incorporating all recent changes.

  ---
  
   <img width="622" alt="image" src="https://github.com/nik-ringba/zendesk-ringba-template/assets/122822827/35d0e3e0-00d5-49ed-993c-220cda8a528a">


### Final Steps

After updating the theme, it's recommended to:

- **Review the Changes:** Ensure that the new theme version is displaying correctly in the Zendesk Help Center.
- **Test Functionality:** Verify that all features are working as expected and that the user experience is seamless.

### Note

Please ensure that all changes are thoroughly tested in a staging environment before deploying them to the live Help Center to avoid any disruptions in service.

---

This deployment guide is designed to ensure a smooth and error-free update process for our Zendesk End-User Help Center Theme.
