# ISTQB GLOSSARY V4

## SOURCE:
<https://glossary.istqb.org/en_US/search?term=&exact_matches_first=true>

## 01 Fundamentals of testing

**(test) coverage**
* The degree to which specified coverage items are exercised by a test suite, expressed as a percentage.

**debugging**
* The process of finding, analyzing and removing the causes of failures in a component or system.

**defect**
* An imperfection or deficiency in a work product where it does not meet its requirements or specifications.
* synonyms: **bug**, **fault**

**error**
* A human action that produces an incorrect result.
* synonyms: **mistake**

**failure**
* An event in which a component or system does not perform a required function within specified limits.

**quality**
* The degree to which a work product satisfies stated and implied needs of its stakeholders.

**quality assurance / QA**
* Activities focused on providing confidence that quality requirements will be fulfilled.
* also see: **quality management**
  + The process of establishing and directing a quality policy, quality objectives, quality planning, quality control, quality assurance, and quality improvement for an organization.

**root cause**
* A source of a **defect** such that if it is removed, the occurrence of the defect type is decreased or removed.

**test analysis**
* The activity that identifies **test conditions** by analyzing the **test basis**.

**test basis**
* The body of knowledge used as the basis for **test analysis** and **test design**.

**test case**
* A set of preconditions, inputs, actions (where applicable), expected results and postconditions, developed based on **test conditions**.

**test completion**
* The activity that makes testware available for later use, leaves test environments in a satisfactory condition and communicates the results of testing to relevant stakeholders.

**test condition**
* A testable aspect of a component or system identified as a basis for testing.
* synonyms: **test situation**, **test requirement**

**test control**
* The activity that develops and applies corrective actions to get a test project on track when it deviates from what was planned.
* also see: **test management**
  + The process of planning, scheduling, estimating, monitoring, reporting, controlling, and completing test activities.

**test data**
* Data needed for test execution.
* synonyms: **test dataset**

**test design**
* The activity that derives and specifies **test cases** from **test conditions**.

**test execution**
* The activity that runs a test on a component or system producing actual results.

**test implementation**
* The activity that prepares the testware needed for **test execution** based on **test analysis** and **design**.

**test monitoring**
* The activity that checks the status of testing activities, identifies any variances from planned or expected, and reports status to stakeholders.
* also see: **test management**
  + The process of planning, scheduling, estimating, monitoring, reporting, controlling, and completing test activities.

**test object**
* The work product to be tested.
* also see: **test item**
  + A part of a **test object** used in the test process.

**test objective**
* The purpose for testing.
* synonyms: **test goal**

**test planning**
* The activity of establishing or updating a **test plan**.
* **test plan**
  + Documentation describing the test **objectives** to be achieved and the means and the schedule for achieving them, organized to coordinate testing activities.

**test procedure**
* A sequence of test cases in execution order, and any associated actions that may be required to set up the initial preconditions and any wrap up activities post execution.

**test result**
* The consequence/outcome of the execution of a test.
* synonyms: **outcome**, **test outcome**, **result**

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
* A **test level** that focuses on determining whether to accept the system.
* also see: **user acceptance testing / UAT**
  + A type of acceptance testing performed to determine if intended users accept the system.

**black-box testing**
* Testing based on an analysis of the specification of the component or system.
* synonyms: **specification-based testing**

**component integration testing**
* The integration testing of components.
* synonyms: **module integration testing**, **unit integration testing**

**component testing**
* A **test level** that focuses on individual hardware or software components.
* synonyms: **module testing**, **unit testing**

**confirmation testing**
* A type of change-related testing performed after fixing a **defect** to confirm that a **failure** caused by that **defect** does not reoccur.
* synonyms: **re-testing**

**functional testing**
* Testing performed to evaluate if a component or system satisfies functional requirements.

**integration testing**
* A **test level** that focuses on interactions between components or systems.

**maintenance testing**
* Testing the changes to an operational system or the impact of a changed environment to an operational system.

**non-functional testing**
* Testing performed to evaluate that a component or system complies with non-functional requirements.

**regression testing**
* A type of change-related testing to detect whether **defects** have been introduced or uncovered in unchanged areas of the software.

**shift-left**
* An approach to performing testing and quality assurance activities as early as possible in the software development lifecycle.

**system integration testing**
* The integration testing of systems.

**system testing**
* A **test level** that focuses on verifying that a system as a whole meets specified requirements.

**test level**
* A specific instantiation of a test process.
* synonyms: **test stage**

**test object**
* The work product to be tested.
* also see: **test item**
  + A part of a test object used in the test process.

**test type**
* A group of test activities based on specific **test objectives** aimed at specific characteristics of a component or system.

**white-box testing**
* Testing based on an analysis of the internal structure of the component or system.
* synonyms: **clear-box testing**, **code-based testing**, **glass-box testing**, **logic-coverage testing**, **logic-driven testing**, **structural testing**, **structure-based testing**

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
* A type of formal review that uses defined team roles and measurement to identify **defects** in a work product, and improve the review process and the software development process.
* also see: **peer review**
  + A review performed by others with the same abilities to create the work product.

**review**
* A type of **static testing** in which a work product or process is evaluated by one or more individuals to detect **defects** or to provide improvements.

**static analysis**
* The process of evaluating a component or system without executing it, based on its form, structure, content, or documentation.

**static testing**
* Testing that does not involve the execution of a **test item**.
* also see: **dynamic testing**
  + Testing that involves the execution of the **test item**.

**technical review**
* A formal review by technical experts that examine the quality of a work product and identify discrepancies from specifications and standards.
* also see: **peer review**

**walkthrough**
* A type of review in which an author leads members of the review through a work product and the members ask questions and make comments about possible issues.
* synonyms: **structured walkthrough**

## 04 Test anaysis and design

**acceptance criteria**
* The criteria that a component or system must satisfy in order to be accepted by a user, customer, or other authorized entity.

**acceptance test-driven development**
* A collaboration-based test-first approach that defines acceptance tests in the stakeholders' domain language.
* also see: **specification by example**
  + A development technique in which the specification is defined by examples.

**black-box test technique**
* A **test technique** based on an analysis of the specification of a component or system.
* synonyms: **black-box test design technique**, **specification-based test technique**

**boundary value analysis**
* A **black-box test technique** in which test cases are designed based on boundary values.
* also see: **boundary value**
  + A minimum or maximum value of an ordered **equivalence partition**.
    - A subset of the value domain of a variable within a component or system in which all values are expected to be treated the same based on the specification.
    - synonyms: **equivalence class**

**branch coverage**
* The coverage of branches in a **control flow graph**.
  + ?
  + **control flow**: The sequence in which operations are performed by a business process, component or system.

**checklist-based testing**
* An experience-based **test technique** in which test cases are designed to exercise the items of a checklist.

**collaboration-based test approach**
* An approach to testing that focuses on defect avoidance by collaborating among stakeholders.

**coverage**
* The degree to which specified coverage items are exercised by a test suite, expressed as a percentage.
* synonyms: **test coverage**

**coverage item**
* An attribute or combination of attributes derived from one or more **test conditions** by using a **test technique**.
* also see: **coverage criteria**
  + The criteria to define the coverage items required to reach a **test objective**.

**decision table testing**
* A **black-box test technique** in which test cases are designed to exercise the combinations of conditions and the resulting actions shown in a decision table.

**equivalence partitioning**
* A **black-box test technique** in which **test conditions** are equivalence partitions exercised by one representative member of each partition.
* synonyms: **partition testing**

**error guessing**
* A **test technique** in which tests are derived on the basis of the tester's knowledge of past **failures**, or general knowledge of failure modes.

**experience-based test technique**
* A **test technique** based on the tester's experience, knowledge and intuition.
* synonyms: **experience-based test design technique**, **experience-based technique**

**exploratory testing**
* An approach to testing in which the testers dynamically design and execute tests based on their knowledge, exploration of the **test item** and the results of previous tests.
* also see: **test charter**
  + Documentation of the goal or objective for a test session.
  + synonyms: **charter**

**state transition testing**
* A **black-box test technique** in which **test cases** are designed to exercise elements of a state transition model.
* synonyms: **finite state testing**

**statement coverage**
* The **coverage** of executable statements.

**test technique**
* A procedure used to define **test conditions**, design **test cases**, and specify **test data**.
* synonyms: **test design technique**

**white-box test technique**
* A **test technique** only based on the internal structure of a component or system.
* synonyms: **white-box test design technique**, **structure-based test technique**

## 05 Managing the test activities

**defect management**
* The process of recognizing, recording, classifying, investigating, resolving and disposing of **defects**.

**defect report**
* Documentation of the occurrence, nature, and status of a **defect**.
* synonyms: **bug report**

**entry criteria**
* The set of conditions for officially starting a defined task.
* also see: **exit criteria**
  + The set of conditions for officially completing a defined task.
  + synonyms: **test completion criteria**, **completion criteria**

**exit criteria**
* The set of conditions for officially completing a defined task.
* synonyms: **test completion criteria**, **completion criteria**
* also see: **entry criteria**
  + The set of conditions for officially starting a defined task.

**product risk**
* A **risk** impacting the quality of a product.
* also see: **risk**
  + A factor that could result in future negative consequences.
  + also see: **product risk**, **project risk**

**project risk**
* A **risk** that impacts project success.
* also see: **risk**
  + A factor that could result in future negative consequences.
  + also see: **product risk**, **project risk**

**risk**
* A factor that could result in future negative consequences.
* also see: **product risk**, **project risk**

**risk analysis**
* The overall process of **risk identification** and **risk assessment**.

**risk assessment**
* The process to examine identified **risks** and determine the **risk level**.

**risk control**
* The overall process of **risk mitigation** and **risk monitoring**.

**risk identification**
* The process of finding, recognizing and describing **risks**.

**risk level**
* The measure of a **risk** defined by impact and likelihood.
* synonyms: **risk exposure**

**risk management**
* The process for handling **risks**.

**risk mitigation**
* The process through which decisions are reached and protective measures are implemented for reducing or maintaining **risks** to specified levels.

**risk monitoring**
* The activity that checks and reports the status of known **risks** to stakeholders.

**risk-based testing**
* Testing in which the management, selection, prioritization, and use of testing activities and resources are based on corresponding risk types and **risk levels**.

**test approach**
* The manner of implementing testing tasks.

**test completion report**
* A type of test report produced at completion milestones that provides an evaluation of the corresponding **test items** against **exit criteria**.
* synonyms: **test summary report**

**test control**
* The activity that develops and applies corrective actions to get a test project on track when it deviates from what was planned.
* also: **test management**

**test monitoring**
* The activity that checks the status of testing activities, identifies any variances from planned or expected, and reports status to stakeholders.
* also see: **test management**

**test plan**
* Documentation describing the **test objectives** to be achieved and the means and the schedule for achieving them, organized to coordinate testing activities.
* also see: **master test plan**, **level test plan**, **test scope**

**test planning**
* The activity of establishing or updating a **test plan**.

**test progress report**
* A type of periodic test report that includes the progress of test activities against a baseline, **risks**, and alternatives requiring a decision.
* synonyms: **test status report**

**test pyramid**
* A graphical model representing the relationship of the amount of testing per level, with more at the bottom than at the top.

**testing quadrants**
* A classification model of **test types** / **test levels** in four quadrants, relating them to two dimensions of **test objectives**: supporting the product team versus critiquing the product, and technology-facing versus business-facing.

## 06 Test tools

**test automation**
* The use of software to perform or support test activities.
