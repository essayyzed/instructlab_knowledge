# Coding best practices

**Coding best practices** or **programming best practices** are a set of informal, sometimes personal, rules (_best practices_) that many software developers, in computer programming follow to improve software quality.[1] Many computer programs require being robust and reliable for long periods of time,[2] so any rules need to facilitate both initial development and subsequent maintenance of source code by people other than the original authors.

In the ninety–ninety rule, Tom Cargill explains why programming projects often run late: "The first 90% of the code takes the first 90% of the development time. The last 10% takes another 90% of the time."[3] Any guidance which can redress this lack of foresight is worth considering.

The size of a project or program has a significant effect on error rates, programmer productivity, and the amount of management needed.[4]

## Software quality

As listed below, there are many attributes associated with good software. Some of these can be mutually contradictory (e.g. being very fast versus performing extensive error checking), and different customers and participants may have different priorities. Weinberg provides an example of how different goals can have a dramatic effect on both effort required and efficiency.[5] Furthermore, he notes that programmers will generally aim to achieve any explicit goals which may be set, probably at the expense of any other quality attributes.

Sommerville has identified four generalized attributes which are not concerned with what a program does, but how well the program does it: Maintainability, dependability, efficiency and usability.[6]

Weinberg has identified four targets which a good program should meet:[7]

- Does a program meet its specification ("correct output for each possible input")?
- Is the program produced on schedule (and within budget)?
- How adaptable is the program to cope with changing requirements?
- Is the program efficient enough for the environment in which it is used?

Hoare has identified seventeen objectives related to software quality, including:[8]

- Clear definition of purpose.
- Simplicity of use.
- Ruggedness (difficult to misuse, kind to errors).
- Early availability (delivered on time when needed).
- Reliability.
- Extensibility in the light of experience.
- Brevity.
- Efficiency (fast enough for the purpose to which it is put).
- Minimum cost to develop.
- Conformity to any relevant standards (including programming language-specific standards).
- Clear, accurate and precise user documents.

## Prerequisites

Before coding starts, it is important to ensure that all necessary prerequisites have been completed (or have at least progressed far enough to provide a solid foundation for coding). If the various prerequisites are not satisfied, then the software is likely to be unsatisfactory, even if it is completed.

From Meek & Heath: "What happens before one gets to the coding stage is often of crucial importance to the success of the project."[9]

The prerequisites outlined below cover such matters as:

- How is the development structured? (life cycle)
- What is the software meant to do? (requirements)
- What is the overall structure of the software system? (architecture)
- What is the detailed design of individual components? (design)
- What is the choice of programming language(s)?

For small simple projects it may be feasible to combine architecture with design and adopt a very simple life cycle.

### Life cycle

A software development methodology is a framework that is used to structure, plan, and control the life cycle of a software product. Common methodologies include waterfall, prototyping, iterative and incremental development, spiral development, agile software development, rapid application development, and extreme programming.

The waterfall model is a sequential development approach; in particular, it assumes that the requirements can be completely defined at the start of a project. However, McConnell quotes three studies that indicate that, on average, requirements change by around 25% during a project.[10] The other methodologies mentioned above all attempt to reduce the impact of such requirement changes, often by some form of step-wise, incremental, or iterative approach. Different methodologies may be appropriate for different development environments.

Since its introduction in 2001, agile software development has grown in popularity, fueled by software developers seeking a more iterative, collaborative approach to software development.[11]

### Requirements

McConnell states: "The first prerequisite you need to fulfill before beginning construction is a clear statement of the problem the system is supposed to solve."[12]

Meek and Heath emphasise that a clear, complete, precise, and unambiguous written specification is the target to aim for.[13] Note that it may not be possible to achieve this target, and the target is likely to change anyway (as mentioned in the previous section).

Sommerville distinguishes between less detailed user requirements and more detailed system requirements.[14] He also distinguishes between functional requirements (e.g. update a record) and non-functional requirements (e.g. response time must be less than 1 second).

### Architecture

Hoare points out: "there are two ways of constructing a software design: one way is to make it so simple that there are _obviously_ no deficiencies; the other way is to make it so complicated that there are no _obvious_ deficiencies. The first method is far more difficult."[15]

Software architecture is concerned with deciding what has to be done and which program component is going to do it (how something is done is left to the detailed design phase below). This is particularly important when a software system contains more than one program since it effectively defines the interface between these various programs. It should include some consideration of any user interfaces as well, without going into excessive detail.

Any non-functional system requirements (response time, reliability, maintainability, etc.) need to be considered at this stage.[16]

The software architecture is also of interest to various stakeholders (sponsors, end-users, etc.) since it gives them a chance to check that their requirements can be met.

### Design

The primary purpose of design is to fill in the details which have been glossed over in the architectural design. The intention is that the design should be detailed enough to provide a good guide for actual coding, including details of any particular algorithms to be used. For example, at the architectural level, it may have been noted that some data has to be sorted, while at the design level, it is necessary to decide which sorting algorithm is to be used. As a further example, if an object-oriented approach is being used, then the details of the objects must be determined (attributes and methods).

### Choice of programming language(s)

Mayer states: "No programming language is perfect. There is not even a single best language; there are only languages well suited or perhaps poorly suited for particular purposes. Understanding the problem and associated programming requirements is necessary for choosing the language best suited for the solution."[17]

From Meek & Heath: "The essence of the art of choosing a language is to start with the problem, decide what its requirements are, and their relative importance since it will probably be impossible to satisfy them all equally well. The available languages should then be measured against the list of requirements, and the most suitable (or least unsatisfactory) chosen."[18]

It is possible that different programming languages may be appropriate for different aspects of the problem. If the languages or their compilers permit, it may be feasible to mix routines written in different languages within the same program.

Even if there is no choice as to which programming language is to be used, McConnell provides some advice: "Every programming language has strengths and weaknesses. Be aware of the specific strengths and weaknesses of the language you're using."[19]

## Coding standards

This section is also really a prerequisite to coding, as McConnell points out: "Establish programming conventions before you begin programming. It's nearly impossible to change code to match them later."[19]

As listed near the end of coding conventions, there are different conventions for different programming languages, so it may be counterproductive to apply the same conventions across different languages. It is important to note that there is no one particular coding convention for any programming language. Every organization has a custom coding standard for each type of software project. It is, therefore, imperative that the programmer chooses or makes up a particular set of coding guidelines before the software project commences. Some coding conventions are generic, which may not apply for every software project written with a particular programming language.

The use of coding conventions is particularly important when a project involves more than one programmer (there have been projects with thousands of programmers). It is much easier for a programmer to read code written by someone else if all code follows the same conventions.

For some examples of bad coding conventions, Roedy Green provides a lengthy (tongue-in-cheek) article on how to produce unmaintainable code.[20]

###

Due to time restrictions or enthusiastic programmers who want immediate results for their code, commenting of code often takes a back seat. Programmers working as a team have found it better to leave comments behind since coding usually follows cycles, or more than one person may work on a particular module. However, some commenting can decrease the cost of knowledge transfer between developers working on the same module.

In the early days of computing, one commenting practice was to leave a brief description of the following:

1.  Name of the module
2.  Purpose of the Module
3.  Description of the Module
4.  Original Author
5.  Modifications
6.  Authors who modified code with a description on why it was modified.

The "description of the module" should be as brief as possible but without sacrificing clarity and comprehensiveness.

However, the last two items have largely been obsoleted by the advent of revision control systems. Modifications and their authorship can be reliably tracked by using such tools rather than by using comments.

Also, if complicated logic is being used, it is a good practice to leave a comment "block" near that part so that another programmer can understand what exactly is happening.

Unit testing can be another way to show how code is intended to be used.

### Naming conventions

Use of proper naming conventions is considered good practice. Sometimes programmers tend to use X1, Y1, etc. as variables and forget to replace them with meaningful ones, causing confusion.

It is usually considered good practice to use descriptive names.

Example: A variable for taking in weight as a parameter for a truck can be named TrkWeight, TruckWeightKilograms or Truck_Weight_Kilograms, with TruckWeightKilograms (See Pascal case naming of variables) often being the preferable one since it is instantly recognizable, but naming convention is not always consistent between projects and/or companies.

### Keep the code simple

The code that a programmer writes should be simple. Complicated logic for achieving a simple thing should be kept to a minimum since the code might be modified by another programmer in the future. The logic one programmer implemented may not make perfect sense to another. So, always keep the code as simple as possible.[21]

### Portability

Program code should not contain "hard-coded" (literal) values referring to environmental parameters, such as absolute file paths, file names, user names, host names, IP addresses, and URLs, UDP/TCP ports. Otherwise, the application will not run on a host that has a different design than anticipated. A careful programmer can parametrize such variables and configure them for the hosting environment outside of the application proper (for example, in property files, on an application server, or even in a database). Compare the mantra of a "single point of definition".[22](SPOD).

As an extension, resources such as XML files should also contain variables rather than literal values, otherwise, the application will not be portable to another environment without editing the XML files. For example, with J2EE applications running in an application server, such environmental parameters can be defined in the scope of the JVM, and the application should get the values from there.

### Scalability

Design code with scalability as a design goal because very often in software projects, new features are always added to a project which becomes bigger. Therefore, the facility to add new features to a software code base becomes an invaluable method in writing software.

### Reusability

Re-use is a very important design goal in software development. Re-use cuts development costs and also reduces the time for development if the components or modules which are reused are already tested. Very often, software projects start with an existing baseline that contains the project in its prior version and depending on the project, many of existing software modules and components are reused, which reduces development and testing time, therefore, increasing the probability of delivering a software project on schedule.

### Construction guidelines in brief

A general overview of all of the above:

1.  Know what the code block must perform
2.  Maintain naming conventions which are uniform throughout.
3.  Indicate a brief description of what a variable is for (reference to commenting)
4.  Correct errors as they occur.
5.  Keep your code simple
6.  Design code with scalability and reuse in mind.

## Code development

### Code building

A best practice for building code involves daily builds and testing, or better still continuous integration, or even continuous delivery.

### Testing

Testing is an integral part of software development that needs to be planned. It is also important that testing is done proactively; meaning that test cases are planned before coding starts, and test cases are developed while the application is being designed and coded.

### Debugging the code and correcting errors

Programmers tend to write the complete code and then begin debugging and checking for errors. Though this approach can save time in smaller projects, bigger and more complex ones tend to have too many variables and functions that need attention. Therefore, it is good to debug every module once you are done and not the entire program. This saves time in the long run so that one does not end up wasting a lot of time on figuring out what is wrong. unit tests for individual modules and/or functional tests for web services and web applications can help with this.

### Deployment

Deployment is the final stage of releasing an application for users. Some best practices are:[23][24]

1.  Keep the installation structure simple: Files and directories should be kept to a minimum. Don’t install anything that’s never going to be used.
2.  Keep only what is needed: The software configuration management activities must make sure this is enforced. Unused resources (old or failed versions of files, source code, interfaces, etc.) must be archived somewhere else to keep newer builds lean.
3.  Keep everything updated: The software configuration management activities must make sure this is enforced. For delta-based deployments, make sure the versions of the resources that are already deployed are the latest before deploying the deltas. If not sure, perform a deployment from scratch (delete everything first and then re-deploy).
4.  Adopt a multi-stage strategy: Depending on the size of the project, sometimes more deployments are needed.[25]
5.  Have a roll back strategy: There must be a way to roll-back to a previous (working) version.
6.  Rely on automation for repeatable processes: There's far too much room for human error, deployments should not be manual. Use a tool that is native to each operating system or, use a scripting language for cross-platform deployments.[26][27]
7.  Re-create the real deployment environment: Consider everything (routers, firewalls, web servers, web browsers, file systems, etc.)
8.  Do not change deployment procedures and scripts on-the-fly and, document such changes: Wait for a new iteration and record such changes appropriately.
9.  Customize deployment: Newer software products such as APIs, micro-services, etc. require specific considerations for successful deployment.[28][29][30]
10. Reduce risk from other development phases: If other activities such as testing and configuration management are wrong, deployment surely will fail.[31][32]
11. Consider the influence each stakeholder has: Organizational, social, governmental considerations.[33][34][35]

## See also

- Best practice
- List of tools for static code analysis
- Motor Industry Software Reliability Association (MISRA)
- Software Assurance
- Software quality
- List of software development philosophies
- The Cathedral and the Bazaar - book comparing top-down vs. bottom-up open-source software
- Davis 201 Principles of Software Development[36]
- Where's the Theory for Software Engineering?[37]
- _Don't Make Me Think_ (Principles of intuitive navigation and information design)[38]

## Notes

## References

1.  McConnell, Steve (2004). _Code Complete_. Redmond, Wash.: Microsoft Press. p. \_[page needed\_\]. ISBN "ISBN (identifier)") 978-0-7356-9125-4. OCLC "OCLC (identifier)") 61315783.
2.  Sommerville, Ian (2004). _Software Engineering_ (Seventh ed.). Pearson. p. 38. ISBN "ISBN (identifier)") 0-321-21026-3.
3.  Bentley, Jon (1985). "Programming pearls: Bumper-Sticker Computer Science". _Communications of the ACM_. **28** (9): 896–901. doi "Doi (identifier)"):10.1145/4284.315122. ISSN "ISSN (identifier)") 0001-0782. S2CID "S2CID (identifier)") 5832776.
4.  McConnell, Steve (2004). _Code Complete_ (Second ed.). Microsoft Press. pp. 649–659. ISBN "ISBN (identifier)") 0-7356-1967-0.
5.  Weinberg, Gerald (1998). _The Psychology of Computer Programming_ (Silver anniversary ed.). Dorset House Publishing, New York. pp. 128–132. ISBN "ISBN (identifier)") 978-0-932633-42-2.
6.  Sommerville, Ian (2004). _Software Engineering_ (Seventh ed.). Pearson. pp. 12–13. ISBN "ISBN (identifier)") 0-321-21026-3.
7.  Weinberg, Gerald (1998). _The Psychology of Computer Programming_ (Silver anniversary ed.). Dorset House Publishing, New York. pp. 15–25. ISBN "ISBN (identifier)") 978-0-932633-42-2.
8.  Hoare, C.A.R. (1972). "The Quality of Software". _Software: Practice and Experience_. **2** (2). Wiley: 103–105. doi "Doi (identifier)"):10.1002/spe.4380020202.
9.  Meek, Brian; Heath, Patricia (1980), _Guide to Good Programming Practice_, Ellis Horwood, Wiley, p. 14
10. McConnell, Steve (2004). _Code Complete_ (Second ed.). Microsoft Press. p. 40. ISBN "ISBN (identifier)") 0-7356-1967-0.
11. Sacolick, Isaac (April 8, 2022). "A brief history of the agile methodology". _Infoworld_. Retrieved February 6, 2023.
12. McConnell, Steve (2004). _Code Complete_ (Second ed.). Microsoft Press. p. 36. ISBN "ISBN (identifier)") 0-7356-1967-0.
13. Meek, Brian; Heath, Patricia (1980), _Guide to Good Programming Practice_, Ellis Horwood, Wiley, p. 15
14. Sommerville, Ian (2004). _Software Engineering_ (Seventh ed.). Pearson. pp. 118–123. ISBN "ISBN (identifier)") 0-321-21026-3.
15. Hoare, C.A.R (1981). "The Emperor's Old Clothes" (PDF). _Communications of the ACM_. **24** (2). ACM: 75–83. doi "Doi (identifier)"):10.1145/358549.358561. S2CID "S2CID (identifier)") 97895. Retrieved 25 Nov 2019.
16. Sommerville, Ian (2004). _Software Engineering_ (Seventh ed.). Pearson. pp. 242–243. ISBN "ISBN (identifier)") 0-321-21026-3.
17. Mayer, Herbert (1989). _Advanced C programming on the IBM PC_. Windcrest Books. p. xii (preface). ISBN "ISBN (identifier)") 0830693637.
18. Meek, Brian; Heath, Patricia (1980), _Guide to Good Programming Practice_, Ellis Horwood, Wiley, p. 37
19. ^ McConnell, Steve (2004). _Code Complete_ (Second ed.). Microsoft Press. p. 70. ISBN "ISBN (identifier)") 0-7356-1967-0.
20. Roedy Green. "unmaintainable code : Java Glossary". Retrieved 2013-11-26.
21. Multiple (wiki). "Best practices". _Docforge_. Retrieved 2012-11-13.
22. "Single-Point-of-Definition by Example". Retrieved 2015-11-30. 'Don't repeat anything. Aim for a Single Point of Definition for every aspect of your application \[...\]'.
23. "7 Application Deployment Best Practices - Done Devops". _dzone.com_.
24. ["The seven deadly sins of software deployment \[LWN.net\]"](https://lwn.net/Articles/562333/). _lwn.net_.
25. blog.fortrabbit.com/multi-stage-deployment-for-website-development
26. Cruz, Victor (April 3, 2013). "Why 30% of App Deployments fail". _Wired_ – via www.wired.com.
27. "The rules of software deployment". Archived from the original on 2010-05-13.
28. "Tools You Need to Speed Up Deployment to Match Demand". February 3, 2017.
29. Ankerholz, Amber (September 14, 2016). "DevOps and the Art of Secure Application Deployment".
30. "Organizing Software Deployments to Match Failure Conditions". _Amazon Web Services_. May 5, 2014.
31. "Best Practices for Risk-Free Deployment". _TheServerSide.com_.
32. Ambler, Scott. "Effective Software Deployment". _Dr. Dobb's_.
33. "Enterprise application deployment: The humanity of software implementation". Archived from the original on 2016-08-21.
34. "Hacking bureaucracy: improving hiring and software deployment | 18F: Digital service delivery". _18f.gsa.gov_. 14 May 2014.
35. "A Bad Software Deployment Is Worse Than Doing Nothing". _Intact Technology_. June 1, 2016.
36. Davis, Alan Mark. (1995). _201 principles of software development_. New York: McGraw-Hill. ISBN "ISBN (identifier)") 0-07-015840-1. OCLC "OCLC (identifier)") 31814837.
37. Johnson, Pontus; Ekstedt, Mathias; Jacobson, Ivar (2012). "Where's the Theory for Software Engineering?". _IEEE Software_. **29** (5): 96. doi "Doi (identifier)"):10.1109/MS.2012.127. ISSN "ISSN (identifier)") 0740-7459. S2CID "S2CID (identifier)") 38239662.
38. Krug, Steve (2014). _Don't make me think, revisited : a common sense approach to Web usability_. Bayle, Elisabeth,, Straiger, Aren,, Matcho, Mark (Third ed.). \[San Francisco, California\]. ISBN "ISBN (identifier)") 978-0-321-96551-6. OCLC "OCLC (identifier)") 859556499.`{{cite book}}`: CS1 maint: location missing publisher (link)

- Harbison, Samuel P.; Steele, Guy L. (2002). _C - A Reference Manual_. ISBN "ISBN (identifier)") 978-0-13-089592-9.
- Enhancing the Development Life Cycle to Product Secure Software, V2.0 Oct. 2008 describes the security principles and practices that software developers, testers, and integrators can adopt to achieve the twin objectives of producing more secure software-intensive systems, and verifying the security of the software they produce.
- Dutta, Shiv; Hook, Gary (June 26, 2003). "Best practices for programming in C". _developerWorks_. IBM. Archived from the original on July 13, 2009. Retrieved January 21, 2010.

## External links

- Paul Burden, co-author of the MISRA C Coding Standards and PRQA's representative on the MISRA C working group for more than 10 years discusses a common coding standard fallacy: "we don't need a coding standard!, we just need to catch bugs!"
