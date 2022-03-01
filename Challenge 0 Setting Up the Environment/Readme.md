# Set up a developer environment

### Check credentials

Check that you have an access to Microsoft 365 tenant and Azure subscription with provided credentials.

### Enable app sideloading

After you have a tenant, you need to enable sideloading for your tenant, see [enable sideloading](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/prepare-your-o365-tenant#enable-custom-teams-apps-and-turn-on-custom-app-uploading). To verify if sideloading is enabled, sign in to Teams, select Apps -> Manage your apps and then check for Upload a custom app option.
![Upload a custom app option](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/sideloading.png)

### Challenge 0-1. Upload an app using Teams client

Upload to the org' app catalog the application package (zip file) of ***PersonalTab app*** using Org's catalog (screenshot above). This option is available only for admins.
***(You can find the PersonalTab.zip on the root folder of Challenge 0)***

### Developer portal

The Developer Portal for Teams is the primary tool for configuring, distributing, and managing your Microsoft Teams apps.
Open [https://dev.teams.microsoft.com/](https://dev.teams.microsoft.com/home) and check which tools are available on Developer portal.
![Developer portal](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/devportal.png)

### Challenge 0-2. Upload an app using Developer portal/Microsoft Teams admin center

1. Import application package of ***PersonalTab app*** to the Developer portal.
2. Change the app version to 1.0.1
3. Publish the app to Org catalog via Developer Portal.
4. Check that ***PersonalTab app*** appeared in Org's catalog.

## Success criteria

1. ***PersonalTab app*** is uploaded to the organization's app catalog
2. ***PersonalTab app*** is uploaded to the organization's app catalog with updated version.

## Learning Resources

1. [Upload your app in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/apps-upload)
2. [Enable custom Teams apps and turn on custom app uploading](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/prepare-your-o365-tenant#enable-custom-teams-apps-and-turn-on-custom-app-uploading).
3. [Manage your apps in the Microsoft Teams admin center](https://docs.microsoft.com/en-us/MicrosoftTeams/manage-apps)
4. [Publish a custom app to your organization's app store](https://docs.microsoft.com/en-us/MicrosoftTeams/manage-apps#publish-a-custom-app-to-your-organizations-app-store)
5. [Developer portal](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Resources/devportal.png)
