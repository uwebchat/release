# Version 1.13.0 *22/08/2024*

## Release notes

### Media Implementation

* **uWebChat now supports media sharing between all of its channels (`WebChat`, `WhatsApp`, `Teams`).** <br />
*The ability to share media within an ongoing conversation has been added, and is available for professional users and up. An attachment button will be visible within the WebChat depending on your license that allows users to upload media to their connected agent. Agents will be able to upload media like normal through their teams client.*

### Media restrictions

**Currently the only supported media types are:** <br />
`image/jpeg`, `image/jpg`, `image/png`, `image/gif`, `image/webp`, `image/bmp`, `image/tiff`.

Furthermore, the dimensions and file size are limited to what the `Azure AI Content Safety API` can handle. Currently at the time of writing this results in a file size of `4MB` and dimensions of `> 50x50` and `< 2048x2048`. See [Azures Content Safety (Service Limits)](https://learn.microsoft.com/en-us/azure/ai-services/content-safety/overview#service-limits) for up-to-date restrictions.

**Below an overview of the limitations per license.**

| License | Media Access | Limit |
| ----- | ----- | ----- |
| Trial | ✅ | 10 |
| Free | ❌ | 0 |
| Basic | ❌ | 0 |
| Professional | ✅ | 20 |
| Enterprise | ✅ | 40 |

### General Improvements

* **Added the option to leave a message when talking to the virtual assistant during closed office hours.** <br />
*This can be found when talking to a virtual assistant as a clickable rich button, `End the conversation` or `Leave a message`.*

* **Streamlined the transfer functionality when transferring the conversation from one agent to another.** <br />
*Enforced the leaving of said conversation after transferring so messages don't get funneled to a conversation that the agent is no longer apart of.*

### WebChat Improvements

* **Disabled the input field before hunting an agent or on disconnect, and re-enabled it on successful connection.**

* **Enabled the microphone button which allows for text-to-speech functionality.** <br />
*This was automatically disabled during one of the previous updates, but is now available again for professional users and up.*

## Bug & Hot fixes

* 🐞 Fixed an issue where certain error logs weren't available anymore after daily caps had been reached.