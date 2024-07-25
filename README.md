# Version 1.12.0 *25/07/2024*

## Release notes

### Custom "Leave a message" button

* **Added functionality to add a custom button under the "Leave a message" dialog.** <br />
*This can be found under `Help` -> `Manage groups` -> `Edit an existing group` -> `Leave a Message Button` -> (`Add custom button` or `Remove custom button`) and is accessible for basic users and up.*

### Under the hood

* **Reworked the service that's responsible for keeping track of the current conversation history in order to generate transcripts.** <br />
*Added numerous logging, improved the performance and reliability, especially surrounding the virtual assistant.* 
* **Reworked the service that's responsible for for catching any errors that weren't correctly handled or caught during normal execution.** <br />
*It'll now forward any uncaught error(s) to our logging system, along with a detailed description of any relevant settings and variables that were present during execution.*

## Bug & Hot fixes

* 🐞 Fixed an issue where irrelevant database logs were clogging up the logging system.
* 🐞 Fixed a few existing technical issues that came to light due to the implementation of a more extensive logging system.