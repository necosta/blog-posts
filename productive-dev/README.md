# (An effort on) productive development 
|
A couple of times in my professional career, while working in collaboration with other developers, 
I've noticed repeated tasks, misuse of tools, and simply not being as efficient as possible in 
performing a task.

For example:
* Password management
  * not knowing where the passwords are...
* Bookmarks 
  * repeating the same navigation to main pages...
* Notification management
  * being overwhelmed with updates from multiple sources...

This article contains **tools**, **tips** and **strategies** that (hopefully) allows developers to develop software 
in a more optimal manner. 

It's incomplete and completely based on the author's experience. 
Still can be useful for the community. In no particular order:

### Password management

So often we have to search for credentials to authenticate to a specific target system.
With the incredible number of targets and the existence of multiple accounts (personal account, service accounts, ...)
it's almost **mandatory** to have a tool as a source-of-truth for all passwords.

One option is [KeePassX](https://github.com/keepassx/keepassx)

This tool can be used to store all username and passwords, 
in an offline master password encrypted file.

There is also one added feature in my opinion, 
can be used to store **any** key-value data:
 * Abbreviations
 * Commands cheat sheet
 * To-Do list
 * Environment names
 * Interview questions
 * Code review check-list
 * Miscellaneous ideas for later

Not so suitable for collaboration (see [Vault](https://github.com/hashicorp/vault) instead) 
but this is a first step in managing credentials (and other key-value data) in an efficient manner.

### Bookmarks

Not using bookmarks efficiently has to go in 
Stack Overflow performance challenges [top list](https://insights.stackoverflow.com/survey/2019?utm_source=so-owned&utm_medium=blog&utm_campaign=dev-survey-2019&utm_content=launch-blog&__hstc=188987252.aa77201028509d3b0b5be4c0cc72a8d1.1577473865186.1577473865186.1577473865186.1&__hssc=188987252.1.1577473865187&__hsfp=4242202861#work-_-greatest-challenges-to-productivity) 😊

So often I see developers scrolling through GitHub to find open pull requests list 
or JIRA to find the active sprint board.

Should be common sense to keep relevant URLs bookmarked and easily accessible in one-click

For example, keep links to:
* Main source code organization
* Open tickets
* Open merge requests
* Sprint/Kanban board
* CI/CD tool
* Monitoring tools
* Documentation/Wiki
* Binary repo/Artifactory
* Infrastructure/Cloud provider
* Articles, Blogs, News, Email
* ...

### Notification management

Between meetings, emails and collaboration tools
it's essential to carefully balance the time we spend on updates vs developing software

Some strategies:
* Emails: Limit the number of times you check your email during the day to 3 (morning, lunch and mid afternoon)
* Emails: Move emails you read/closed out of inbox
* Meetings: Ask for clarity on the scope when not clear
* Meetings: Interrupt when participants start drifting off
* Collaboration tools: Always broadcast in written (as opposed to sending emails or creating meetings to verbally communicate updates)

### Tools

* **Amphetamine:** Ensures your laptop does not go into sleep mode
* **Atom:** Awesome text and source code editor
* **Docker:** Containerisation support
* **IntelliJ IDEA:** Powerful IDE (Integrated Development Environment)
* **iTerm2:** Terminal emulator
* **kdiff3:** Great diff tool to solve git merge conflicts
* **Postman:** Platform for API development
* **Tablecruncher:** Powerful CSV editor
* **VirtualBox:** Virtualisation support (Linux VM)
* **Visual Studio Code:** Also an awesome code editor
* **VisualVM:** View detailed information about Java applications

### Other strategies

* Check inner source and open source before starting any task
* Perform source code analysis
* Perform code reviews in the morning
* Periodically challenge status quo

_______

> Work smart, not hard
