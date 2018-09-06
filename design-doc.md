# Design Doc for Dream Mail Client

## Disclaimer/Foreword:

This is a list of things I think could/would/should be in a mail client. In a perfect world, all of the things I list in here would make it into a release of the client. 

I'd like to think of this mostly as a evolving list. At somepoint, it'll be made into a roadmap that is more concrete. For the time being, it's just a loose feature list.

# Guiding Principles

Overall, the experience should follow these principles listed below.

Fundamentals: 
- Clean
- Fast
- Focused
- Modular 

The idea is to build something that allows you to focus on the task you set out to do __without__ bombarding you with a million and one widgets and gizmos. 

This app will give reminders when appropriate, and allow you to manage the flow of information to something you find managable. 

As part of this, good workflows and macro's/shortcuts should be available. Some items might be context sensitive (i.e. highlight the text, and you should see textual related options and so on)

Another aspect that would be good is having modularity. Allowing you to reload compoents on the fly, rather than having to restart the program completely. This would allow for faster troubleshooting and customization. 

Ultimately, it should get out of your way and let you get work done. 



## Functionality and Features

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
        * This should be pretty straight forward. Perhaps there is a way to s
    * Mail rules
    * Archive management
        * Needs solid file architecture (to avoid corruption when over X GB's -- looking at you Outlook desktop!)
        * Offer standardized times (i.e. keep this legal mail for 5 years, then deep six it)
        * Backup to separate file (needs to be easier than OST/PST files)
    * Sweep inbox rule (automated rule based clean-up, a la Outlook webmail)
    * To-do functionality
        * Snooze
        * Assign Due dates
            * Have standard increments and days, allow custom ones as well
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
    * Gmail, Yahoo, Outlook (The Big 3)
- Notification flow
    * User customizable
    * Lets you supress notifications from certain people, recurring emails
        * Perhaps there will be an AI component that will scrape and highlight the top 5-10 items from emails that you flag as recoccurring? This concept should be explored further
    * Meeting reminders could be handled in a discreet way (fewer annoying popups) until a certain point
        * For example, you have two reminder types, subtle and obvious. You could configure it to show subtle reminders at 1hr before and 30 min before. Then at 15 min before, it could use the obvious reminder to make sure that you see it.
        * The user should be able to create a default reminder template (i.e. remind at 2hr, 30min and 15min) which would apply to all events that aren't edited manually
- To-do lists
    * Emails sent to yourself could have an option to build a to-do list from them. Perhaps this is AI assisted?
    * This can intergrate with reminders and notifications
    * Need to explore how this would intergrate with a calendar app or component     

# UI Mockups

Nothing here yet, just a placeholder.

## Reference Articles for Idea's

- PC World Article about Newton:
    * https://www.pcworld.com/article/3297801/software/newtons-shutdown-means-windows-users-are-losing-the-only-good-email-app-its-not-gmail.html

