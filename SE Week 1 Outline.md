# Project Management
1. Definition: skills, tools, and management processes required to undertake a project successfully
    * Skills: experience and specialised knowledge required for success and risk minimisation
    * Tools: Assist
    * Processes: minimise risk, control time, quality, scope, and cost
2. Phases
    * Project Initiation
    * Project Planning
    * Project Execution 
    * Project Closure
3. Uncertainty
    * Uncertainty is greatest when scope (what) is very large and tech (how) is very large
4. Budget, Schedule, and Resources
    * Cost, schedule, and resources will determine project progress - a lack in any given area will require trying to make it up in other areas
        * Resources: conduct a resources assessment to determine the current resources that are reducing risk factors and increasing protective factors
            * To make a resources assessment, consider assumptions about resources (full time, part time), equipment, location, and outside resources/support
        * Schedule: current status: high-level overview of progress against schedule
            * Current status should consider where the project is behind, on-time, and ahead
            * Schedule should anticipate unexpected delays to the degree possible
            * Schedule should keep in mind the final date for delivery
            * Project Scheduling should split project into tasks and estimate time and resources for each task; organise tasks concurrently to make best use of resources; minimise task dependencies to avoid blocking
            * The project scheduling process is generally: 1) identify activities (from software requirements and design information); 2) identify dependencies; 3) estimate resources for activities; 4) allocate people to activities; 5) create project charts (bar charts describing the project schedule)
        * Cost is dependent on client contract
5. Activity Network Diagram
    * Also called arrow diagram, network diagram, activity chart
    * Shows the required order of tasks in a project or process, the best schedule for the entire project, and potential scheduling and resource problems and their solutions
    * Allows someone to calculate the critical path of the project
        * Critical path shows where delays will affect the timing of the entire project and where addition of resources can speed up the project
    * When to use an Activity Network Diagram: 
        * When scheduling and monitoring tasks within a complex project or process with interrelated tasks and resources
        * When you know the steps of a project, how long each step will take, and what order they have to be taken in
        * When schedule is critical to the success of the project
6. PDSA (Deming) Cycle
    * P(lan): study current situation
        * After planning, should have an action plan, list of risks, preventive actions, and agreement on how to proceed
    * D(o): implement plan on trial basis
    * S(tudy/Check) : determine if trial is working correctly
    * A(ct): standardize improvements
7. Quality Assurance and Standards
    * Key to effective quality management
    * Might be international, organisational, or something else
    * Product standards relate to how components of the project should behave
    * Process standards relate to how product processes are enacted
    * The quality of the production process will affect the quality of the finished product
8. Processes
    * Definition: a set of activities with a specified beginning and end that, in concert with the resources of an organisation, adds value to a measurable object from a supplier to a predetermined measurable result to a customer
    * Individual processes are carried out by individuals
    * Vertical processes are associated with a certain department or unit
    * Horizontal processes cut across a company and involve multiple departments or units
9. How to Maintain Process Quality
    * Define process standards (like how reviews are carried out)
    * Monitor to ensure that standards are maintained
    * Report on the process to project management 
    * Don't use processes that aren't working (just because they're there)
    * Steps:
        1. Define process
        2. Develop product
        3. Assess product quality
        4. If quality is good, standardize the process
        5. If quality isn't good, improve the process and then start over with developing the product

# Software Development Life Cycle (SDLC)
1. Number and type of stages in a system's life cycle can vary, but primary stages are conception, development, and maintenance
    * SDLC deals with the development phase
2. Software Development Process
    * Analysis
        * Translate user needs into system requirements
        * Involves studying current procedures and systems
        * Eliminate redundancies
        * One process is to generate alternative designs, compare those alternatives, and then choose the best
    * Design
        * Begins with problem statement and ends with design that can be turned into an operational system
        * Bulk of development process
        * Goal: to construct a solution by determining the overall *architecture* of the system, partition the software into components, and identify the relationships and dependencies between them
        * Deliverables: System design document and detailed design document, along with various diagrams
    * Implementation
        * Takes design and turns it into an operational system that meets user needs
        * Must consider equipment, procedure, users, etc - how system will work in its operational environment
        * Might (probably) involve unit testing
        * Goal is to implement the design and then test each component to make sure that it functions correctly before it's integrated with the other components
        * Deliverables: source code and unit testing documentation
    * General Model of the Design Process:
        * Inputs:
            * Platform Information
            * Requirements Specification
            * Data Description
        * Design Activities:
            * Architectural Design
            * Interface Design
            * Component Design
            * Component and Architectural Design lead to Database Design
        * Outputs:
            * System Architecture
            * Database Specification
            * Interbase Specification
            * Component Specification
    * VS Methodology
        * SDLC refers to a natural stage in a system's lifecycle
        * By contrast, a methodology is an attempt to control the naturally occurring events
        * A methodology is a set of steps, guidelines, activities, and/or principles to follow in a situation

# Software Models
1. Waterfall Model
    * Separate and distinct phases of specification and development
    * Specification, validation, and development are interleaved
    * Many varieties of waterfall models
    * General process:
        1. Requirements Definition
        2. System and Software Design
        3. Implementation and Unit Testing
        4. Integration and System Testing
        5. Operation and Maintenance
    * Each phase is finished before continuing to the next
    * Milestone and deliverable at each step
    * Problems:
        * Partitioning into inflexible stages makes adjusting to customer feedback very difficult
        * Only appropriate when requirements are well understood and few changes will be made during development
        * Note that few business systems have that much stability
        * Cannot begin next phase until feedback is received from the previous phase
        * Handling risk is not part of the model (risk is pushed forward instead)
2. Agile Methods
    * Principles
        1. Customer involvement: customers are involved throughout the process, providing updated requirements and other feedback on iterations
        2. Incremental delivery: developed in increments with customery specifying the requirements for each increment
        3. People not process: team members should be utilized according to their skills and not micro-managed
        4. Embrace change
        5. Maintain simplicity: strive for simplicity in product and design
    * Involves iterative development, incremental development, or both 
    * Iterative Development
        * Consists of a number of successful iterations
        * Each iteration produces a working program
        * System is built incrementally
        * Facilitates and manages changes
        * Examples: RUP and Spiral models
            * RUP: Rational Unified Process
            * blend of 3 generic process models, developed from UML
    * Incremental Development
        * Outline description turns into 
        * the concurrent activities of specification, development, and validation
        * Steps:
            1. Define outline requirements
            2. Assign requirements to increments
            3. Design system architecture
            4. Develop system increment
            5. Validate increment
            6. Integrate increment
            7. Validate system
            8. Deploy increment
            9. Repeat 4-8 until the system is complete
    * XP
        * Stands for eXtreme Programming
        * Developers are paired off for all aspects of work
            * Pairing determination has no single standard
        * Full time customer engagement with team
        * Regular system releases
        * Maintains simplicity through constant refactoring of code
        * All requirements are expressed as scenarios
        * Implemented as a series of tasks
        * Documentation is written during development
    * Scrum
        * Iterative and incremental agile framework
        * Focuses on project management situations where it's difficult to plan ahead
        * Empirical process control - feedback loops are used
        * Main roles
            * Scrum master: maintains the processes
            * Product owner: represents the stakeholders
            * Team: 4-7 people who design, develop, test, implement, etc system
        * Method
            * Team Roles
                * Development Team
                    * Cross functional, no titles, no leader, self organized
                    * Iterations = sprints
                        * A sprint is 30 days or less
                        * No time between sprints
                * Product Owner
                    * Prioritizes and manages the product backlog
                    * Manages the ROI (Return on Investment)
                    * Interfaces with the customer
                    * Not in charge of the team
                * Scrum Master
                    * Makes sure the team follows scrum practices/values
                    * Runs meetings
                    * Protects the team from disturbances
                    * Collects and removes obstacles (impediments)
                    * Can be part of the team, but cannot be the product owner
                    * Does not give orders to the team (the team runs itself)
            * Artifacts
                * Product backlog
                    * List of PBI (product backlog items)
                    * Prioritized
                    * Available
                    * Never complete
                    * Features, bug fixes, documentation, tests, etc
                    * Product Owner is responsible for it, but everyone can add to it
                    * Each PBI includes title, scenario, value, estimate
                * Sprint backlog
                * Impediment List
                    * Only track hours remaining, not hours worked
            * Events
                * Sprint planning
                    * Chart with tasks, in progress, blocked, complete
                * Daily scrum
                    * Stand up meeting that scrum master runs
                    * Same place and time every day
                    * Everyone talks for 1-2 minutes
                        * What they did yesterday
                        * What they're doing today
                    * NOT for solving problems
                * Sprint review
                    * Around 4 hours, done at end of each sprint
                    * Team, scrum master, and product owner (might also include customer)
                    * Informal meeting about what's been done
                    * Demonstrations of working functionality, not powerpoint presentations
                * Sprint retrospective
                    * Around 3 hours
                    * Purpose is to consider the last sprint and how things went
                    * Choose another chunk of the backlog and start the process over
        * Done
            * Tools to help determine this
    
# Requirements
* A requirement is a desired function or property of a system or product
    * Client or customer needs or wishes
    * What the system or product must do or solve
    * Functionalities
    * What qualities the system or service has
    * Describe what the supplier must meet in their delivery
* Requirements can be expressed in terms of goal images
* Requirements must be measurable
* Requirements are often vague
* How to gather requirements:
    * Understand the current state
        * Gather system and process details
        * Review applications and processes
        * Review documentation
        * Reverse engineer current state of application
        * Document findings: user scenarios, paper prototype of future application, draft initial requirements
    * Define the future state
        * Gather user details
            * Conduct interviews
            * User task/job analysis
            * Workshops for brainstorming and prototyping
* Requirement process activities
    * Requirements discovery
        * Interact with stakeholders to discover requirements
        * Establish domain requirements
    * Requirements classification and organisation
        * Group requirements and organize into logical clusters
    * Prioritisation and Negotiation
        * Prioritize and resolve conflicting requirements
    * Requirements documentation
        * Document and put into next round of spiral
* Requirements definition/specification
    * Definition: statement in natural language plus diagrams of system services and operational constraints (for customers)
    * Specification: structured document setting out detailed description of system services (contract between client and contractor)
    * Software specification: detailed software description that can serve as basis for design or implementation (for developers)
* Scenario
    * Description of what the system and user expects when the scenario starts
    * Description of normal flow of events in scenario
    * What can go wrong and how handled
    * Info about other activities that might be happening at the same time
    * Description of system state when scenario finishes
* Requirements Checking
    * Validity
    * Consistency
    * Completeness
    * Realism (is budget/resources sufficient to realize requirements)
* Types of Requirements
    * Functional: what system must do
    * Non-Functional
    * Data
    * Graphical Interface
    * Usability
* Requirements Evolution
    * Requirements systematically reviewed for errors and inconsistencies
    * Prototyping: executable model demo'd to end-users to see if it meets their needs
    * Test-case generation: Reqs must be testable; if test is difficult to develop, probably issue with the requirement

# Requirement Change Management
* Process must recognize and address changes
* Internal or external factors may prompt change in requirements
* Process for managing change:
    1. Recognize that change is inevitable and plan for it as much as possible
    2. Baseline the requirements
    3. Establish a single channel to control changes
    4. Use a change control system to capture changes
    5. Manage change hierarchically 
* Change Request Flow
    * Requests for change may come from
        * Customer/end-user
        * Marketing
        * Developers
        * Testers
        * Others
    * Regardless of origin, change should go through firewall (not just be automatically accepted)
    * If passes firewall, go to change request system
    * After change approved:
        * New feature
        * New requirement
        * Modify design
        * Fix bug
        * Fix test
* Ripple Effect
    * imagine throwing a stone in a lake, and all these ripples come out from it
    * every time someone wants to change a req, the ripples come out
        * must understand the ripple:
            * identify who threw the stone
            * where is it a specification, where is it a feature
                * is it a feature, going to original documentation
                * specification: doesn't change model/reqs - just changing a feature 
                * what kind of ripple
            * if we must change design, we're changing features
            * feature vs specification
                * feature needs new design model, whole new round of design specs 
                * specification is just something added, doesn't require change of underlying model
* Requirements Change Management
    * Applies to all proposed changes to requirements
    * Stages:
        1. Problem analysis: discuss and propose change
        2. Change analysis and costing: determine impact on other requirements
        3. Change implementation: modify requirements document and other documents to reflect change
* Requirements Management
    * Deals with the process of managing changes in the requirements during the requirements engineering process and system development
    * Requirements traceability is concerned with the relationships between requirements (dependencies), their sources, and the design system
