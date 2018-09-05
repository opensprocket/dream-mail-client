# Design Doc for Dream Mail Client

## Disclaimer/Foreword:

This is a list of things I think could/would/should be in a mail client. In a perfect world, all of the things I list in here would make it into a release of the client. 

I'd like to think of this mostly as a evolving list. At somepoint, it'll be made into a roadmap that is more concrete. For the time being, it's just a loose feature list.

# Guiding Principles

Fundamentals: 
- Clean
- Fast
- Focused

## Functionality

- Basic features
    * Send/recive
    * To & From
    * CC & BCC
    * Drafts
- Contacts
    * Groups
    * Individuals
    * Distribution lists
- Delivery/information
    * Seen/read recipts (display as checkmarks (like ))
    * Scheduled sending (i.e. Send at 8:00pm on X date)
    * Recall sent messages (up to 24 hrs?)
    * Halt/Stop sending message
- Mail Management
    * Robust tagging
        * Labeling/tagging
        * Priority (Low, Med, High)
    * Folder sorting
    * Mail rules
    * Archive management
        * Needs solid file architecture (to avoid corruption over X amounts of GB's -- looking at you Outlook desktop app!)
        * Offer standardized times (i.e. keep this legal mail for 5 years, then deep six it)
        * Backup to separate file (needs to be easier than OST/PST files)
    * Sweep inbox rule (automated rule based clean-up, a la Outlook webmail)
    * To-do functionality
        * Snooze
        * Assign Due dates
    * Out of office replies/canned responses
    * Reply reminders (nudges?)
- Security 
    * Encryption comes standard!
    * HTTPS or similar protocols when possible
    * Lockable client 
    * Password Safe intergration (Keepass)
    * Expiring Emails
- Supported Protocols/existing solutions
    * POP3
    * IMAP
    * OAuth sign-in
    * Gmail, Yahoo, Outlook (Big3)


    

## Reference Articles for Idea's

- https://www.pcworld.com/article/3297801/software/newtons-shutdown-means-windows-users-are-losing-the-only-good-email-app-its-not-gmail.html

