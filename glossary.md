# ISTQB GLOSSARY V4

## SOURCE:
<https://glossary.istqb.org/en_US/search?term=&exact_matches_first=true>

## 01 Fundamentals of testing

**(test) coverage**
* The degree to which specified *coverage items* are exercised by a test suite, expressed as a percentage.

**debugging**
* The process of finding, analyzing and removing the causes of *failures* in a component or system.

**defect**
* An imperfection or deficiency in a work product where it does not meet its requirements or specifications.
* synonyms: *bug*, *fault*

**error**
* A human action that produces an incorrect result.
* synonyms: mistake

**failure**
* An event in which a component or system does not perform a required function within specified limits.

**quality**
* The degree to which a work product satisfies stated and implied needs of its stakeholders.

**quality assurance / QA**
* Activities focused on providing confidence that quality requirements will be fulfilled.
* also see: **quality management**
  + The process of establishing and directing a quality policy, quality objectives, quality planning, *quality control*, *quality assurance*, and quality improvement for an organization.

**root cause**
* A source of a *defect* such that if it is removed, the occurrence of the *defect* type is decreased or removed.

**test analysis**
* The activity that identifies *test conditions* by analyzing the *test basis*.

**test basis**
* The body of knowledge used as the basis for *test analysis* and *test design*.

**test case**
* A set of preconditions, inputs, actions (where applicable), expected results and postconditions, developed based on *test conditions*.

**test completion**
* The activity that makes testware available for later use, leaves test environments in a satisfactory condition and communicates the results of testing to relevant stakeholders.

**test condition**
* A testable aspect of a component or system identified as a basis for testing.
* synonyms: test situation, test requirement

**test control**
* The activity that develops and applies corrective actions to get a test project on track when it deviates from what was planned.
* also see: **test management**
  + The process of planning, scheduling, estimating, monitoring, reporting, controlling, and completing test activities.

**test data**
* Data needed for test execution.
* synonyms: test dataset

**test design**
* The activity that derives and specifies *test cases* from *test conditions*.

**test execution**
* The activity that runs a test on a component or system producing actual results.

**test implementation**
* The activity that prepares the testware needed for *test execution* based on *test analysis* and *test design*.

**test monitoring**
* The activity that checks the status of testing activities, identifies any variances from planned or expected, and reports status to stakeholders.
* also see: **test management**
  + The process of planning, scheduling, estimating, monitoring, reporting, controlling, and completing test activities.

**test object**
* The work product to be tested.
* also see: **test item**
  + A part of a *test object* used in the test process.

**test objective**
* The purpose for testing.
* synonyms: test goal

**test planning**
* The activity of establishing or updating a *test plan*.
* **test plan**
  + Documentation describing the *test objectives* to be achieved and the means and the schedule for achieving them, organized to coordinate testing activities.

**test procedure**
* A sequence of test cases in execution order, and any associated actions that may be required to set up the initial preconditions & any wrap up activities post execution.

**test result**
* The consequence/outcome of the execution of a test.
* synonyms: outcome, test outcome, result

**testing**
* The process within the software development lifecycle that evaluates the quality of a component or system and related work products.
* also see: **quality control / QC**
  + Activities designed to evaluate the quality of a component or system.

**testware**
* Work products produced during the test process for use in planning, designing, executing, evaluating and reporting on testing.

**validation**
* Confirmation by examination that a work product matches a stakeholder's needs.

**verification**
* Confirmation by examination and through provision of objective evidence that specified requirements have been fulfilled.

## 02 Testing throughout the software development lifecycle

**acceptance testing**
* A *test level* that focuses on determining whether to accept the system.
* also see: **user acceptance testing / UAT**
  + A type of acceptance testing performed to determine if intended users accept the system.

**black-box testing**
* Testing based on an analysis of the specification of the component or system.
* synonyms: specification-based testing

**component integration testing**
* The integration testing of components.
* synonyms: module integration testing, unit integration testing

**component testing**
* A *test level* that focuses on individual hardware or software components.
* synonyms: module testing, unit testing

**confirmation testing**
* A type of change-related testing performed after fixing a *defect* to confirm that a *failure* caused by that *defect* does not reoccur.
* synonyms: re-testing

**functional testing**
* Testing performed to evaluate if a component or system satisfies functional requirements.

**integration testing**
* A *test level* that focuses on interactions between components or systems.

**maintenance testing**
* Testing the changes to an operational system or the impact of a changed environment to an operational system.

**non-functional testing**
* Testing performed to evaluate that a component or system complies with non-functional requirements.

**regression testing**
* A type of change-related testing to detect whether *defects* have been introduced or uncovered in unchanged areas of the software.

**shift-left**
* An approach to performing testing and *quality assurance* activities as early as possible in the software development lifecycle.

**system integration testing**
* The integration testing of systems.

**system testing**
* A *test level* that focuses on verifying that a system as a whole meets specified requirements.

**test level**
* A specific instantiation of a test process.
* synonyms: *test stage*

**test object**
* The work product to be tested.
* also see: **test item**
  + A part of a test object used in the test process.

**test type**
* A group of test activities based on specific *test objectives* aimed at specific characteristics of a component or system.

**white-box testing**
* Testing based on an analysis of the internal structure of the component or system.
* synonyms: clear-box testing, code-based testing, glass-box testing, logic-coverage testing, logic-driven testing, structural testing, structure-based testing

## 03 Static testing

**anomaly**
* A condition that deviates from expectation.

**dynamic testing**
* Testing that involves the execution of the **test item**.
* also see: **static testing**

**formal review**
* A type of review that follows a defined process with a formally documented output.

**informal review**
* A type of review that does not follow a defined process and has no formally documented output.

**inspection**
* A type of formal review that uses defined team roles and measurement to identify *defects* in a work product, and improve the review process and the software development process.
* also see: **peer review**
  + A review performed by others with the same abilities to create the work product.

**review**
* A type of *static testing* in which a work product or process is evaluated by one or more individuals to detect **defects** or to provide improvements.

**static analysis**
* The process of evaluating a component or system without executing it, based on its form, structure, content, or documentation.

**static testing**
* Testing that does not involve the execution of a *test item*.
* also see: **dynamic testing**
  + Testing that involves the execution of the *test item*.

**technical review**
* A formal review by technical experts that examine the quality of a work product and identify discrepancies from specifications and standards.
* also see: **peer review**

**walkthrough**
* A type of review in which an author leads members of the review through a work product and the members ask questions and make comments about possible issues.
* synonyms: structured walkthrough

## 04 Test anaysis and design

**acceptance criteria**
* The criteria that a component or system must satisfy in order to be accepted by a user, customer, or other authorized entity.

**acceptance test-driven development**
* A collaboration-based test-first approach that defines acceptance tests in the stakeholders' domain language.
* also see: **specification by example (SBE)**
  + A development technique in which the specification is defined by examples
  + see [Wkipedia](https://en.wikipedia.org/wiki/Specification_by_example)

**black-box test technique**
* A *test technique* based on an analysis of the specification of a component or system.
* synonyms: black-box test design technique, specification-based test technique

**boundary value analysis**
* A *black-box test technique* in which test cases are designed based on boundary values.
* also see: **boundary value**
  + A minimum or maximum value of an ordered **equivalence partition**.
    - A subset of the value domain of a variable within a component or system in which all values are expected to be treated the same based on the specification.
    - synonyms: equivalence class

**branch coverage**
* The coverage of branches in a*control flow graph*.
  + ?
  + **control flow**: The sequence in which operations are performed by a business process, component or system.

**checklist-based testing**
* An experience-based *test technique* in which test cases are designed to exercise the items of a checklist.

**collaboration-based test approach**
* An approach to testing that focuses on defect avoidance by collaborating among stakeholders.

**coverage**
* The degree to which specified coverage items are exercised by a test suite, expressed as a percentage.
* synonyms: test coverage

**coverage item**
* An attribute or combination of attributes derived from one or more *test conditions* by using a *test technique*.
* also see: **coverage criteria**
  + The criteria to define the coverage items required to reach a *test objective*.

**decision table testing**
* A *black-box test technique* in which test cases are designed to exercise the combinations of conditions and the resulting actions shown in a decision table.

**equivalence partitioning**
* A *black-box test technique* in which *test conditions* are equivalence partitions exercised by one representative member of each partition.
* synonyms: partition testing

**error guessing**
* A *test technique* in which tests are derived on the basis of the tester's knowledge of past *failures*, or general knowledge of failure modes.

**experience-based test technique**
* A *test technique* based on the tester's experience, knowledge and intuition.
* synonyms: experience-based test design technique, experience-based technique

**exploratory testing**
* An approach to testing in which the testers dynamically design and execute tests based on their knowledge, exploration of the *test item* and the results of previous tests.
* also see: **test charter**
  + Documentation of the goal or objective for a test session.
  + synonyms: charter

**state transition testing**
* A *black-box test technique* in which *test cases* are designed to exercise elements of a state transition model.
* synonyms: finite state testing

**statement coverage**
* The *coverage* of executable statements.

**test technique**
* A procedure used to define *test conditions*, design *test cases*, and specify *test data*.
* synonyms: test design technique

**white-box test technique**
* A *test technique* only based on the internal structure of a component or system.
* synonyms: white-box test design technique, structure-based test technique

## 05 Managing the test activities

**defect management**
* The process of recognizing, recording, classifying, investigating, resolving and disposing of *defects*.

**defect report**
* Documentation of the occurrence, nature, and status of a *defect*.
* synonyms: bug report

**entry criteria**
* The set of conditions for officially starting a defined task.
* also see: **exit criteria**
  + The set of conditions for officially completing a defined task.
  + synonyms: test completion criteria, completion criteria

**exit criteria**
* The set of conditions for officially completing a defined task.
* synonyms: test completion criteria, completion criteria
* also see: **entry criteria**
  + The set of conditions for officially starting a defined task.

**product risk**
* A *risk* impacting the quality of a product.
* also see: **risk**
  + A factor that could result in future negative consequences.
  + also see: *product risk*, *project risk*

**project risk**
* A *risk* that impacts project success.
* also see: **risk**
  + A factor that could result in future negative consequences.
  + also see: *product risk*, *project risk*

**risk**
* A factor that could result in future negative consequences.
* also see: *product risk*, *project risk*

**risk analysis**
* The overall process of *risk identification* and *risk assessment*.

**risk assessment**
* The process to examine identified *risks* and determine the *risk level*.

**risk control**
* The overall process of *risk mitigation* and *risk monitoring*.

**risk identification**
* The process of finding, recognizing and describing *risks*.

**risk level**
* The measure of a **risk** defined by impact and likelihood.
* synonyms: risk exposure

**risk management**
* The process for handling *risks*.

**risk mitigation**
* The process through which decisions are reached and protective measures are implemented for reducing or maintaining *risks* to specified levels.

**risk monitoring**
* The activity that checks and reports the status of known *risks* to stakeholders.

**risk-based testing**
* Testing in which the management, selection, prioritization, and use of testing activities and resources are based on corresponding risk types and *risk levels*.

**test approach**
* The manner of implementing testing tasks.

**test completion report**
* A type of test report produced at completion milestones that provides an evaluation of the corresponding *test items* against *exit criteria*.
* synonyms: test summary report

**test control**
* The activity that develops and applies corrective actions to get a test project on track when it deviates from what was planned.
* also: **test management**

**test monitoring**
* The activity that checks the status of testing activities, identifies any variances from planned or expected, and reports status to stakeholders.
* also see: **test management**

**test plan**
* Documentation describing the *test objectives* to be achieved and the means and the schedule for achieving them, organized to coordinate testing activities.
* also see: master test plan, level test plan, test scope

**test planning**
* The activity of establishing or updating a *test plan*.

**test progress report**
* A type of periodic test report that includes the progress of test activities against a baseline, *risks*, and alternatives requiring a decision.
* synonyms: test status report

**test pyramid**
* A graphical model representing the relationship of the amount of testing per level, with more at the bottom than at the top.

**testing quadrants**
* A classification model of *test types* / *test levels* in four quadrants, relating them to two dimensions of *test objectives*: supporting the product team versus critiquing the product, and technology-facing versus business-facing.

## 06 Test tools

**test automation**
* The use of software to perform or support test activities.

## My additions

**the Pareto principle** (1.3)
* The Pareto principle states that for many outcomes, roughly 80% of consequences come from 20% of causes (the "vital few"). Other names for this principle are the 80/20 rule, the law of the vital few, or the principle of factor sparsity.
* In computer science the Pareto principle can be applied to optimization efforts. Eg. Microsoft noted that by fixing the top 20% of the most-reported bugs, 80% of the related errors and crashes in a given system would be eliminated. Lowell Arthur expressed that "20% of the code has 80% of the errors. Find them, fix them!" It was also discovered that, in general, 80% of a piece of software can be written in 20% of the total allocated time. Conversely, the hardest 20% of the code takes 80% of the time. This factor is usually a part of COCOMO estimating for software coding.
* see [Wikipedia](https://en.wikipedia.org/wiki/Pareto_principle)

**waterfall model** (2.1)
* A sequential model that divides software development into pre-defined phases. Each phase must be completed before the next phase can begin with no overlap between the phases. Each phase is designed for performing specific activity during the SDLC phase. It was introduced in 1970 by Winston Royce.

**V-model** (2.1)
* A sequential software development lifecycle model describing a one-for-one relationship between major phases of software development from business requirements specification to delivery, **and** corresponding test levels from acceptance testing to component testing.
* see [guru99](https://www.guru99.com/v-model-software-testing.html)

**spiral model** (2.1)
* a risk-driven software development process model. It is a combination of waterfall model and iterative model. Spiral Model helps to adopt software development elements of multiple process models for the software project based on unique risk patterns ensuring efficient development process.
* each phase of spiral model in software engineering begins with a design goal and ends with the client reviewing the progress.
* was first mentioned by Barry Boehm in his 1986 paper
* development process starts with a small set of requirement and goes through each development phase for those set of requirements. The software engineering team adds functionality for the additional requirement in every-increasing spirals until the application is ready for the production phase.
* see [guru99](https://www.guru99.com/what-is-spiral-model-when-to-use-advantages-disadvantages.html)

**prototyping** (2.1)
* a software development model in which prototype is built, tested, and reworked until an acceptable prototype is achieved. It also creates base to produce the final system or software. It works best in scenarios where the project’s requirements are not known in detail. It is an iterative, trial and error method which takes place between developer and client.
* see[guru99](https://www.guru99.com/software-engineering-prototyping-model.html)

**incremental development models** (2.1)
* Development is done in steps from analysis design, implementation, testing/verification, maintenance.
* Each iteration passes through the requirements, design, coding and testing phases. And each subsequent release of the system adds function to the previous release until all designed functionality has been implemented.
* see [guru99](https://www.guru99.com/what-is-incremental-model-in-sdlc-advantages-disadvantages.html)

**Unified Process** (2.1)
* a software development framework used for object-oriented modeling. The framework is also known as Rational Unified Process (RUP) and the Open Unified Process (Open UP)
* Some of the key features of this process include:
  + it defines the order of phases
  + it is component-based, meaning a software system is built as a set of software components. There must be well-defined interfaces between the components for smooth communication
  + it follows an iterative, incremental, architecture-centric, and use-case driven approach
* see [educative.io](https://www.educative.io/answers/what-is-a-unified-process-model)

**acceptance test-driven development** (ATDD)  (2.1)
* ATDD is closely related to test-driven development (TDD)
* differs by the emphasis on developer-tester-business customer collaboration
* ATDD encompasses acceptance testing, but highlights writing acceptance tests before developers begin coding
* Acceptance tests are from the user's point of view – the external view of the system
  + they examine externally visible effects, such as specifying the correct output of a system given a particular input
  + they can verify how the state of something changes, eg. an order that goes from "paid" to "shipped"
  + they also can check the interactions with interfaces of other systems, eg. shared databases or web services
  + in general, they are implementation independent, although automation of them may not be
* see [Wikipedia](https://en.wikipedia.org/wiki/Acceptance_test-driven_development)

**behavior-driven development** (BDD)  (2.1)
* encourages teams to use conversation & concrete examples to formalize a shared understanding of how the application should behave
* emerged from test-driven development (TDD)
* combines the general techniques & principles of TDD with ideas from domain-driven design and object-oriented analysis and design to provide software development and management teams with shared tools and a shared process to collaborate on software development
* although principally an idea about how software development should be managed by both business interests and technical insight, the practice of BDD does assume the use of specialized software tools to support the development process
  + although these tools are often developed specifically for use in BDD projects, they can be seen as specialized forms of the tooling that supports test-driven development
  + the tools serve to add automation to the ubiquitous language that is a central theme of BDD
* largely facilitated through the use of a simple domain-specific language (DSL) using natural-language constructs (eg. English-like sentences) that can express the behaviour & the expected outcomes
* test scripts have long been a popular application of DSLs with varying degrees of sophistication
* considered an effective technical practice especially when the "problem space" of the business problem to solve is complex
* see [Wikipedia](https://en.wikipedia.org/wiki/Behavior-driven_development)

**domain-driven design** (DDD)  (2.1)
* a major software design approach, focusing on modeling software to match a domain according to input from that domain's experts
* the structure and language of software code (class names, class methods, class variables) should match the business domain
  + eg. if software processes loan applications, it might have classes like "loan application", "customers", and methods such as "accept offer" and "withdraw"
* domain-driven design is predicated on the following goals:
  + placing the project's primary focus on the core domain and domain logic,
  + basing complex designs on a model of the domain,
  + initiating a creative collaboration between technical & domain experts to iteratively refine a conceptual model that addresses particular domain problems
* critics of domain-driven design argue that developers must typically implement a great deal of isolation and encapsulation to maintain the model as a pure and helpful construct
* while domain-driven design provides benefits such as maintainability, Microsoft recommends it only for complex domains where the model provides clear benefits in formulating a common understanding of the domain
* the term was coined by Eric Evans in his book of the same title published in 2003
* see [Wikipedia](https://en.wikipedia.org/wiki/Domain-driven_design)

**extreme programming** (XP)  (2.1)
* intends to improve software quality and responsiveness to changing customer requirements. As a type of agile software development, it advocates frequent releases in short development cycles, intended to improve productivity and introduce checkpoints at which new customer requirements can be adopted.
* other elements of extreme programming include:
  + programming in pairs or doing extensive code review,
  + unit testing of all code,
  + a flat management structure,
  + code simplicity and clarity,
  + expecting changes in the customer's requirements as time passes and the problem is better understood
  + frequent communication with the customer and among programmers.
* takes its name from the idea that the beneficial elements of traditional software engineering practices are taken to "extreme" levels. Eg. code reviews are considered a beneficial practice; taken to the extreme, code can be reviewed continuously (ie. the practice of pair programming).
* see [Wikipedia](https://en.wikipedia.org/wiki/Extreme_programming)

**feature-driven development** (FDD)  (2.1)
* an iterative & incremental software development process, a lightweight Agile method for developing software
* blends a number of industry-recognized best practices into a cohesive whole
* these practices are driven from a client-valued functionality (feature) perspective
* its main purpose is to deliver tangible, working software repeatedly in a timely manner in accordance with the Principles behind the Agile Manifesto

Kanban  (2.1)
* Kanban is a popular framework used to implement agile and DevOps software development
* requires real-time communication of capacity and full transparency of work
  + work items are represented visually on a kanban board
  + allowing team members to see the state of every piece of work at any time
* in the late 1940s Toyota began optimizing its engineering processes based on the same model that supermarkets were using to stock their shelves. Supermarkets stock just enough product to meet consumer demand, a practice that optimizes the flow between the supermarket and the consumer.
* when Toyota applied this same system to its factory floors, the goal was to better align their massive inventory levels with the actual consumption of materials. To communicate capacity levels in real-time on the factory floor (and to suppliers), workers would pass a card, or "kanban", between teams. When a bin of materials being used on the production line was emptied, a kanban was passed to the warehouse describing what material was needed, the exact amount of this material, and so on. The warehouse would have a new bin of this material waiting, which they would then send to the factory floor, and in turn send their own kanban to the supplier. The supplier would also have a bin of this particular material waiting, which it would ship to the warehouse. While the signaling technology of this process has evolved since the 1940s, this same "just in time" (or JIT) manufacturing process is still at the heart of it.
* see [Atlassian](https://www.atlassian.com/agile/kanban)
* see [Wikipedia](https://en.wikipedia.org/wiki/Kanban)

Lean IT  (2.1)
* see [Wikipedia](https://en.wikipedia.org/wiki/Lean_IT)

**Scrum**  (2.1)
* def.
  + an agile project management framework that helps teams structure & manage their work through a set of values, principles, and practices
  + encourages teams to learn through experiences, self-organize while working on a problem, and reflect on their wins and losses to continuously improve
  + describes a set of meetings, tools, and roles that work in concert to help teams structure and manage their work.
* it details the members of a scrum team and their accountabilities, “artifacts” that define the product and work to create the product, and scrum ceremonies that guide the scrum team through work
* a scrum team is a small and nimble team dedicated to delivering committed product increments
* three specific roles:
  + product owner
  + scrum master
  + the development team including testers, designers, UX specialists, & ops engineers
* product owner
  + the champions for their product:
    - focussed on understanding business, customer, and market requirements,
    - then prioritizing the work to be done by the engineering team accordingly
  + effective product owners:
    - build and manage the product backlog
    - closely partner with the business & the team to ensure everyone understands the work items in the product backlog
    - give the team clear guidance on which features to deliver next
    - decide when to ship the product with a predisposition towards more frequent delivery
* scrum master
  + the champions of scrum within their teams
    - they coach teams, product owners, & the business on the scrum process
    - look for ways to fine-tune their practice of it
  + an effective scrum master:
    - deeply understands the work being done by the team & can help the team optimize their transparency & delivery flow
    - as the facilitator-in-chief: schedules the needed resources ( human & logistical) for sprint planning, stand-up, sprint review, & the sprint retrospective
* scrum dev team
  + the champions for sustainable development practices: get things done
  + effective scrum teams are tight-knit, co-located, & usually five to seven members
    - the famous ‘two pizza rule’ coined by Jeff Bezos: team should be small enough to share two pizzas
  + members have differing skill sets, and cross-train each other so no one person becomes a bottleneck in the delivery of work
  + scrum teams are self-organizing & approach their projects with a clear ‘we’ attitude
  + all members of the team help one another to ensure a successful sprint completion
  + the scrum team drives the plan for each sprint
    - forecast how much work they can complete over the iteration using their historical velocity as a guide
* scrum artifacts
  + Product Backlog
    - the primary list of work that needs to get done & maintained by the product owner or product manager
    - this is a dynamic list of features, requirements, enhancements, & fixes that acts as the input for the sprint backlog
    - it is, essentially, the team’s “To Do” list
    - is constantly revisited, re-prioritized and maintained by the Product Owner because, as we learn more or as the market changes, items may no longer be relevant or problems may get solved in other ways
  + Sprint Backlog
    - the list of items, user stories, or bug fixes, selected by the development team for implementation in the current sprint cycle
    - before each sprint, in the sprint planning meeting the team chooses which items it will work on for the sprint from the product backlog
    - may be flexible & can evolve during a sprint
    - however, the fundamental sprint goal – what the team wants to achieve from the current sprint – cannot be compromised
  + Increment / Sprint Goal
    - the usable end-product from a sprint
    - often referred to as the team’s definition of “Done”, a milestone, the sprint goal, or even a full version or a shipped epic – depending on how your teams defines “Done” & how you define your sprint goals
    - eg. some teams choose to release something to their customers at the end of every sprint. So their definition of ‘done’ would be ‘shipped’. However, this may not be realistic of other types of teams
* scrum ceremonies / events
  + Organize the backlog: Sometimes known as backlog grooming, this event is the responsibility of the product owner. The product owner’s main jobs are to drive the product towards its product vision and have a constant pulse on the market and the customer. Therefore, he/she maintains this list using feedback from users and the development team to help prioritize and keep the list clean and ready to be worked on at any given time. You can read more about maintaining a healthy backlog here.

  + Sprint planning:
    - the work to be performed (scope) during the current sprint is planned during this meeting by the entire development team. This meeting is led by the scrum master and is where the team decides on the sprint goal. Specific user stories are then added to the sprint from the product backlog.  These stories always align with the goal and are also agreed upon by the scrum team to be feasible to implement during the sprint.
    - at the end of the planning meeting, every scrum member needs to be clear on what can be delivered in the sprint and how the increment can be delivered.

  + Sprint
    - A sprint is the actual time period when the scrum team works together to finish an increment. Two weeks is a pretty typical length for a sprint, though some teams find a week to be easier to scope or a month to be easier to deliver a valuable increment. Dave West, from Scrum.org advises that the more complex the work and the more unknowns, the shorter the sprint should be. But it’s really up to your team, and you shouldn’t be afraid to change it if it’s not working! During this period, the scope can be re-negotiated between the product owner and the development team if necessary. This forms the crux of the empirical nature of scrum.
    - All the events — from planning to retrospective — happen during the sprint. Once a certain time interval for a sprint is established, it has to remain consistent throughout the development period. This helps the team learn from past experiences and apply that insight to future sprints.

  + Daily scrum or stand up:
    - This is a daily super-short meeting that happens at the same time (usually mornings) and a place to keep it simple. Many teams try to complete the meeting in 15 minutes, but that’s just a guideline. This meeting is also called a ‘daily stand-up’ emphasizing that it needs to be a quick one. The goal of the daily scrum is for everyone on the team to be on the same page, aligned with the sprint goal, and to get a plan out for the next 24 hours.
    - The stand up is the time to voice any concerns you have with meeting the sprint goal or any blockers.
    - A common way to conduct a stand up is for every team member to answer three questions in the context of achieving the sprint goal:
    •      What did I do yesterday?
    •      What do I plan to do today?
    •      Are there any obstacles?
    - However, we’ve seen the meeting quickly turn into people reading from their calendars from yesterday and for the next day. The theory behind the stand up is that it keeps distracting chatter to a daily meeting, so the team can focus on the work for the rest of the day.  So if it turns into a daily calendar read-out, don’t be afraid to change it up and get creative.

  + Sprint review:
    - At the end of the sprint, the team gets together for an informal session to view a demo of, or inspect, the increment. The development team showcases the backlog items that are now ‘Done’ to stakeholders and teammates for feedback. The product owner can decide whether or not to release the increment, although in most cases the increment is released.
    - This review meeting is also when the product owner reworks the product backlog based on the current sprint, which can feed into the next sprint planning session. For a one-month sprint, consider time-boxing your sprint review to a maximum of four hours.
  + Sprint retrospective:
    - The retrospective is where the team comes together to document and discuss what worked and what didn’t work in a sprint, a project, people or relationships, tools, or even for certain ceremonies. The idea is to create a place where the team can focus on what went well and what needs to be improved for the next time, and less about what went wrong.
* see [Atlassian](https://www.atlassian.com/agile/scrum)

**test-driven development** (TDD)  (2.1)
* relies on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases – as opposed to software being developed first and test cases created later
* related to the test-first programming concepts of extreme programming, begun in 1999, but more recently has created more general interest in its own right
* see [Wikipedia](https://en.wikipedia.org/wiki/Test-driven_development)

integration strategy approaches (2.2.1)
* like bottom-up
* top-down
* big-bang

main forms of acceptance testing (2.2.1)
* user acceptance testing (UAT),
* operational acceptance testing,
* contractual and regulatory acceptance testing,
* alpha testing and beta testing

the Definition of Ready (3.1 & 5.1.3)

audit trail (3.2.4)

continuous partitions vs discrete partitions (4.2.1)

ordered partitions vs unordered (4.2.1)

finite partitions vs infinite (4.2.1)

smoke test (5.1.3)

scope creep (5.2.2)
