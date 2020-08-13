| | | |
|-|-|-|
|**Jira Issue Type Dictionary**| | |
|**Issue Type**|**Definition**/**Purpose**|**Rules/Characteristics/Relationships|**
|**Access**|Used to state the type of authority or permission to obtain restricted information.|Is child link of: Role|
|**Action**|Used to state a step that must be taken in order to achieve a specific goal.|Is child link of: Any issue|
|**Alert**|This issue type states a notification which indicates that a predefined event or error condition has occurred and that some action is needed|Is child link of: Story, feature, Product|
|**ASSET TYPE**|States the kind or category of a company asset|Is child link of: IT Asset|
|**Assets**|Used to state what asset is currently related to a product, project or vulnerability|Is child link of: Component|
|**AWS ACCOUNTS**|Used to state which AWS Account is currently in use for the related issue| |
|**Backlog**|This issue type states a list of tasks required to support a larger strategic plan. In a product development context, it contains a prioritized list of items that the team has agreed to work on next. Typical items on a product backlog include user stories, changes to existing functionality, and bug fixes.                                                                                  Provide a single source of truth for the team’s planned work                            Facilitate team discussions  Make it easier to assign work|Is child link of:  Feature, Story, Bug, Task         Has parent link: Backlog|
|**Bug**|States a problem or fault in a program which causes failure or deviation from expected results. It provides a link between features & related bugs, Provides a template to define the steps to replicate the problem|Is child link of: Feature, Story, SOW|
|**Business Objective**|This issue type shows a specific result aimed to be achieved throughout a period|Is child link of: Project|
|**Change**|A change is the process of moving a project, product or feature current specifics to new ones; This issue type shows the new specifics to work with| |
|**Checklist**|This issue type shows a list of items to be checked for the successful completion of a task|Is parent link of:   Any issue                            Is child link of:  Any issue|
|**CLOUD ASSET**|Used to state a Cloud based IT Asset| |
|**Completed Outcomes**|Completed outcomes are measurable statements that demonstrates a set goal have been reached;  This issue type is used to show that a specific outcome has been completed|Is parent link of:   Outcome                                              Is child link of:       Squad|
|**Component**|This issue type states a uniquely identifiable input to be included as a part of a finished product| |
|**COVID**|Used to manage covid related issues| |
|**Customer**|A client of the organisation or an internal customer. All squads should have customers/clients. These are the consumers of the delivered outcome. Who will use what is being delivered|Can be linked to an Entity, Project or Customer |
|**Decision**|Used to  state the choice made between alternative courses of action in a situation of uncertainty.|Can be linked to any issue type|
|**Decision Tree**|Used to  show a course of action representing the decisions, outcomes or reactions in a given situation| |
|**Design**|Used to record design project work| |
|**Domain**|Used to show the core knowledge of a product or business| |
|**Entity**|A issue type that has a unique and separate existence|Entity have stakeholders.|
|**Equipment**|Used to record any signed equipment|Linked to Person|
|**Event**|A issue type that refers to an action or occurrence that affects a project & can be reasonably measured| |
|**Fact**|A issue type that denotes a observed state or information item known to have happened & confirmed or validated to such an extent that it is considered a reality.| |
|**FAQ**|Used to  state the frequently asked questions on a product, project, use case ect..| |
|**Feature**|A issue type that states a specific software attribute that represents a product or system functionality |Feature has Story, is linked to a Project|
|**Focus**|A issue type that shows the center of activity, attraction, or attention of a Program or project|Focus has Program or Projects|
|**Gaming**|??| |
|**GitHub**|??| |
|**Github Organization**|??| |
|**Github Users**|??| |
|**Group Goal**|??| |
|**Guild**|A lightweight community of interest where people across the whole company gather and share knowledge of a specific area. Anyone can join or leave a Guild at any time. For example, ‘React’, ‘Performance’|Guilds have members|
|**HARDWARE**|???| |
|**Hat**|Used to classify a squad as working at Pioneer, Settler or Town planner level|Linked to Squad|
|**Hypothesis**|This issue type states a supposition or theory that is provisionally accepted in order to interpret certain events and to provide guidance for further investigation |Is linked to any issue|
|**IAM**|This issue type shows the AWS Identity & Access Management permission of a ressource| |
|**Incident**|This issue type describes an event that disrupts the normal operations of a system, the daily business & services | |
|**Industry**|??| |
|**InfoSecScrum**|??| |
|**IT Asset**|A company-owned information, system or hardware that is used for company activities|Has Asset|
|**IT Helpdesk**|??| |
|**IT Onboarding**|Used to  record the activities & processes for the integration a new employee into the organization|Is linked to a Person, has Training, Team, Squad|
|**IT System**|A system or platform which staff use and have accounts on. These systems are owned and managed by our IT team. For example, ‘Jira’, ‘GitHub’|IT Systems have stakeholders.|
|**Jira**|??| |
|**Key Result**|Measurable deliveries. An outcome would be broken down into specific and measurable Key Results|Has parent link: Outcome                       Has child link: Task|
|**LAPTOP**|??| |
|**Learning**|A issue type that states lessons learnt after an incedent or project|Has parent link: Project, Incident, Sprint|
|**Limitation**|Used to  state what the designed system is unable to do as of its present state|Has link: Product, Feature|
|**LOCATION**|??| |
|**Meeting**|Used to record a meeting's agenda, notes & outcomes|Can be linked to any issue type|
|**MOBILE ASSET**|??| |
|**MONITOR**|Used to  record a monitor type asset?| |
|**MVP**|A issue type that denotes a minimum viable product |Has Customer, Feature, Question |
|**NDA**|a issue type for Non Disclosure Agreement?| |
|**Opportunity**|Records related commercial opportunity of a Program|Linked to Program|
|**Outcome**|A issue type that shows the short term objective of a project, or squad.|Has Key Result|
|**Permission**|Used to  show the controlling and regulating access to a specific resource| |
|**Person**|A issue type for a person| |
|**Personal Objective**|Used to  record the work-specific goals of a person|Linked to Person|
|**Playbook**|Used to  show a process workflows that reflect a plan, an approach or strategy defining predetermined responses worked out ahead of time|Linked to Playbook|
|**Policy**|This issue type records the organisation's formal set of statements that define standard expectations | |
|**Problem**|??| |
|**Product**|This is Used to  record something or a software that can be offered in the market to solve a problem or satisfy a need|Linked to Customer, Project, Squad & other|
|**Product Capability**|Used to record the unique value or characteristic offered by a product| |
|**Product Feature**|duplicates| |
|**Product Limitation**|duplicates| |
|**Program**|Used to represent a group of related projects managed in a coordinated manner to obtain benefits not available from managing them individually|Has Projects, Product deliverable Longer in duration than projects|
|**Project**|Used to record a temporary endeavor undertaken to create a unique project service or result|Has Features                                               Must have a start & end date Are temporary|
|**Question**|Used to record the questions in any aspect of business that has the ultimate goal of providing an answer that would lead to improving quality, lowering cost, exploring new ideas ect..|Linked to any issue type|
|**Recommendation**|Used to record a suggestion or proposal that a course of action is good for a particular purpose|Linked to any issue type|
|**RELEASE**|Used to record the distribution of the final version of a software feature or product|Linked to Projects|
|**Report**|Used to record results, extracted data for visualisation & presentation to stakeholders| |
|**Request**|Used to record a proposal to alter a product or system| |
|**Requirement**|Used to describe the functionalities expectations of users of a product or process | |
|**Risk**|Used to record the probability of a problem or any type of loss occuring caused by lack of time or information | |
|**Role**|The function assumed, or part played by a person or thing in a situation. In some situations this could be your job title, or something close to it, but not always. You could assume a role in a squad which is not aligned with your title.| |
|**Scrum**|Used to iterative progress toward a well-defined goal.| |
|**Security Champions**|States a person who promotes and defends project security| |
|**Security Control**|Used to record the proper protections to confidentiality, integrity, and availability of a system| |
|**Service accounts (I am)**|??| |
|**SKILL**|Used to show a ability required for developing, designing, testing, debugging a software based off specific requirements.| |
|**Slack**|Used to record the slack channel used for a project or squad??| |
|**SOFTWARE**|??| |
|**Solution**|Used to record the suggested implementation to solve a business problem| |
|**SOW**|Used to record a Statement of Work of a project| |
|**Sprint**|Used to show the repeatable work cycles of a project that are limited in time| |
|**Squad**|Vertical group of roles that deliver an outcome. A squad is cross-functional and constitutes all roles needed to deliver its outcomes end to end.|Squads have - squad developers; squad stakeholders; squad leader; customers|
|**Story**|Shows the description of a product, feature or requirement from a user's perspective|Has parent: Feature                                                Has child: Task|
|**Supplier**|Shows organisations from whom services are required for a project| |
|**Task**|Describes a single action required to be completed for the implementation of a Story in a project| |
|**Team**|Horizontal group of people that have a common competency area. E.G. Cloud Dev, Core QA, SRE. This is your existing line management structure.|Teams have members|
|**Technical Debt**|Used to record left over implementation or non fixed issues in a product's design and development| |
|**Technology Goal**|States required ability to use technology efficiently to get work done| |
|**Technology Platform**|Used to refer to the software or hardware platforms on which technical architecture of a product is laid out| |
|**TestAzureDevopsLink**|A test issue type to test the linking between Azure Devops feature & Jira feature| |
|**Tests**|Used to define the executions steps, expected & actual results of a feature testing|Linked to Story, Feature or SOW|
|**Threat**|Used to describe a potential negative action or event facilitated by a vulnerability that results in unwanted impact to a product or system| |
|**Threat Actor**|Used to note a Person or group of people partially or wholly responsible for a threat incident that impacts the security of a system| |
|**Threat Model**|Used to record the defined countermeasures & mitigation techniques to protect a designed product & it's resources| |
|**Timeline**|Used to display of a list of events to occur in chronological order for the completion of a program or project| |
|**Topic**|Used to state a subject of conversation or discussion| |
|**Training**|Used to define the acquisition of a knowledge, skill to support a project work or a onboarding| |
|**Tribe**|A collection of squads that cover the same business area. E.G. Glasswall Engine, SaaS| |
|**Trust Boundary**|Used to define the thrust constraints of a product or system| |
|**Variant**|??| |
|**Viable Product**|A issue type that denotes a viable product | |
|**Vulnerability**|A weakness which can be exploited by a threat actor to perform unauthorized actions | |
