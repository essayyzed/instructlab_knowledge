# Systems development life cycle - Wikipedia

![](https://en.wikipedia.org/wiki/File:SDLC-Maintenance-Highlighted.png)

Model of the software development life cycle, highlighting the maintenance phase

In systems engineering, information systems and software engineering, the **systems development life cycle** (**SDLC**), also referred to as the **application development life cycle**, is a process for planning, creating, testing, and deploying an information system.[1] The SDLC concept applies to a range of hardware and software configurations, as a system can be composed of hardware only, software only, or a combination of both.[2] There are usually six stages in this cycle: requirement analysis, design, development and testing, implementation, documentation, and evaluation.

## Overview

A systems development life cycle is composed of distinct work phases that are used by systems engineers and systems developers to deliver information systems. Like anything that is manufactured on an assembly line, an SDLC aims to produce high-quality systems that meet or exceed expectations, based on requirements, by delivering systems within scheduled time frames and cost estimates.[3] Computer systems are complex and often link components with varying origins. Various SDLC methodologies have been created, such as waterfall, spiral, agile, rapid prototyping, incremental, and synchronize and stabilize.[4]

SDLC methodologies fit within a flexibility spectrum ranging from agile to iterative to sequential. Agile methodologies, such as XP and Scrum "Scrum (development)"), focus on lightweight processes that allow for rapid changes.[5] Iterative methodologies, such as Rational Unified Process and dynamic systems development method, focus on stabilizing project scope and iteratively expanding or improving products. Sequential or big-design-up-front (BDUF) models, such as waterfall, focus on complete and correct planning to guide larger projects and limit risks to successful and predictable results.[6] Anamorphic development is guided by project scope and adaptive iterations.

In project management a project can include both a project life cycle (PLC) and an SDLC, during which somewhat different activities occur. According to Taylor (2004), "the project life cycle encompasses all the activities of the project, while the systems development life cycle focuses on realizing the product requirements".[7]

SDLC is not a methodology per se, but rather a description of the phases that a methodology should address. The list of phases is not definitive, but typically includes planning, analysis, design, build, test, implement, and maintenance/support. In the Scrum framework,[8] for example, one could say a single user story goes through all the phases of the SDLC within a two-week sprint. By contrast the waterfall methodology, where every business requirement\_[citation needed*\] is translated into feature/functional descriptions which are then all implemented typically over a period of months or longer.\_[citation needed*\]

## History

According to Elliott (2004), SDLC "originated in the 1960s, to develop large scale functional business systems in an age of large scale business conglomerates. Information systems activities revolved around heavy data processing and number crunching routines".[9]

The structured systems analysis and design method (SSADM) was produced for the UK government Office of Government Commerce in the 1980s. Ever since, according to Elliott (2004), "the traditional life cycle approaches to systems development have been increasingly replaced with alternative approaches and frameworks, which attempted to overcome some of the inherent deficiencies of the traditional SDLC".[9]

## Models

![](https://en.wikipedia.org/wiki/File:Systems_Development_Life_Cycle.gif)

A ten-phase version of the systems development life cycle[10]

SDLC provides a set of phases/steps/activities for system designers and developers to follow. Each phase builds on the results of the previous one.[10][11][12][13] Not every project requires that the phases be sequential. For smaller, simpler projects, phases may be combined/overlap.[10]

### Waterfall

The oldest and best known is the waterfall model, which uses a linear sequence of steps.[11] Waterfall has different varieties. One variety is as follows:[10][11][14][15]

#### Preliminary analysis

Conduct with a preliminary analysis, consider alternative solutions, estimate costs and benefits, and submit a preliminary plan with recommendations.

- Conduct preliminary analysis: Identify the organization's objectives and define the nature and scope of the project. Ensure that the project fits with the objectives.
- Consider alternative solutions: Alternatives may come from interviewing employees, clients, suppliers, and consultants, as well as competitive analysis.
- Cost-benefit analysis: Analyze the costs and benefits of the project.

#### Systems analysis, requirements definition

Decompose project goals\_[clarification needed\_\] into defined functions and operations. This involves gathering and interpreting facts, diagnosing problems, and recommending changes. Analyze end-user information needs and resolve inconsistencies and incompleteness:[16]

- Collect facts: Obtain end-user requirements by document review, client interviews, observation, and questionnaires.
- Scrutinize existing system(s): Identify pros and cons.
- Analyze the proposed system: Find solutions to issues and prepare specifications, incorporating appropriate user proposals.

#### Systems design

At this step, desired features and operations are detailed, including screen layouts, business rules, process diagrams, pseudocode, and other deliverables.

#### Development

Write the code.

#### Integration and testing

Assemble the modules in a testing environment. Check for errors, bugs, and interoperability.

#### Acceptance, installation, deployment

Put the system into production. This may involve training users, deploying hardware, and loading information from the prior system.

#### Maintenance

Monitor the system to assess its ongoing fitness. Make modest changes and fixes as needed. To maintain the quality of the system. Continual monitoring and updates ensure the system remains effective and high-quality.[17]

#### Evaluation

The system and the process are reviewed. Relevant questions include whether the newly implemented system meets requirements and achieves project goals, whether the system is usable, reliable/available, properly scaled and fault-tolerant. Process checks include review of timelines and expenses, as well as user acceptance.

#### Disposal

At end of life, plans are developed for discontinuing the system and transitioning to its replacement. Related information and infrastructure must be repurposed, archived, discarded, or destroyed, while appropriately protecting security.[18]

In the following diagram, these stages are divided into ten steps, from definition to creation and modification of IT work products:

### Systems analysis and design

Systems analysis and design (SAD) can be considered a meta-development activity, which serves to set the stage and bound the problem. SAD can help balance competing high-level requirements. SAD interacts with distributed enterprise architecture, enterprise I.T. Architecture, and business architecture, and relies heavily on concepts such as partitioning, interfaces, personae and roles, and deployment/operational modeling to arrive at a high-level system description. This high-level description is then broken down into the components and modules which can be analyzed, designed, and constructed separately and integrated to accomplish the business goal. SDLC and SAD are cornerstones of full life cycle product and system planning.

### Object-oriented analysis and design

Object-oriented analysis and design (OOAD) is the process of analyzing a problem domain to develop a conceptual model that can then be used to guide development. During the analysis phase, a programmer develops written requirements and a formal vision document via interviews with stakeholders.

The conceptual model that results from OOAD typically consists of use cases, and class and interaction diagrams. It may also include a user interface mock-up.

An output artifact "Artifact (software development)") does not need to be completely defined to serve as input of object-oriented design; analysis and design may occur in parallel. In practice the results of one activity can feed the other in an iterative process.

Some typical input artifacts for OOAD:

- Conceptual model "Conceptual model (computer science)"): A conceptual model is the result of object-oriented analysis. It captures concepts in the problem domain. The conceptual model is explicitly independent of implementation details.
- Use cases: A use case is a description of sequences of events that, taken together, complete a required task. Each use case provides scenarios "Scenario (computing)") that convey how the system should interact with actors (users). Actors may be end users or other systems. Use cases may further elaborated using diagrams. Such diagrams identify the actor and the processes they perform.
- System Sequence Diagram: A System Sequence diagrams (SSD) is a picture that shows, for a particular use case, the events that actors generate, their order, including inter-system events.
- User interface document: Document that shows and describes the user interface.
- Data model: A data model describes how data elements relate to each other. The data model is created before the design phase. Object-oriented designs map directly from the data model. Relational designs are more involved.

### System lifecycle

The system lifecycle is a view of a system or proposed system that addresses all phases of its existence to include system conception, design and development, production and/or construction, distribution, operation, maintenance and support, retirement, phase-out, and disposal.[19]

#### Conceptual design

The conceptual design stage is the stage where an identified need is examined, requirements for potential solutions are defined, potential solutions are evaluated, and a system specification is developed. The system specification represents the technical requirements that will provide overall guidance for system design. Because this document determines all future development, the stage cannot be completed until a conceptual design review has determined that the system specification properly addresses the motivating need.

Key steps within the conceptual design stage include:

- Need identification
- Feasibility analysis
- System requirements analysis
- System specification
- Conceptual design review

#### Preliminary system design

During this stage of the system lifecycle, subsystems that perform the desired system functions are designed and specified in compliance with the system specification. Interfaces between subsystems are defined, as well as overall test and evaluation requirements.[20] At the completion of this stage, a development specification is produced that is sufficient to perform detailed design and development.

Key steps within the preliminary design stage include:

- Functional analysis
- Requirements allocation
- Detailed trade-off studies
- Synthesis of system options
- Preliminary design of engineering models
- Development specification
- Preliminary design review

For example, as the system analyst of Viti Bank, you have been tasked to examine the current information system. Viti Bank is a fast-growing bank in Fiji. Customers in remote rural areas are finding difficulty to access the bank services. It takes them days or even weeks to travel to a location to access the bank services. With the vision of meeting the customers' needs, the bank has requested your services to examine the current system and to come up with solutions or recommendations of how the current system can be provided to meet its needs.

#### Detail design and development

This stage includes the development of detailed designs that brings initial design work into a completed form of specifications. This work includes the specification of interfaces between the system and its intended environment, and a comprehensive evaluation of the systems logistical, maintenance and support requirements. The detail design and development is responsible for producing the product, process and material specifications and may result in substantial changes to the development specification.

Key steps within the detail design and development stage include:

- Detailed design
- Detailed synthesis
- Development of engineering and prototype models
- Revision of development specification
- Product, process, and material specification
- Critical design review

#### Production and construction

During the production and/or construction stage the product is built or assembled in accordance with the requirements specified in the product, process and material specifications, and is deployed and tested within the operational target environment. System assessments are conducted in order to correct deficiencies and adapt the system for continued improvement.

Key steps within the product construction stage include:

- Production and/or construction of system components
- Acceptance testing
- System distribution and operation
- Operational testing and evaluation
- System assessment

#### Utilization and support

Once fully deployed, the system is used for its intended operational role and maintained within its operational environment.

Key steps within the utilization and support stage include:

- System operation in the user environment
- Change management
- System modifications for improvement
- System assessment

#### Phase-out and disposal

Effectiveness and efficiency of the system must be continuously evaluated to determine when the product has met its maximum effective lifecycle.[21] Considerations include: Continued existence of operational need, matching between operational requirements and system performance, feasibility of system phase-out versus maintenance, and availability of alternative systems.

## Phases

### System investigation

During this step, current priorities that would be affected and how they should be handled are considered. A feasibility study determines whether creating a new or improved system is appropriate. This helps to estimate costs, benefits, resource requirements, and specific user needs.

The feasibility study should address operational, financial, technical, human factors, and legal/political concerns.

### Analysis

The goal of analysis is to determine where the problem is. This step involves decomposing the system into pieces, analyzing project goals, breaking down what needs to be created, and engaging users to define requirements.

### Design

In systems design, functions and operations are described in detail, including screen layouts, business rules, process diagrams, and other documentation. Modular design reduces complexity and allows the outputs to describe the system as a collection of subsystems.

The design stage takes as its input the requirements already defined. For each requirement, a set of design elements is produced.

Design documents typically include functional hierarchy diagrams, screen layouts, business rules, process diagrams, pseudo-code, and a complete data model with a data dictionary. These elements describe the system in sufficient detail that developers and engineers can develop and deliver the system with minimal additional input.

### Testing

The code is tested at various levels in software testing. Unit, system, and user acceptance tests are typically performed. Many approaches to testing have been adopted.

The following types of testing may be relevant:

- Path testing
- Data set testing
- Unit testing
- System testing
- Integration testing
- Black-box testing
- White-box testing
- Regression testing
- Automation testing
- User acceptance testing
- Software performance testing

### Training and transition

Once a system has been stabilized through testing, SDLC ensures that proper training is prepared and performed before transitioning the system to support staff and end users. Training usually covers operational training for support staff as well as end-user training.

After training, systems engineers and developers transition the system to its production environment.

### Operations and maintenance

Maintenance includes changes, fixes, and enhancements.

### Evaluation

The final phase of the SDLC is to measure the effectiveness of the system and evaluate potential enhancements.

## Life cycle

### Management and control

![](https://en.wikipedia.org/wiki/File:SDLC_Phases_Related_to_Management_Controls.jpg)

SDLC phases related to management controls[22]

SDLC phase objectives are described in this section with key deliverables, a description of recommended tasks, and a summary of related control objectives for effective management. It is critical for the project manager to establish and monitor control objectives while executing projects. Control objectives are clear statements of the desired result or purpose and should be defined and monitored throughout a project. Control objectives can be grouped into major categories (domains), and relate to the SDLC phases as shown in the figure.[22]

To manage and control a substantial SDLC initiative, a work breakdown structure (WBS) captures and schedules the work. The WBS and all programmatic material should be kept in the "project description" section of the project notebook.\_[clarification needed\_\] The project manager chooses a WBS format that best describes the project.

The diagram shows that coverage spans numerous phases of the SDLC but the associated MCD\_[clarification needed\_\] shows mappings to SDLC phases. For example, Analysis and Design is primarily performed as part of the Acquisition and Implementation Domain, and System Build and Prototype is primarily performed as part of delivery and support.[22]

### Work breakdown structured organization

![](https://en.wikipedia.org/wiki/File:SDLC_Work_Breakdown_Structure.jpg)

Work breakdown structure[22]

The upper section of the WBS provides an overview of the project scope and timeline. It should also summarize the major phases and milestones. The middle section is based on the SDLC phases. WBS elements consist of milestones and tasks to be completed rather than activities to be undertaken and have a deadline. Each task has a measurable output (e.g., analysis document). A WBS task may rely on one or more activities (e.g. coding). Parts of the project needing support from contractors should have a statement of work (SOW). The development of a SOW does not occur during a specific phase of SDLC but is developed to include the work from the SDLC process that may be conducted by contractors.[22]

### Baselines

Baselines\_[clarification needed\_\] are established after four of the five phases of the SDLC, and are critical to the iterative nature of the model.[23] Baselines become milestones.

- functional baseline: established after the conceptual design phase.
- allocated baseline: established after the preliminary design phase.
- product baseline: established after the detail design and development phase.
- updated product baseline: established after the production construction phase.

## Alternative methodologies

Alternative software development methods to systems development life cycle are:

- Software prototyping
- Joint applications development (JAD)
- Rapid application development (RAD)
- Extreme programming (XP);
- Open-source development
- End-user development
- Object-oriented programming

Comparison of Methodology Approaches (Post, & Anderson 2006)[24]

|                            | SDLC        | RAD     | Open source | Objects    | JAD     | Prototyping | End User |
| -------------------------- | ----------- | ------- | ----------- | ---------- | ------- | ----------- | -------- |
| Control                    | Formal      | MIS     | Weak        | Standards  | Joint   | User        | User     |
| Time frame                 | Long        | Short   | Medium      | Any        | Medium  | Short       | Short–   |
| Users                      | Many        | Few     | Few         | Varies     | Few     | One or two  | One      |
| MIS staff                  | Many        | Few     | Hundreds    | Split      | Few     | One or two  | None     |
| Transaction/DSS            | Transaction | Both    | Both        | Both       | DSS     | DSS         | DSS      |
| Interface                  | Minimal     | Minimal | Weak        | Windows    | Crucial | Crucial     | Crucial  |
| Documentation and training | Vital       | Limited | Internal    | In Objects | Limited | Weak        | None     |
| Integrity and security     | Vital       | Vital   | Unknown     | In Objects | Limited | Weak        | Weak     |
| Reusability                | Limited     | Some    | Maybe       | Vital      | Limited | Weak        | None     |

## Strengths and weaknesses

Fundamentally, SDLC trades flexibility for control by imposing structure. It is more commonly used for large scale projects with many developers.

Strength and Weaknesses of SDLC[24]

| Strengths                             | Weaknesses                                                |
| ------------------------------------- | --------------------------------------------------------- |
| Control                               | Increased development time                                |
| Monitor large projects                | Increased development cost                                |
| Detailed steps                        | Systems must be defined up front                          |
| Evaluate costs and completion targets | Rigidity                                                  |
| Documentation                         | Hard to estimate costs, project overruns                  |
| Well defined user input               | User input is sometimes limited                           |
| Ease of maintenance                   | Little parallelism                                        |
| Development and design standards      | Automation of documentation and standards is limited      |
| Tolerates changes in MIS of staffing  | Does not tolerate changes in requirements                 |
|                                       | Projects canned early on the result in little or no value |

## See also

- Application lifecycle management
- Decision cycle
- IPO model
- Software development methodologies

## References

1.  SELECTING A DEVELOPMENT APPROACH. Retrieved 17 July 2014.
2.  Parag C. Pendharkara; James A. Rodgerb; Girish H. Subramanian (November 2008). "An empirical study of the Cobb–Douglas production function properties of software development effort". _Information and Software Technology_. **50** (12): 1181–1188. doi "Doi (identifier)"):10.1016/j.infsof.2007.10.019.
3.  "Systems Development Life Cycle from". FOLDOC. Retrieved 2013-06-14.
4.  "Software Development Life Cycle (SDLC)".
5.  "SDLC Overview: Models & Methodologies". Retrieved 2021-12-12.
6.  Arden, Trevor (1991). _Information technology applications_. London: Pitman. ISBN "ISBN (identifier)") 978-0-273-03470-4.
7.  Taylor, James (2004). _Managing Information Technology Projects_. p. 39.
8.  "What is Scrum?". December 24, 2019.
9.  ^ Geoffrey Elliott (2004) _Global Business Information Technology_. p.87.
10. ^ US Department of Justice (2003). INFORMATION RESOURCES MANAGEMENT Chapter 1. Introduction.
11. ^ Everatt, G.D.; McLeod, R Jr (2007). "Chapter 2: The Software Development Life Cycle". _Software Testing: Testing Across the Entire Software Development Life Cycle_. John Wiley & Sons. pp. 29–58. ISBN "ISBN (identifier)") 9780470146347.
12. Unhelkar, B. (2016). _The Art of Agile Practice: A Composite Approach for Projects and Organizations_. CRC Press. pp. 56–59. ISBN "ISBN (identifier)") 9781439851197.
13. Land, S.K.; Smith, D.B.; Walz, J.W. (2012). _Practical Support for Lean Six Sigma Software Process Definition: Using IEEE Software Engineering Standards_. John Wiley & Sons. pp. 341–3. ISBN "ISBN (identifier)") 9780470289952.
14. Kay, Russell (May 14, 2002). "QuickStudy: System Development Life Cycle". _ComputerWorld_.
15. Taylor, G.D. (2008). _Introduction to Logistics Engineering_. CRC Press. pp. 12.6–12.18. ISBN "ISBN (identifier)") 9781420088571.
16. "Chapter 5". _Information Systems Control and Audit_ (PDF). Institute of Chartered Accountants of India. August 2013. p. 5.28.
17. Shah, Kazim. "The Maintenance Phase Of Software Development Life Cycle". _primetechnologiesglobal_. kazim shah. Retrieved 12 May 2024.
18. Radack, S. (n.d.). "The system development life cycle (SDLC)" (PDF). National Institute of Standards and Technology.
19. Blanchard and Fabrycky (2006). _Systems Engineering and Analysis, Fourth Edition_. Prentice Hall. p. 19.
20. Dr. Joahn Gouws (2007). _Introduction to Engineering, System Engineering_. Melikon Pty Ltd.
21. Cunningham, James. "HERC Maintenance". _Fargo_. **XXI** (North Avenue): 49. Archived from the original on 21 January 2013. Retrieved 13 May 2009.
22. ^ U.S. House of Representatives (1999). _Systems Development Life-Cycle Policy_. p.13. Archived 2013-10-19 at the Wayback Machine
23. Blanchard, B. S."), & Fabrycky, W. J.(2006) _Systems engineering and analysis_ (4th ed.) New Jersey: Prentice Hall. p.31
24. ^ Post, G., & Anderson, D., (2006). _Management information systems: Solving business problems with information technology_. (4th ed.). New York: McGraw-Hill Irwin.

## Further reading

- Cummings, Haag (2006). _Management Information Systems for the Information Age_. Toronto, McGraw-Hill Ryerson
- Beynon-Davies P. (2009). _Business Information Systems_. Palgrave, Basingstoke. ISBN "ISBN (identifier)") 978-0-230-20368-6
- Computer World, 2002, Retrieved on June 22, 2006, from the World Wide Web:
- Management Information Systems, 2005, Retrieved on June 22, 2006, from the World Wide Web:

## External links

- The Agile System Development Lifecycle
- Pension Benefit Guaranty Corporation – Information Technology Solutions Lifecycle Methodology
- DoD Integrated Framework Chart IFC (front, back)
- FSA Life Cycle Framework
- HHS Enterprise Performance Life Cycle Framework
- The Open Systems Development Life Cycle
- System Development Life Cycle Evolution Modeling
- Zero Deviation Life Cycle
- Integrated Defense AT&L Life Cycle Management Chart, the U.S. DoD form of this concept.
