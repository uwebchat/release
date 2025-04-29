# Version 1.16.0 *29/04/2025*
 
## Release notes
 
### Preparing for Microsoft Certification
 
* **Microsoft 365 App Compliance Program.** <br />
*To get uWebChat ready for Microsoft 365 App Compliance we've been busy behind the scenes making some pretty significant upgrades. From extra security scans to OWASP dependency checks, streamlining packages and pipelines and even boosting the speed of the bot's responses, we've got it covered. As we charge ahead into 2025 we're not slowing down. Our sights are set on one thing: earning that shiny certification badge for uWebChat within Teams. Stay tuned, we’re working hard to make it happen!*
 
### Transfer expansion: Group Transfer
 
* **You can now transfer chats to entire groups!** <br />
*The ability to transfer an ongoing conversation to another agent has been expanded on! With the new Group Transfer feature, you can type `/transfer` during any active chat, then select the `Available Groups` option. From there, choose the group you want, and uWebChat will smartly scan for any active agents in that group and route the conversation accordingly. It’s smoother, faster, and more flexible, perfect for busy support teams with shared responsibilities.*
 
### Authenticate with Visitors
 
* **Visitor authentication is here.** <br />
*Ever wondered if the person you're chatting with is actually who they say they are? Now you can stop wondering. With the new authentication feature, agents using uWebChat (Professional and Enterprise plans) can type `/authenticate` in any ongoing chat. This launches a guided flow where you can verify your visitor via email or SMS, sending them a secure 4-digit code. The visitor then enters the code into a prompt to complete the verification process.*
 
### Save and View Conversations from the Virtual Assistant
 
* **Now you can save and review conversations your virtual assistant has had with visitors.**<br />
*Admins can now configure uWebChat to monitor and save chats between visitors and your virtual assistant. You’ll find this option under `Help -> Manage Virtual Assistant -> Edit Virtual Assistant Settings`, then look for either `Group Ownership` or `Save Conversation History`. Once you’ve registered a group owner and flipped the appropriate setting on, any finished chat with the virtual assistant on that group will trigger a notification to the owner. From there, you can either view the conversation in full or save it straight to your OneDrive for future reference.*
 
## Bug & Hot fixes
 
* 🐞 Fixed several pesky translation errors that snuck into various languages.
* 🐞 Squashed a bug affecting the BanIP functionality, it’s now working as expected.
* 🐞 Improved how the virtual assistant handles uploaded documents, smoother and more intuitive.
* 🐞 Took care of several low-level issues that cropped up during our prep for Microsoft certification.