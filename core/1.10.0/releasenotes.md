# Version 1.10.0 *27/06/2024*

## Release notes

### Typing Indicator

* **Added functionality for a typing indicator when talking with the bot or with a virtual assistant for a more responsive experience.** <br />
*This functionality works exclusively for interacting with the bot itself, or when talking with a virtual assistant.*

### Under the hood

* **Reworked various classes with regards to code quality, readability and performance.**
* **Reworked the majority of the database backend for better performance and to anticipate for Microsoft's changes and end-of-life schedule.**
* **Added a lot of internal logging for exception handling, catching bugs and maintaining security.**

## Bug & Hot fixes

* 🐞 Fixed an issue where the WhatsApp integration would sporadically send duplicate requests and responses.
* 🐞 Fixed an issue where some automatic timer functions wouldn't properly function under specific conditions.
* 🐞 Fixed an internal issue with the style functionality which originated from a previous version migration.