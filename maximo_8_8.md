IBM Maximo Application Suite 8.8 adds IBM Maximo Optimizer, and provides enhancements for IBM Maximo Manage, IBM Maximo Monitor, IBM Maximo Health, IBM Maximo Predict, IBM Maximo Health and Predict - Utilities, IBM Maximo Visual Inspection, IBM Maximo Assist, and IBM Maximo Mobile
Published: 26 July 2022AD22-0666[222-117]PLA software

At a glance
IBM Maximo Application Suite offers a single point of access to a full suite of asset lifecycle management capabilities. Maximo Application Suite 8.8 provides key enhancements across the applications within the suite, focused on the user experience, industry-specific updates, and core integration updates. Version 8.8 adds:

IBM Maximo Optimizer
Maximo Application Suite 8.8 also brings continuous delivery (CD) support (see the Program technical support section for details) and the following artificial intelligence (AI) driven asset performance capabilities:

IBM Maximo Monitor enhances its UI with a streamlined capability to create device type and metrics, accelerating startup of Maximo Monitor.
IBM Maximo Health charts view capability enables users to group any set of assets and visually analyze multiple key performance indicators (KPIs) related to health, unplanned downtime, and failure rate in charts that are designed to be easy to read.
IBM Maximo Predict adds lifecycle management for predictive models to the notebooks in IBM Watson Studio.
IBM Maximo Health & Predict - Utilities matrix feature enables users to identify and take action on high risk assets by using the configurable matrix.
IBM Maximo Visual Inspection adds anomaly detection as a model type that can be trained to detect objects and automatically identify one or more anomalies on each inspection object inference.
IBM Maximo Visual Inspection Edge inspection capability is enhanced to support complex automated workflows in pipelines that use a library of functions. It can also support a series of models that are in use sequentially to create a composite model.
Overview
Maximo Application Suite is an integrated suite, enabling easier access to a full set of asset lifecycle applications, with flexibility to start at any point in the asset lifecycle and expand into other areas. This flexibility uses a simplified, suite-based licensing structure and does not require additional provisioning. Deployment flexibility, through Red Hat OpenShift and hybrid cloud, enables diverse options for provisioning Maximo Application Suite across multiple clouds, on premises, or hosted as a managed service on IBM Cloud.

Starting with IBM Maximo Manage and expanding access to asset performance management applications, the Maximo Application Suite portfolio of offerings can enable your organization to obtain operational visibility of assets through their lifecycle with the potential for faster ROI, increased productivity, and operational uptime.

The Maximo Application Suite streamlines installation and administration, while enhancing the user experience with shared data, workflow, and user experience. Infused with AI, this offering is purpose-built to accelerate digital transformation of traditional asset maintenance into AI-driven maintenance.

Maximo Application Suite includes the following:

IBM Maximo Manage
IBM Maximo Monitor
IBM Maximo Health
IBM Maximo Predict
IBM Maximo Health and Predict - Utilities
IBM Maximo Visual Inspection
IBM Maximo Visual Inspection Edge
IBM Maximo Assist
IBM Maximo Safety
IBM Maximo Optimizer
New in Maximo Application Suite 8.8

Maximo Manage
Inventory Count Books application provides capability to record physical counts of inventory.
Autoscripting is enhanced to improve the debugging of scripts.
Maximo Monitor
The capability to create device types and metrics is streamlined and easier to use, enabling users to get metrics in the Maximo Monitor UI without having to call the API.
Remote operations engineers can view large data set without losing fidelity and can identify patterns and outliers in a line chart.
Maximo Health
Users can analyze KPIs for multiple assets in the charts view and take actions, such as export results externally, open a service request or work order, and add relevant assets to an asset investment optimizer project for Maximo Health and Predict - Utilities. The following charts are available:
Health pie chart breakdown
Unplanned downtime
Failure rate per manufacturer
Maximo Predict
Lifecycle management for predict models enables the data scientist using Watson Studio to determine if a model needs to be retrained based on new data.
Maximo Health and Predict - Utilities
The matrix capability enables users to visualize the number of assets at risk so that the most critical in need of maintenance or replacement can be identified and addressed to help ensure system or service availability, uptime, and safety:
Administrators can set up prerequisite requirements to run analysis; configure ready-to-use matrix axes that are being visualized such as Criticality, Health, End of Life, and Risk; and define categories (such as low, medium, and high), ranges, and colors.
Users can see matrix results and take actions to export externally, open a service request or work order, or add relevant assets to an asset investment optimizer project.
Maximo Visual Inspection
Anomaly detection is added as a model type and can run inspections by using the APIs. Anomaly detection can be trained to detect unexpected objects that deviate from the trained object and can automatically indicate when one or more anomalies are found on each inspection object inference.
The Detectron instance segmentation model training is updated to Compute Unified Device Architecture (CUDA) version 11, supporting the model to run on the NVIDIA Ampere GPUs and benefit from the numerous advantages of CUDA.
Tags are added to the data set UI, providing an easier way to define, filter on, and quickly distinguish training and inspection results data sets.
Maximo Visual Inspection Edge
Create complex automated workflows in pipelines that use a library of functions. It can also support a series of models that are in use sequentially to create a composite model.
Automatically trigger an inference when an object appears in the region of interest of the image.
Maximo Optimizer
Enhanced automation. Maximo Optimizer automates decisions for plans, schedules, and dispatch of resources for asset maintenance while balancing competing objectives and constraints. Maximo Optimizer includes IBM Maximo Optimization Framework for data and application management of optimization jobs and embeds IBM ILOG CPLEX Optimization Studio for solving the optimization models. Maximo Optimizer supports optimization models built in Java (JDK 11) and Python (Python 3.9).
Maintenance scheduling. Maximo Optimizer features large schedule optimization and also considers resource availability constraints in critical path analyses of maintenance schedules.
Support for asset investment optimization. Implementation of the asset investment optimization model included with Maximo and Predict - Utilities can help generate optimal plans for asset investment.
Unlimited virtual processor cores and models. Maximo Optimizer application default plan has no restrictions on number of virtual processor cores (within the overall VPCs entitled for MAS) and allows for unlimited number of models. The default models are provided by IBM. Clients can customize models to meet their unique requirements. Maximo Optimizer also enables parallel implementation of jobs.
Flexibility and cost-efficiency. Maximo Optimizer application features a reduced cost version, Maximo Optimizer Limited. This cost-efficient option limits deployment to two virtual processor cores, the use of a single model (provided by default by IBM or its extension), and serialized implementation of jobs.
To learn how IBM can host and manage the Maximo Application Suite for your enterprise, see Software Announcement 220-237, dated May 29, 2020.

Key requirements
The following offerings are required to use Maximo Application Suite 8.8:

Red Hat OpenShift Platform 4.8
IBM Cloud Pak for Data 4.0
The following are required to use Maximo Visual Inspection with Maximo Application Suite 8.8:

x86 system with at least one NVIDIA Pascal, Volta, Ampere, or Turing-architecture GPU
Planned availability date
July 26, 2022

Availability within a country is subject to local legal requirements.

See the Availability of national languages section for national language availability.

Description
Maximo Application Suite 8.8 (5737-M66)

Includes Maximo applications that consists of:

IBM Maximo Manage
IBM Maximo Monitor
IBM Maximo Health
IBM Maximo Predict
IBM Maximo Health and Predict - Utilities
IBM Maximo Visual Inspection
IBM Maximo Visual Inspection Edge
IBM Maximo Assist
IBM Maximo Safety
IBM Maximo Optimizer
Maximo Manage provides robust asset lifecycle management and maintenance management functionality that helps organizations improve asset life and lower cost of ownership. The following select Maximo Manage industry-specific and add-on products are included with Maximo Application Suite 8.8.

Maximo Manage industry solutions:

IBM Maximo Utilities
IBM Maximo Oil and Gas
IBM Maximo Nuclear
IBM Maximo Transportation
IBM Maximo Aviation
IBM Maximo Civil Infrastructure
Maximo Manage add-ons:

IBM Maximo Service Provider
IBM Maximo Health, Safety and Environment
IBM Maximo Asset Configuration Manager
IBM Maximo Spatial
IBM Maximo Connector for SAP Applications
IBM Maximo Connector for Oracle Applications
IBM Maximo Mobile
IBM Maximo Anywhere
Maximo Manage

Maximo Manage unifies robust asset lifecycle and maintenance management activities, providing insight into all enterprise assets, their conditions and work processes to achieve better planning and control.

Maximo Manage includes the following capabilities:

Work management. Asset-intensive organizations need to centrally manage planned and unplanned work activities, from initial request through completion and recording of actuals. Mobile workers need to accomplish more in the field, from reading meters, to capturing electronic signatures, to using bar code and RFID capabilities for asset tracking and management. The right combination of features can streamline work processes for increased productivity.
Asset management. An effective asset management solution must manage and optimize the use of all assets to achieve greater asset availability, reliability, and performance. The result is the capability to extend the asset's life because assets are better maintained. The capability to gather and analyze data about asset operations enables an organization to move from corrective maintenance (repairs made after a problem occurs) to preventive maintenance (scheduled repairs based on experience). The last step is a move to predictive maintenance (repairs made because data for a particular asset indicates that a failure is imminent).
Planning and scheduling. Planners and schedulers are at the heart of optimized work processes. To lower maintenance costs and improve resource usage, personnel need to graphically view all work orders and preventive maintenance schedules on a Gantt chart. Intuitive navigation through work orders can help dispatchers manage task and work dependencies.
Crews dispatched for special jobs in remote locations have an acute need for the proper skills, tools, and documentation, which is an expensive strategy used in the most critical situations. In addition, the capability to locate and track field resources on a public map can help improve workforce management and help increase the efficiencies of emergency work.
Supply chain management. As traditional business assets become more technology-enabled, operations and IT functions are increasingly converging in today's fast-paced business and technology environments. As a result, one way to effectively manage operational applications is to consolidate them. Organizations that seek to better manage their supply chains must:
Find support that can manage a wide variety of asset types and maintenance information
Establish a single technology system to manage virtually all asset types and information (for example, production, linear, facilities, transportation, and infrastructure) including calibration support and use of mobile capabilities
Have an integrated asset management solution that enables optimal return on assets, complies with regulations and helps minimize risk
Develop smarter processes and provide users with an innovative, fully integrated supply chain management system designed for asset intensive industries
Mobility. The widespread adoption of mobile technologies requires today's engineers, field technicians, and other business staff to use smart mobile devices to get their work done. These workers need to complete their projects within an optimized, IT-approved environment. By taking advantage of device-specific capabilities such as photos and voice-to-text features, mobile solutions enable technicians to capture the right information at the right time.
Calibration. This capability provides requirements for traceability and reverse traceability, calibration history data, calibration data sheets, and reporting.
Linear Assets. This capability is used for managing assets such as roads, pipelines, rail lines, and transmission lines. The linear visual control feature is designed to provide an improved user experience when administering linear assets.
Maximo Manage has options that address the special needs of industries:

Utilities. Provides special capabilities for linear assets, configuration management, and crew schedule or dispatching based on geospatial visual management tools. Suitable for transmission and distribution in water and wastewater, gas, and electric power.
Oil and gas, mining, and metals. Focuses on operational excellence by helping clients integrate safety, reliability, compliance, and performance into work management. Reduces costs through standardization, collaboration, and the adoption of better operational practices.
Manufacturing. Helps industries such as automotive, aerospace and defense, electronics or industrial products, food and beverage, or consumer products manage all their assets and maintenance activities. Uses concepts such as proper Lean Six Sigma terminology and complements product lifecycle management requirements.
Life sciences. Helps monitor, track, and manage equipment, facilities, mobile, and IT-enabled assets. Use calibration to manage tools, traceability, and management of e-signature and gold standards.
Healthcare. Helps manage the complex relationship between facilities and equipment readiness. Tracks and locates critical assets, monitors facility conditions, helps clients comply with reporting requirements and integrates with operational health information systems.
Nuclear power. Helps nuclear organizations manage work and asset management regulations through detailed state management, workflows, escalations, and e-signature. Suitable to assist in the management of client activities within stringent regulatory environments due to compliance, health, safety, and security.
Transportation. Provides detailed asset configuration management, fuel management, drivers' logs, and bay scheduling tools to help improve the availability and use of critical transportation assets in organizations that operate rail, road, and air traffic or logistics.
Service providers. Helps manage profitability and SLAs by linking customer service commitments with field teams that deliver services. Related service management activities for multiple customers are managed in a single cloud-based deployed instance that is accessible by an Android or Apple mobile device.
For more information about compatibility and coexistence for Maximo Manage and the Maximo Manage add-ons and industry solutions that are included with Maximo Application Suite, see the IBM Maximo Application Suite website.

Maximo Manage industry solutions

Maximo Utilities

Maximo Utilities helps enable clients in the electric, gas, and water utility industries to efficiently and effectively manage all their assets that are used in the transmission and distribution of electricity, gas, and water. The solution addresses key business challenges by optimizing asset performance, assisting clients in complying with industry regulations, and leveraging industry best practices. This solution is configurable to help clients keep pace with the ever-changing business and regulatory requirements of utilities. Additional capabilities have been added to support advanced planning and scheduling in Maximo Utilities including CPM for Crews, and Work Crew Gantt View.

Maximo Oil and Gas

Helps transform business models by integrating work and asset management, assisting clients with meeting their health and safety requirements, and integrated operations in a way that becomes essential for oil and gas businesses. This evolving offering can help businesses improve operational efficiency and effectiveness, help businesses meet their quality and safety requirements, and maintain their regulatory and compliance standards.

Key features and capabilities of Maximo Oil and Gas and Maximo Health, Safety and Environment Manager are:

Isolation Management application. To efficiently manage the work activities around isolating assets or locations that operate in a potentially dangerous environment, you can use the Isolation Management application. By using this application, you can create isolation certificates that provide a system of control to assist client with its plant and personnel safety procedures.
Operational Actions application. To efficiently manage the actions that are assigned to you or to your group, across multiple applications, you can use the Operational Actions application. By using this application, you can manage all of the actions for any Maximo Health, Safety and Environment Manager application for which actions are defined. You can review the actions that are to be completed, mark actions as complete, and add actions to an application. You can also create queries that are based on search fields that you choose and create reports from those queries.
Operator Log Book application. With this application, clients can review all the shift logs and their entries that relate to an asset or a location. Operator log books link shift logs together into a log book. An operator log book facilitates the organization of shift logs. Personnel who are taking over from an earlier work shift can review the progression of events and be aware of the possible need for action.
Ticket Templates application. Applying standardized templates to common and high-volume tickets saves time by letting the system populate values from the template into fields on the ticket. Clients can create and manage templates by using the Ticket Templates application. Clients can also add frequently used ticket templates to your Quick Insert portlet.
Maximo Nuclear

Maximo Nuclear is a robust enterprise asset management system that helps manage the lifecycle of assets of nuclear plants and fleets. It streamlines and automates key asset management processes while providing a single platform for managing all asset types. It also supports industry-specific requirements by modeling nuclear objects and business processes, including:

Technical specifications
Clearances
Permits
Surveillance testing
Corrective actions
Maximo Nuclear offers Extended Operational Management with major functionality added for complex capabilities required by nuclear power and other sophisticated power generation users.

Maximo Transportation

Maximo Transportation provides enterprise asset management to improve the productivity of all types of transportation assets. Assets include fleets of cars, trucks, buses, locomotives, rail vehicles, aircraft, vessels, and related linear assets. The software helps organizations meet regulatory requirements, extend asset life, optimize parts management, reduce road calls, and increase planned maintenance.

This industry-specific solution helps manage critical aspects of each assets lifecycle, while providing key capabilities such as automated alerts, campaigns, lifecycle accounting, fuel system integration, industry codes, motor pool capabilities, telematics integration, driver logs, warranty recovery, recent and repeat repair notification and mechanics clipboard. Maximo Transportation helps clients address the stringent requirements of regulatory bodies, while also adhering to industry-standard coding structures for industries such as trucking, rail, and aviation. Best practices are built into the solution to help extend asset life, optimize spare parts management, reduce road calls and incidents, and increase planned maintenance.

This is a robust solution for managing all transportation asset types, including fleets of cars, trucks, buses, locomotives and rail vehicles, aircraft, and vessels, adding capabilities to Maximo Manage. It can be combined with Maximo Asset Configuration Manager to support maintenance, repair, and overhaul of aircraft.

Maximo Transportation provides:

Advanced asset management capabilities for equipment status, meter change out and history, meter import, position codes, serial number changes and warranty recovery
Enhanced work management capabilities for campaigns, industry codes, labor certification, maintenance alerts, mechanics clipboard and outside repair orders
Extended inventory management features for cycle counting and fuel tank management
Maximo Aviation

Maximo Aviation provides robust lifecycle management and maintenance management capabilities for both rotary and fixed wing aircraft. Its focused tool set can help organizations that provide maintenance, repair, and overhaul services in the aviation market to improve the performance of their operations. With its advanced asset management functions, Maximo Aviation can help your organization improve asset life, reduce aircraft downtime, and lower the cost of ownership.

Maximo Aviation feature set includes:

Enhanced data access control that provides more fine-grained access control to data
Maintenance program management for equipment that enables equipment maintenance tasks to be defined as part of the operator maintenance program (OMP)
Work package enhancements that enable users to define and manage the contents of a work package that is aligned to the operational processes of an organization
Capability to allocate aircraft to flight schedules, validate the availability of the aircraft against planned maintenance, and import flight schedules from third-party applications
Capability to define preflight checks and aircraft preparation in advance of the planned flights
Capability to view the current role of an aircraft (for example, commercial) and to apply role changes based on predefined job cards
Enhanced receiving and inspection process
Integrated shipment and inventory usage processes
Capability to provide a fixed price quote
Support for customer tool rentals
Support for calibration
Maximo Civil Infrastructure

Maximo Civil Infrastructure integrates current IBM asset lifecycle management capabilities to support operators in monitoring the condition of civil infrastructure, such as bridges, roads, and tunnels throughout the lifecycle of the infrastructure. It integrates inspection, anomaly tracking, and maintenance activities to help organizations improve asset life, keep critical systems up and running, and potentially lower total cost of ownership of civil infrastructure.

Maximo Civil Infrastructure provides the capability to:

Track and manage assets, including components of a structure, such as cables, hangers, and decks as well as related assets, such as fans, dampers, and dehumidifiers
Manage planned and unplanned work activities, ranging from routine maintenance to complex structure updates
Perform and record the results of inspections on steel and concrete structures, roads, rails, and related equipment
Track contractor work, purchase orders, and contracts
Visualize planned work and anomalies in asset, linear, spatial, or schematic views, accounting for the differing user interactions based on the different structures
Maximo Civil Infrastructure provides infrastructure owners an accurate account of the history, condition, and planned activity related to assets on and in bridges, roads, tunnels, and railways. With Maximo Civil Infrastructure, organizations can more efficiently inspect structures and manage the anomalies identified during inspections as well as manage routine work on structures. In addition, it allows for the connection of sensors on structures to gain deeper insights into the infrastructure that they are managing.

Maximo Civil Infrastructure enhances core Maximo Manage functionality using the add-ons needed to perform the initial configuration of security groups to focus on the applications most relevant to the management of civil infrastructure. With Maximo Civil Infrastructure, organizations can begin the journey towards more automated and intelligent management of civil infrastructure.