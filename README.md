# Microsoft Teams - Set Status Message
Update your Microsoft Teams status message based on your location.

![](/MicrosoftTeamsStatusMessage.png)

## General
Want to let your colleagues know that you are also at the office via Microsoft Teams and do this automatically?
Let this Power Automate flow set you Microsoft Teams status message to "At the office" or something else you desire when you enter the geofence you have set.

_[Power Automate app](https://emea.flow.microsoft.com/en-us/mobile/download/?src=banner) form Microsoft is required._

## Connections in use
* SharePoint

## Setup
1. Please download the [MicrosoftTeamsSetStatusMessage.zip](/../../raw/main/MicrosoftTeamsSetStatusMessage.zip).
2. Go to https://emea.flow.microsoft.com/manage/flows/import.
3. Upload and import the MicrosoftTeamsSetStatusMessage.zip file. [Extra help for importing Power Automate projects](/../../../MrAutomate33/blob/main/files/CreateConnectionsInImport.md).
4. Open the Power Automate flow and set your geofence trigger location.
5. Set the desired message and expiry in the SharePoint REST Api call action.
7. Don't forget to turn on the Power automate flow.

## Troubleshooting
If the action called "Send_an_HTTP_request_to_SharePoint_-_Set_Teams_Message" fails with code 301, try one of the other site addresses. This may differ per tenant.
Post a issues if none of the other site addresses work for you.
* https://noam.presence.teams.microsoft.com
* https://noamdf.presence.teams.microsoft.com
* https://presence.gcc.teams.microsoft.com
* https://presence.teams.microsoft.com
