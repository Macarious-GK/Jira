# Jira Service Management
- Jira Service Management helps you solve **customer requests**
- The Process of managing requests and support customer or employees

## Use Cases
- Service request management
    - Enterprise service management (ESM) extends IT service management (ITSM) processes
- Incident management
    - The practice of responding to an unplanned event or service interruption 
    - Two levels: Incident & Major Incident
- Problem management
- Change management
    - minimizes risks and disruptions to IT services while making changes to systems and services
- Knowledge management
    - the process of creating and sharing knowledge across an organization.
- Asset and configuration management
    - manages the physical and digital assets of an organization. 
    - manages the settings and configurations of those assets

##  work items, requests, projects, and queues

- A `request` is how a work item is represented to a customer.
- A `work item` is an individual unit of work.
- A `queue` is a filtered list of work items based on specific criteria.
- A `project` is a collection of related work items. In Jira Service Management, every work item belongs to a service project.
- A `portals`, websites for customers to submit requests for service in Service projects.
- `Knowledge base articles` share information and guidance that can help customers solve problems on their own. 


### Work items & Requests - Queue
- **Requests** and **work items** are two different views of the `same item`. Customers see requests; service team members see work items.
- Just like work items and requests, **service projects** and **portals** are different views of the `same items`.
- Request types got mapped to work types. (**custom request type** `->` **task work type**)
- We can add request types to `request type groups` (most related request types)

-  `Priority groups` are collections of queues that agents can easily switch between



## Roles
- An `agent` is a licensed user who works on customer requests and adds customers to the service project. 
- A `collaborator` is a user who works with agents, but likely belongs to another team, like Engineering or Finance
- A `Request participant` is a person that the customer want to inform about the request
- A `Approver` is a person that the customer need its  approve for the request
- `Customer`
- `Project admin`


## Access & Permissions
- Project admins can set Channel access to either Open or Restricted:
    - When set to **Open** → Anyone can submit requests to this project. 
    - When **Restricted** → Only people directly invited to this project can submit requests.

## Service in JSM
- `Services represent` a product or a service that your organization uses. These can be specific systems, tools, or products. 

## SLA
- `service-level agreement (SLA)` goals that specify how much time it should take to resolve certain work items.
    - an internal metric to help agents prioritize and respond efficiently to requests.

- Time and goals make up an SLA
    - A `time metric` lets you define how time will be measured for this SLA.
    - The `goal` for selected work items lets you define a target for the time metric. 

- SLA types:
    - Preconfigured Data
    - Customized SLA
    - A New SLA