# Confluence
- It's a collaboration tool act as a central hub for your team to create/find/share information needed for working.
- Like a digital library of information

## Roles
- Org admin
- App admin
    - User access
    - Global permissions
    - Site settings and functionality
    - Customization
    - Monitor and troubleshoot
- Space admin

## Administration
### Monitoring
- Mission control : overview of the site data
- Audit logs
- Analytics
### Admin tools
- Automation 
- User access (test user access across the site)
- Spaces
- Announcement
### Settings
- Configuration:
    - General config
    - Notification
    - Global Template & blueprints
        - Global templates are created by Confluence admins. 
        - Global blueprints are created by Atlassian or third-party developers.
- Security:
    - Security config
        - `Hide external links` from search engines
    - Global permissions
    - Space permissions
    - Page restrictions


## Permissions:
### Global-level permissions
- Global permissions control what groups of users can do in Confluence
- Org admins give licensed users access to the Confluence site as members of user groups. ***Users can’t be added individually.***
    - Create **spaces or personal space** in Confluence 
    - **Public links**, you can let your Confluence users share content with anyone on the internet. 
    - Give access to Guests (access to one space only)
    -  Control anonymous access on this site

### Space-level permissions
- Space permission is given to users/groups, by check/uncheck a checkbox under the permission
- Space admins control this. At the space level, admins decide what each user or group can do in that space.
    - control default space permissions 
    - control spaces permissions 
    - can give users permissions to all spacess 

### Content/Page -level permissions
- Anyone who has permission to edit the content and to overall edit content in the space can change access to content items.

## Space
- A `Space` is a collection of related content. 
- A team may have hundreds of documents contained within a single space.
- Common uses:
    - Team space
    - Project space
    - Documentation space
    - Knowledge base space
    - Personal space

### Search

- Search with wildcards
    - `*` more than one char
    - `?` one exact char
## Pages
- `Pages` are documents you can create in Confluence. You can fill pages with text, tables, and multimedia
- `Parent pages` *group content*, like **folders**.
- `Child pages` sit within parent pages. You can have several levels of parent and child pages.
    - inherit view permissions from their parent page.
    - don’t inherit editing permissions from their parent page.
- `Live docs` are dynamic, collaborative documents that allow multiple users to edit content in real time.
- `Page templates` are pre-formatted pages that include instructions on filling out the page.
    - You can only use page templates when creating a new, blank page

### Enhance pages
- Page Header:
    - Name, Emoji, Status & header image
- Format your page: Tool Bar
- `macros`: extends the capabilities of a Confluence page, type `/` for quick access. 
    - code snipped
    - Jira work items
    - Table of content

## Whiteboards
- `Whiteboards` are interactive places where you can collaborate with teammates. 
- You can add stickies, boxes, comments, icons, images, links, and more.
- You can also set timers for brainstorms, draw on the whiteboard, and watch other users work.
- Common uses:
    - Brainstorming
    - Planning and strategy
    - Diagramming
    - Team building
    - Practicing agile
- We can create a Jira work item from a whiteboard object

## Databases.
- ``Databases`` are essentially flexible tables that enable teams to store, connect, and organize structured data in one place. 
- A database organizes content into **fields and entries**:
    - **Fields** define the structure of the database and are visually represented as columns.
    - **Entries** make up the content and are visually represented as rows.
- We can have a view (board, table, cards)
    - hide || sort || filter capabilities

## Calender
- `Team calendars` help your team stay organized and communicate availability with a schedule of personal and team events that link to individual work calendars and Confluence pages. 



## automation 
- `Smart Buttons` are buttons on pages that users can click to automatically perform actions