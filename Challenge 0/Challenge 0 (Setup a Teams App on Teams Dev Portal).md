# Set up a developer environment

### Check credentials.
Check that you have an access to Microsoft 365 tenant and Azure subscription with provided credentials.

### Enable app sideloading.
After you have a tenant, you need to enable sideloading for your tenant, see [enable sideloading](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/prepare-your-o365-tenant#enable-custom-teams-apps-and-turn-on-custom-app-uploading). To verify if sideloading is enabled, sign in to Teams, select Apps -> Manage your apps and then check for Upload a custom app option.
![Upload a custom app option](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Challenge%200/sideloading.png)
<br/>

### Challenge 0-1. Upload an app using via Teams client.
Upload to the org' app catalog the app manifest of Test app #1 using Org's catalog (screenshot above). This option is avaliable only for admins.

**Success criteria**:


### Developer portal.
The Developer Portal for Teams is the primary tool for configuring, distributing, and managing your Microsoft Teams apps. <br/>
Open [https://dev.teams.microsoft.com/](https://dev.teams.microsoft.com/home) and check which tools are avaliable on Developer portal.<br/>
![Developer portal](https://github.com/LevonDX/Teams-Hack-event-March-2022/blob/main/Challenge%200/devportal.png)

### Challenge 0-2. Upload an app using Developer portal/Microsoft Teams admin center
1. Import the app manifest of Test app #2 to the Developer portal.
2. Change the app version to 1.0.1
3. Publish the app to Org catalog via Developer Portal.
4. Check that Test app #2 appeared in Org's catalog.

**Success criteria**:
1. Test app #1 is uploaded to the organization's app catalog
2. Test app #2 is uploaded to the organization's app catalog with upldated version.


**Resources**:
0. [Upload your app in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/deploy-and-publish/apps-upload)
1. [Enable custom Teams apps and turn on custom app uploading](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/prepare-your-o365-tenant#enable-custom-teams-apps-and-turn-on-custom-app-uploading).
2. [Manage your apps in the Microsoft Teams admin center](https://docs.microsoft.com/en-us/MicrosoftTeams/manage-apps): [Publish a custom app to your organization's app store](https://docs.microsoft.com/en-us/MicrosoftTeams/manage-apps#publish-a-custom-app-to-your-organizations-app-store)




3. https://docs.microsoft.com/en-us/microsoftteams/platform/get-started/get-started-overview
4. https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/build-and-test/teams-developer-portal?view=msteams-client-js-latest
-> need to determine success factos for this one. The idea is that this is the starting point, where the dev setups bot, tabs tec

