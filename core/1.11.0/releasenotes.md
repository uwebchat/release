# Version 1.11.0 *10/07/2024*

## Release notes

### Transcriptions

* **Added a downloadable transcript for end-users that shows the entire conversation history in `.txt` format.** <br />
*Accessible for professional users and up, available for both agent and virtual agent conversations.*

### Privileges Management

* **Added the option to grant and revoke administrative privileges to multiple agents within your uWebChat tenant.** <br />
*This can be found under `Help` -> `Manage agents` -> `Manage privileges` -> `Grant or Revoke privileges`.*

### Virtual Assistant

* **Added functionality to connect to a real agent from within a conversation with the virtual assistant.** <br />
*This can be found when talking with a virtual assistant within a group, and clicking the `Call live Agent` button.*
* **Added functionality to connect with a virtual assistant during closed hours of a group instead of leaving a message.** <br />
*This can be found under `Help` -> `Manage groups` -> `Edit an existing group` -> `VA in closed-hours`.*
* **Added a dialog to configure the required credentials and endpoints that the virtual agent needs to function.** <br />
*Currently unavailable within the help menu, type `configure openai` in order to prompt for the dialog.*

## Bug & Hot fixes

* 🐞 Fixed an issue where sending two or more messages to the assistant agent at once would cause problems.