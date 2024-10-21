# Version 1.14.0 *26/09/2024*

## Release notes

### County Blocklist Implementation

* **Due to customer demand, uWebChat now supports restricting access for one or multiple countries.** <br />
*The ability to block individual or various countries has been added, and is available for enterprise users and up. The options for this can be found under `Help` -> `Customer Actions` -> `Manage blocklist`.*
* **The blocklist functionality works alongside our new usage system.** <br />
*Each enterprise customer will get `600 x Enterprise License` worth of usage which resets on the first day of each month. This gets subtracted by 1 when a visitor attempts to start a new conversation. Note that visitors can still start conversations regardless of the available usage, but only the blocklist functionality will cease to function when you've ran out usage tokens for the month.*

### Help Menu Redesign

* **The help menu has been partially redesigned so new features are easier to locate.** <br />
*Various features have been relocated behind top level buttons so they are easier to find. Previously a bunch of functionality was hidden behind multiple nested menus which were getting increasingly difficult to navigate to. This is the first step into giving a better user experience, and we'll continue to look for ways of improving the way you interact with our bot.*

### Automated Greetings Implementation

* **Automated greetings through the use of suggested actions have been added when interacting with Virtual Agents.** <br />
*The option of adding automated greetings has been added on a group level for enterprise users and up. You'll be able to enable this functionality on any group that houses a virtual agent. 3 suggested actions will appear for visitors when starting a new conversation that they'll be able to click, which instantly asks the virtual agent the suggested question that they clicked on. Note that if you don't manually set these 3 automated greetings, uWebChat will generate 3 relevant questions dynamically using AI. The options for this can be found under `Help` -> `Manage groups` -> `Edit an existing group` -> `Manage greetings message`.*

## Bug & Hot fixes

* 🐞 Fixed a rare issue where you'd be stuck in a disconnect loop when certain OneDrive permissions weren't properly set.
* 🐞 Fixed an issue where the wrong language was translated within the generated transcriptions when working with multiple languages.
* 🐞 Fixed various silent errors in the backend that were causing instability.
