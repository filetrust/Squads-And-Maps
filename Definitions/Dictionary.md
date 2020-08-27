| | | | |
|-|-|-|-|
| | | | |
| | | | |
|Jira Issue Type Dictionary| | | |
|Issue Type|Definition/Purpose|Rules/Characteristics/Relationships|Statuses|
|Access|Used to state the type of authority or permission to obtain restricted information.|Has links: Role|Has Statuses: |
| | | |·        Requested|
| | |Has Custom Fields: Expiry date|·        Granted|
| | | |·        Revoked|
|Action|Used to state a step that must be taken in order to achieve a specific goal.|Has links: Any issue|Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields: None|·        In Progress|
| | | |·        Done|
|Alert|This issue type states a notification which indicates that a predefined event or error condition has occurred and that some action is needed|Has links: Story, Feature, Product|Has Statuses: |
| | | |·        To Investigate|
| | |Has Custom Fields: Triggered by, Component|·        Investigation in Progress|
| | | |·        Resolved?|
|ASSET TYPE|States the kind or category of a company asset|Has links: IT Asset| Has Statuses: |
| | | | |
| | |Has Custom Fields:| |
|Assets|Used to state what asset is currently related to a product, project or vulnerability|Has links: Component| Has Statuses: |
| | | |§  In Use|
| | |Has Custom Fields: Asset Type, Asset Tag|§  Not Used |
|AWS ACCOUNTS|Used to state which AWS Account is currently in use for the related issue|Has links: Scope, service account, AWS account| Has Statuses: |
| | | |§  In Planning|
| | |Has Custom Fields: Subscription ID, Subscription Name, Subscription Status, Subscription Owner, Subscription Administrator, Subscription Contributor|§  In Use|
| | | |§  Closed|
|Backlog|This issue type states a list of tasks required to support a larger strategic plan. In a product development context, it contains a prioritized list of items that the team has agreed to work on next. Typical items on a product backlog include user stories, changes to existing functionality, and bug fixes. Provide a single source of truth for the team’s planned work;|Has links:  Backlog, Feature, Story, Bug, Task |Has Statuses:|
| | |                                                                                                                                                                                                                                                                                                                                                   Has Custom Fields: None|§  Planned|
| | | |§  Not Planned|
|Bug|States a problem or fault in a program which causes failure or deviation from expected results. It provides a link between features & related bugs, provides a template to define the steps to replicate the problem|Has links: Feature, Story, SOW|Has Statuses:|
| | | |§  To Do|
| | |Has Custom Fields:|§  In Development|
| | | |§  Rejected|
| | | |§  Ready for Test|
| | | |§  In Test|
| | | |§  Re-Opened|
| | | |§  Closed|
|Business Objective|This issue type shows a specific result aimed to be achieved throughout a period|Has links: Project| Has Statuses: |
| | | |§  Achieved|
| | |Has Custom Fields: None|§  Not Achieved|
|Change|A change is the process of moving a project, product or feature current specifics to new ones; This issue type shows the new specifics to work with|Has links: Any| Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields: None|·        In Progress|
| | | |·        Done|
|Checklist|This issue type shows a list of items to be checked for the successful completion of a task|Has links:   Any issue     |Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields: Items List    |·        In Progress|
| | | |·        Done|
| | |                                                                                                                                                                                                                                                                                                                                          | |
|CLOUD ASSET|Used to state a Cloud based IT Asset|Has links: user, asset type| Has Statuses: |
| | | |·        In Planning|
| | |Has Custom Fields: Subscription ID, Subscription Name, Subscription Status, Subscription Owner, Subscription Administrator, Subscription Contributor|·        Acquired|
| | | |·        In Operation|
| | | |·        Disposed|
|Completed Outcomes|Completed outcomes are measurable statements that demonstrates a set goal have been reached; |Has links:   Outcome| N/A|
| |This issue type is used to show that a specific outcome has been completed| | |
| | |Has Custom Fields:| |
|Component|This issue type states a uniquely identifiable input to be included as a part of a finished product|Has links: Asset, Threat Model| Component risk statuses?|
| | | | |
| | |Has Custom Fields: None| |
|COVID|Used to manage Covid related issues| | |
|Customer|A client of the organisation or an internal customer. All squads should have customers/clients. These are the consumers of the delivered outcome. Who will use what is being delivered|Has links: Any |Has Statuses: |
| | | |·        Prospect|
| | |Has Custom Fields:|·        Active Customer|
| | | |·        Churned|
|Contract| |Has links: Any |Has Statuses: |
| | | |·        Created |
| | |Has Custom Fields: Contract Owner, Supplier's name, Signatory, Supplier's Contract Type, Start date, End Date|·        In Review|
| | | |·        Approved|
| | | |·        Signed|
| | | |·        Archived|
| | | |·        Renewed|
|Characteristic|A set of attributes that bear on the existence of a set of functions and their specified properties|Has links: Sub-characteristic, Standard|Has Statuses: N/A|
| | | | |
| | |Has Custom Fields: None| |
|Decision|Used to state the choice made between alternative courses of action in a situation of uncertainty.|Has links: Any|  Has Statuses: |
| | | |·        Draft |
| | |Has Custom Fields: Evidence|·        More Details Required|
| | | |·        Not A Decision|
| | | |·        Approved|
| | | |·        Not Approved|
|Decision Tree|Used to show a course of action representing the decisions, outcomes or reactions in each situation|Has links: tbc| N/A|
| | | | |
| | |Has Custom Fields: None| |
|Design|Used to record design project work|Has links: Any|  Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields: Template|·        In Progress|
| | | |·        Researching|
| | | |·        Consistency Check|
| | | |·        Designing|
| | | |·        Done |
| | | |·        Recycling|
| | | |·        For Review|
|Domain|Used to show the address where Internet users can access Glasswall websites|Has links: Entity|  Has Statuses: |
| | | |·        Active |
| | |Has Custom Fields: Expiry Date|·        Expired|
| | | |·        Deactivated|
| | | |·        Pending Delete|
|Entity|An issue type that has a unique and separate existence|Has links: stakeholders, business owner, decision, playbook, program, project|  Has Statuses: TBC|
| | | | |
| | |Has Custom Fields: None| |
|Equipment|Used to record any signed equipment|Has links: Person|    Has Statuses: |
| | | |·        Signed Out Requested|
| | |Has Custom Fields: tbc|·        Equipment Signed Out |
| | | |·        Equipment Returned|
|Event|An issue type that refers to an action or occurrence that affects a project & can be reasonably measured|Has links: Any|    Has Statuses: |
| | | |·        Planning|
| | |Has Custom Fields: Updates|·        In Progress |
| | | |·        Closed|
|Fact|An issue type that denotes an observed state or information item known to have happened & confirmed or validated to such an extent that it is considered a reality.|Has links: Any|N/A|
| | | | |
| | |Has Custom Fields: Updates| |
|FAQ|Used to state the frequently asked questions on a product, project, use case etc..|Has links: Any|   Has Statuses: |
| | | |·        Awaiting Answer|
| | |Has Custom Fields: Answer|·        Answer Applied|
|Feature|An issue type that states a specific software attribute that represents a product or system functionality |Has links: Story, Project|  Has Statuses: |
| | | |·        New|
| | |Has Custom Fields:  Acceptance Criteria, Due Date, Requirements|·        In Progress|
| | | |·        Blocked|
| | | |·        Paused|
| | | |·        Not Done|
| | | |·        Done |
| | | |·        Removed|
|Focus|A issue type that shows the center of activity, attraction, or attention of a Program or project|Has links: Program or Projects|  Has Statuses: |
| | | |·        Long Term Focus|
| | |Has Custom Fields: Focus period?|·        Short Term Focus|
|Gaming|tbc| | |
|GitHub| |Has links: Program, Projects |  Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields: tbc (GitHub Organization, GitHub Users)?|·        In Progress|
| | | |·        Done|
|GitHub Organization|tbc| | |
|GitHub Users|tbc| | |
|Group Goal|tbc| | |
|Guild|A lightweight community of interest where people across the whole company gather and share knowledge of a specific area. Anyone can join or leave a Guild at any time. For example, ‘React’, ‘Performance’|Has links: member| Has Statuses: |
| | | |·        Open|
| | | |·        Closed|
| | |Has Custom Fields: None| |
|HARDWARE|???|Has links:  ASSET TYPE| Has Statuses: |
| | | |·        Acquired|
| | | |·        In Operation|
| | |Has Custom Fields: Useful Life, Warranty Type, Asset Value, Asset Condition Rating, Asset Status|·        Disposed|
|Hat|Used to classify a squad as working at Pioneer, Settler or Town planner level|Has links: Squad, Person|Has Statuses: |
| | | |·        In Use|
| | |Has Custom Fields: None|·        Not Use|
| | | | |
|Hypothesis|This issue type states a supposition or theory that is provisionally accepted in order to interpret certain events and to provide guidance for further investigation|Has links: any issue|Has Statuses: |
| | | |·        Confirmed|
| | |Has Custom Fields:|·         |
|IAM|This issue type shows the AWS Identity & Access Management permission of a resource|Has links: tbc|Has Statuses: |
| | | |·        Requested|
| | |Has Custom Fields: tbc|·        Granted|
| | | |·        Revoked|
|Incident|This issue type describes an event that disrupts the normal operations of a system, the daily business & services|Has links: Any|  Has Statuses: |
| | | | |
| | |Has Custom Fields: Priority, Event Date, Severity| |
|Industry|??|Has links: Industry|  Has Statuses: |
| | |Has Custom Fields: None|      TBC|
|InfoSec Scrum|??|Has links:| |
| | |Has Custom Fields: | |
|IT Asset|A company-owned information, system or hardware that is used for company activities|Has Asset|  Has Statuses: |
| | |Has Custom Fields: None|·        In Planning|
| | | |·        Acquired|
| | | |·        In Operation|
| | | |·        Disposed|
|IT Helpdesk|??|Has links: tbc| |
| | | | |
| | |Has Custom Fields:  tbc| |
|IT Onboarding|Used to record the activities & processes for the integration a new employee into the organization|Has links: Person, has Training, Team, Squad|  Has Statuses: TBC|
| | | | |
| | |Has Custom Fields: None| |
|IT System|A system or platform which staff use and have accounts on. These systems are owned and managed by our IT team. For example, ‘Jira’, ‘GitHub’|Has links:  Role, Entity|  Has Statuses: TBC|
| | | | |
| | |Has Custom Fields:  None| |
|Jira|??|  Has links:  stakeholders|  Has Statuses: TBC|
| | | | |
| | |Has Custom Fields:  None| |
|Key Result|Measurable deliveries. An outcome would be broken down into specific and measurable Key Results|Has links:  Outcome                                                                                                  Has Custom Fields: None|  Has Statuses: TBC|
|LAPTOP|??|Has links:  tbc                                                                                         |  Has Statuses: |
| | | |·        Acquired|
| | |Has Custom Fields:  Display Size (inches), CPU Model, CPU Cores, CPU Speed (GHz), |·        In Operation|
| | |Total RAM Amount, RAM Speed, Model Name, Primary Drive Type, Primary Drive Capacity|·        Disposed|
|Learning|A issue type that states lessons learnt after an incident or project|Has link: Project, Incident, Sprint|  Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields:  None|·        In Progress|
| | | |·        Done|
|Limitation|Used to state what the designed system is unable to do as of its present state|Has link: Product, Feature| |
| | | | |
| | |Has Custom Fields:| |
|LOCATION|??| | |
|Meeting|Used to record a meeting's agenda, notes & outcomes|Has link: Any| Has Statuses: |
| | | |To Do|
| | |Has Custom Fields:  Agenda, Checklists|In Progress|
| | | |·        Done|
|MOBILE ASSET|??|Has link:  tbc|  Has Statuses: |
| | | | |
| | |Has Custom Fields:  None| |
|MONITOR|Used to record a monitor type asset?|Has link:  tbc|Has Statuses: |
| | | |·        Acquired|
| | |Has Custom Fields:  None|·        In Operation|
| | | |·        Disposed|
|MVP|A issue type that denotes a minimum viable product |Has link:  Customer, Feature, Question |  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields:  Shopify, COLLECTION|In Progress|
| | | |·        Done|
|NDA|A issue type for Non-Disclosure Agreement?|Has link:|  Has Statuses:|
| | | | |
| | |Has Custom Fields:| |
|Opportunity|Records related commercial opportunity of a Program|Has link: Program|  Has Statuses:|
| | | | |
| | |Has Custom Fields:| |
|Outcome|A issue type that shows the short-term objective of a project, or squad.|Has link: Key Result|  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields:|In Progress|
| | | |·        Done|
|Permission|Used to show the controlling and regulating access to a specific resource|Has link: tbc|   Has Statuses: |
| | | |·        Requested|
| | |Has Custom Fields: None|·        Granted|
| | | |·        Revoked|
|Person|A issue type for a person|Has link: Any |  Has Statuses: |
| | | |Active|
| | |Has Custom Fields:|·        Not Here Anymore|
|Personal Objective|Used to record the work-specific goals of a person|Has link: Person|  Has Statuses: |
| | | |New|
| | |Has Custom Fields: Objective-What, Objective-Why, Objective-Success Measure, Objective-Plan|In Progress|
| | | |·        Achieved|
|Playbook|Used to show a process workflow that reflect a plan, an approach or strategy defining predetermined responses worked out ahead of time|Has link: Playbook| |
| | | | |
| | |Has Custom Fields:| |
|Policy|This issue type records the organisation's formal set of statements that define standard expectations |Has link: tbc|  Has Statuses: |
| | | |Draft|
| | |Has Custom Fields: Policy |Awaiting Approval|
| | | |·        Under Review|
| | | |·        Approved|
|Problem|??|Has link: Any|  Has Statuses: |
| | | |Resolved|
| | |Has Custom Fields: Solution|In Investigation|
| | | |·        Unresolved|
|Product|This is Used to record something or a software that can be offered in the market to solve a problem or satisfy a need|Has link: Customer, Desired Feature, Bug, Project, Squad, Technical Owner, Technical Debt, Product Owner|  Has Statuses: |
| | | |Active|
| | |Has Custom Fields: Product Name, Product Type, Price, Compare at Price, Cost Per Item, Vendor, Product Description, GitHub Repo|Launched|
| | | |End of Life|
|Product Capability|Used to record the unique value or characteristic offered by a product|Has link: tbc|  Has Statuses: |
| | | |New Idea|
| | |Has Custom Fields:  tbc|·        In Progress|
| | | |·        Won’t Do|
|Product Feature|duplicates|Has link: Limitation, Capability, Story, Vulnerability|  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields:  tbc|Analysis|
| | | |Design|
| | | |Backlog|
| | | |In Development|
| | | |Testing|
| | | |Launched|
| | | |Not Done|
|Product Limitation|duplicates|Has link: Product|  Has Statuses: tbc|
| | | | |
| | |Has Custom Fields: None| |
|Program|Used to represent a group of related projects managed in a coordinated manner to obtain benefits not available from managing them individually|Has link: Projects, Product deliverables, Customer, Business owner, Program Manager|  Has Statuses: |
| | |Longer in duration than projects|To Do|
| | | |·        In Progress|
| | |Has Custom Fields: Updates, Objectives, GitHub Repo|·        Done|
|Project|Used to record a temporary endeavour undertaken to create a unique project service or result|Has link: Features, Business owner, Project Manager, Technical Owner                                                                                                                 Must have a start & end date|  Has Statuses: |
| | |Projects are temporary|Draft|
| | | |·        Needs Approval|
| | |Has Custom Fields: Updates, GitHub Repo, Objectives|·        Needs More Details|
| | | |·        Not Scheduled|
| | | |·        Scheduled|
| | | |·        Blocked|
| | | |·        In Progress|
| | | |·        Done|
|Question|Used to record the questions in any aspect of business that has the goal of providing an answer that would lead to improving quality, lowering cost, exploring new ideas etc..|Has link: Any|  Has Statuses: |
| | | |Asked|
| | |Has Custom Fields: Answer, Updates, Date Asked|Answered|
| | | |Not Answered|
|Recommendation|Used to record a suggestion or proposal that a course of action is good for a particular purpose|Has link: Any|  Has Statuses: |
| | | |Accepted|
| | |Has Custom Fields: None|Applied|
| | | |Rejected|
|RELEASE|Used to record the distribution of the final version of a software feature or product|Has link: Projects|  Has Statuses: |
| | | |·        Not Scheduled|
| | |Has Custom Fields:|·        Scheduled|
|Report|Used to record results, extracted data for visualisation & presentation to stakeholders|Has link: Asset, Feature, Product|  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields: tbc|·        In Progress|
| | | |·        Done|
|Request|Used to record a proposal to alter a product or system|Has link: Product|  Has Statuses: |
| | | |Analysis|
| | |Has Custom Fields: tbc|Feasible|
| | | |Not Feasible|
| | | |Need More Details|
|Requirement|Used to describe the functionalities expectations of users of a product or process |Has link: tbc|    Has Statuses: |
| | | |To Do|
| | |Has Custom Fields: Requirement|·        In Progress|
| | | |·        Done|
|Risk|Used to record the probability of a problem or any type of loss occurring caused by lack of time or information |Has link: Threat, Threat model|  Has Statuses: |
| | | |Active|
| | |Has Custom Fields: Security Level, Risk Impact, Risk Possibility, Date Registered, Risk Category, Proximity|·        Closed|
|Role|The function assumed, or part played by a person or thing in a situation. In some situations, this could be your job title, or something close to it, but not always. You could assume a role in a squad which is not aligned with your title.|Has link: Person|  Has Statuses: |
| | | |Active|
| | |Has Custom Fields: None|·        Closed|
|Scrum|Used to iterative progress toward a well-defined goal.|Has link: Project|  Has Statuses: |
| | | |Initiation|
| | |Has Custom Fields: tbc|·        Planning|
| | | |·        Implementation|
| | | |·        Review|
| | | |·        Released|
|Security Champions|States a person who promotes and defends project security|Has link: tbc|  Has Statuses: |
| | | |Active|
| | |Has Custom Fields: tbc|·        Not Here Anymore|
|Security Control|Used to record the proper protections to confidentiality, integrity, and availability of a system|Has link: Vulnerability, Feature, Threat|    Has Statuses: |
| | | |To Do|
| | |Has Custom Fields: None|In Progress|
| | | |Applied|
|Service accounts (I am)|??|Has link: tbc|  Has Statuses: tbc|
| | | | |
| | |Has Custom Fields: tbc| |
|SKILL|Used to show a ability required for developing, designing, testing, debugging a software based off specific requirements.|Has link: Person|  Has Statuses: |
| | | |Beginner|
| | |Has Custom Fields: None|Intermediate|
| | | |Expert|
|Slack|Used to record the slack channel used for a project or squad??|  Has link: tbc|  Has Statuses: tbc|
| | | | |
| | |Has Custom Fields: tbc| |
|SOFTWARE|??|Has link: tbc|Has Statuses: |
| | | |·        Acquired|
| | |Has Custom Fields:  License, License Renewal Date, Expiry Date|·        In Operation|
| | | |·        Disposed|
|Solution|Used to record the suggested implementation to solve a business problem|Has link:  tbc| |
| | | | |
| | |Has Custom Fields:  tbc| |
|SOW|Used to record a Statement of Work of a project|Has link: Bug, Sow|  Has Statuses: |
| | | |·        To Do|
| | |Has Custom Fields:  Verification Method, Setup, Expected Results, Actual results, Updates, Design Text, Content Status, SoW order, SectionId, EnhancementId|·        Unable To Test|
| | | |·        Blocked|
| | | |·        Compliant With Bugs|
| | | |·        Content Design|
| | | |·        In Progress|
| | | |·        Non-Compliant|
| | | |·        Partially Compliant|
|Sprint|Used to show the repeatable work cycles of a project that are limited in time|Has link:  tbc|  Has Statuses: |
| | | |Initiation|
| | |Has Custom Fields: Start Date, End Date|·        Planning|
| | | |·        Implementation|
| | | |·        Review|
| | | |·        Released|
|Squad|Vertical group of roles that deliver an outcome. A squad is cross-functional and constitutes all roles needed to deliver its outcomes end to end.|Has link: squad developers; squad stakeholders; squad leader; customers|  Has Statuses: |
| | | |·        Active|
| | |Has Custom Fields:  Updates|·        Disbanded|
| | |Has link: Characteristics                                                                                                                |  Has Statuses: |
| | | |·        Planning|
| | |Has Custom Fields: Updates|·        Analysis|
| | | |·        Implementation|
| | | |·        Monitoring|
| | | |·        Internal Audit|
| | | |·        External Audit|
|Story|Shows the description of a product, feature or requirement from a user's perspective|Has link: Feature, Task                                                                                                             |      Has Statuses: |
| | | |To Do|
| | |Has Custom Fields: Acceptance Criteria, Updates, Work Delivered, GitHub Repo, Time tracking|·        In Progress|
| | | |·        Done|
|Supplier|Shows organisations from whom services are required for a project|Has link: tbc|  Has Statuses: |
| | | |·        Active|
| | |Has Custom Fields:  Email, Signatory, Address, Contact person, website|·        Not Used|
|Task|Describes a single action required to be completed for the implementation of a Story in a project|Has link: Story|  Has Statuses: |
| | | |Backlog|
| | |Has Custom Fields:  Updates|To Do|
| | | |Cancelled|
| | | |·        Under Review|
| | | |·        Done|
| | | |·        Not Done|
| | | |·        In Progress|
|Team|Horizontal group of people that have a common competency area. E.G. Cloud Dev, Core QA, SRE. This is your existing line management structure.|Has link: members|  Has Statuses: |
| | | |·        Active|
| | |Has Custom Fields: None|tbc|
|Technical Debt|Used to record left over implementation or non-fixed issues in a product's design and development|Has link: |  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields:|·        In Progress|
| | | |·        Done|
|Technology Goal|States required ability to use technology efficiently to get work done|Has link: tbc|  Has Statuses: |
| | | |On Track|
| | |Has Custom Fields: None|Progressing|
| | | |Off Track|
| | | |·        Completed|
|Technology Platform|Used to refer to the software or hardware platforms on which technical architecture of a product is laid out|Has link: tbc|  Has Statuses: tbc|
| | | | |
| | |Has Custom Fields: None| |
|TestAzureDevopsLink|A test issue type to test the linking between Azure DevOps feature & Jira feature|Has link:| |
| | | | |
| | |Has Custom Fields:| |
|Tests|Used to define the executions steps, expected & actual results of a feature testing|Has link: Story, Feature or SOW|  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields:|·        In Progress|
| | | |·        Test Passed|
| | | |·        Test Failed|
| | | |·        Done|
|Threat|Used to describe a potential negative action or event facilitated by a vulnerability that results in unwanted impact to a product or system|Has link: Risk, Security Control, Threat Model|  Has Statuses: |
| | | |·        Mitigation in progress|
| | |Has Custom Fields: None|·        Resolved|
|Threat Actor|Used to note a Person or group of people partially or wholly responsible for a threat incident that impacts the security of a system|Has link: Vulnerability|  Has Statuses: |
| | | |N/A|
| | |Has Custom Fields: None| |
|Threat Model|Used to record the defined countermeasures & mitigation techniques to protect a designed product & it's resources|Has link: Task, Risk, Asset, Security Control|  Has Statuses: |
| | |Uses: Playbook|To Do|
| | | |·        In Progress|
| | |Has Custom Fields:|·        Done|
|Timeline|Used to display of a list of events to occur in chronological order for the completion of a program or project|Has link: Milestone|  Has Statuses: |
| | | |  N/A|
| | |Has Custom Fields:  Event Date| |
|Topic|Used to state a subject of conversation or discussion|Has link: tbc|  Has Statuses: |
| | | | tbc|
| | |Has Custom Fields: None| |
|Training|Used to define the acquisition of a knowledge, skill to support a project work or a onboarding|Has link:|  Has Statuses: |
| | | |To Do|
| | |Has Custom Fields: None|·        In Progress|
| | | |·        Done|
|Tribe|A collection of squads that cover the same business area. E.G. Glasswall Engine, SaaS|Has link: Squad|  Has Statuses: |
| | | |·        Active|
| | |Has Custom Fields: None|·        Disbanded|
|Trust Boundary|Used to define the thrust constraints of a product or system|Has link:  Trust Boundary|  Has Statuses:|
| | | | N/A|
| | |Has Custom Fields: None| |
|Variant|?? tbc|Has link: thc|  Has Statuses:|
| | | | N/A|
| | |Has Custom Fields: None| |
|Viable Product|A issue type that denotes a viable product |Has link:|    Has Statuses: |
| | | |·        Incubating|
| | |Has Custom Fields: None|·        Active|
| | | |·        End of Life|
|Vulnerability|A weakness which can be exploited by a threat actor to perform unauthorized actions |Has link:  thc|  thc|
| | | | |
| | |Has Custom Fields:  thc| |
|Deliverables|Artefacts produced as a result of work done on a project that is intended to be delivered to a customer |Has link:  thc| tbc|
| | | | |
| | |Has Custom Fields:  thc| |
|Dependency|Refers to the coupling view of issue type that relies on each one of the other|Has link:  thc| tbc|
| | | | |
| | |Has Custom Fields:  thc| |
|Project brief|Used to record the statement that describes the purpose, cost, time and performance requirements/constraints for a project.|Has link:  thc| tbc|
| | | | |
| | |Has Custom Fields:  thc| |
