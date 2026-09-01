---
layout: post
title: About
---

# Max Nicosia, PhD

## Software R&D & Systems Engineer

I am a Software R&D and Systems Engineer with over 10 years of hands-on experience designing, prototyping, implementing and validating complex technical systems across simulation, XR, safety-critical software, distributed systems, hardware/software integration and low-latency applications.

I specialise in taking early-stage technical concepts from requirements and system architecture through prototyping, implementation, experimentation, optimisation and validation. My background includes technical leadership at Woven by Toyota, production low-latency C++ systems, UK Ministry of Defence-funded R&D, XR and simulation platforms, distributed sensor middleware, and human-in-the-loop systems.

My strongest development languages are **C++, C# and Python**, with additional experience in TypeScript, JavaScript, Java and a broad range of systems, research and visualisation technologies.

Holder of a 5-year visa.

# Table of Contents

- [Core Expertise](#core-expertise)
- [Technical Skills](#technical-skills)
- [Work Experience](#work-experience)
- [Projects](#projects)
- [PhD Research](#phd-research)
- [Education](#education)
- [Earlier Research and Development](#earlier-research-and-development)
- [Publications](#publications)
- [Patents](#patents)
- [Additional Projects](#additional-projects)
- [Languages](#languages)

# Core Expertise

R&D & Rapid Prototyping • Systems Architecture & Design • Simulation • XR / AR / VR • Safety-Critical Systems • Human-in-the-Loop Systems • Verification & Validation • Hardware/Software Integration • Distributed Systems & Middleware • Low-Latency Software • Performance Optimisation • Technical Leadership

# Technical Skills

### Programming Languages

C / C++ • C# • Python • Java • TypeScript • JavaScript • Ruby • R • SQL

### Systems and Software Engineering

Multithreading • Distributed Systems • Middleware • TCP/IP • UDP • WebSockets • Windows/Linux Sockets • CAN • Custom APIs • Dependency Injection • Automated Testing • CI/CD • Performance Profiling • Low-Latency Software • Agile / Scrum • Test-Driven Development

### Simulation / XR / Interactive Systems

Unity • Unreal Engine • AR / VR / XR • Vehicle Simulation • Physics Simulation • 2D/3D Adaptive Interfaces • Real-Time Visualisation • Human-in-the-Loop Systems • Eye Tracking • Sensor Integration • Vehicle/Pedestrian Pathfinding • Behaviour Trees • Blackboards • Animations • Shaders / Filters • Mixamo • LOD • Dynamic Asset Loading • Serialisation / Marshalling • Unreal Blueprint

### Parallel / High-Performance Computing

OpenMP • MPI • pthreads • Lockless Programming • Synchronisation • Memory Barriers • Ring Buffers • Memory Pools • Cache Alignment • Compiler Optimisation

### Data / Scientific Computing / Machine Learning

NumPy • SciPy • Pandas • scikit-learn • PyTorch • Jupyter • d3.js • Bayesian Optimisation • Statistical Testing • Statistical Model Fitting • Sensor Fusion • Machine Learning • Scientific Visualisation • Experimental Design • Big-Data Analysis • MapReduce / Hadoop

### Tools / Platforms

Docker • Podman • CMake • Make • GitHub Actions • Git • Boost • psutil • Bash • PowerShell • Gradle • AWS • Linux • Android • iOS • Xcode • React • CSS • MySQL / SQL

### Project / Research Management

Stakeholder Meetings • Requirements Elicitation • Milestone Planning and Prioritisation • Technical Leadership • Team Management • Mentoring • Research Proposals • Live Demonstrations • Technical Presentations • Experimental Design and Validation

# Work Experience

## Woven by Toyota — Technical Lead, XR Safety / Driver Sync Assist

**June 2024 – March 2026 · Tokyo, Japan**

Technical lead for the judgement and simulation workstream of a driver-safety and XR research programme.

- Led the judgement and simulation workstream, directly managing up to 2 engineers and providing technical direction, mentoring, task allocation and code review.
- Re-architected an inherited Unity environment consisting primarily of loosely structured scenes and assets into a maintainable C# simulation platform suitable for repeatable experiments, safety validation and product development.
- Restructured the codebase using interfaces, inheritance, dependency injection and the Humble Object pattern, improving maintainability and enabling automated testing.
- Developed automated tests covering shared physics calculations and safety judgement for vehicles, pedestrians, traffic lights and other obstacles.
- Designed and implemented driver-safety judgement using live and simulated data, including probabilistic collision risk, driver reaction time and cognitive-load considerations.
- Developed vehicle and environmental physics logic and integrated Vehicle Physics Pro for realistic vehicle and engine simulation.
- Developed reproducible vehicle and pedestrian navigation/pathfinding for controlled simulation scenarios.
- Implemented capture, playback and re-simulation capabilities for repeatable experimentation, testing and analysis.
- Developed C/C++ wrappers and CAN interfaces for simulation hardware inputs including steering, speed, acceleration, pedals and feature controls.
- Profiled and optimised the Unity simulation, eliminating repeated execution and other bottlenecks to achieve the target of **60+ FPS**, typically reaching approximately **90–120 FPS** depending on scene complexity.
- Maintained interactive performance while driving **5 × 4K displays plus 2 × HD mirrored displays**.
- Supported experiments with **16 participants** using Latin-square counterbalancing for verification and validation of judgement and safety logic.
- Defined testing and product-verification strategies and produced documentation supporting PoC and beta-gate approval.
- Presented quarterly technical demonstrations and project progress to product management.
- Developed visualisation technology resulting in patent filings in Japan and the United States and was named as a co-inventor.
- Delivered project milestones through PoC verification and beta gates, allowing the project to progress into early production development.

**Technologies:** C#, C++, Unity, CAN, Vehicle Physics Pro, automated testing, simulation, performance profiling, XR, hardware integration

## FinStadiumX — Strategic Software Development Team Lead

**April 2024 – May 2024 · Tokyo, Japan**

- Led and mentored a team of 2 engineers developing and maintaining production low-latency C++ financial transaction systems.
- Designed, implemented and deployed C++ components for high-frequency equities, futures and dark-pool transaction processing on Linux.
- Worked on production systems handling approximately **2,000–5,000 transactions per second** at approximately **20 ms latency**, with transaction flows associated with approximately **¥7–10 billion in daily revenue per product**.
- Applied low-latency techniques including memory barriers, lockless data structures, ring buffers, memory pools, cache alignment and compiler optimisation.
- Profiled legacy components to identify performance bottlenecks and candidates for redesign or reimplementation.
- Began formalising latency and performance testing for production components.
- Developed build procedures across Linux and Windows using CMake, Make and Visual Studio.
- Maintained Docker and Podman development, test and production environments.
- Ensured component compliance with FIX protocols.
- Introduced automated CMake build, test and deployment scripts that prevented defective changes from reaching production.
- Mentored engineers and reorganised work allocation around technical strengths and verifiable development priorities.

**Technologies:** C++, Linux, CMake, Make, Docker, Podman, FIX, low-latency systems, multithreading, lockless programming

## Tokyo Academics — Head of Research

**November 2022 – March 2024 · Tokyo, Japan**

- Managed approximately 20 part-time researchers supervising student research projects.
- Managed research operations together with divisional sales and marketing strategy.
- Supervised computer-science projects involving software prototyping and machine learning across multiple technologies.
- Grew the research programme from approximately 20 students to around 50–60 students.
- Achieved approximately **125% growth in sales receipts** against a 50% growth target.

## Cambridge Intelligent Systems UK Ltd — CEO, Co-founder & Technical Lead

**November 2017 – June 2025 · Cambridge, UK / Remote**

Co-founded an R&D consultancy delivering applied research and software prototypes for the UK Ministry of Defence.

- Secured approximately **£150,000 in combined funding** across two UK MoD R&D programmes in XR, simulation, human factors and safety-critical systems.
- Served as principal engineer and sole software developer, taking projects from proposals and stakeholder requirements through architecture, implementation, integration, experimentation, demonstration and final delivery.
- Worked directly with MoD and DSTL engineers and researchers throughout project inception, requirements definition, development and evaluation.
- Planned and managed milestones, deliverables, budgets and procurement and wrote research proposals and contract bids.
- Personally presented and demonstrated completed systems to senior military stakeholders.

See [Projects](#projects) for detailed technical descriptions, images and demonstration videos.

## University of Cambridge, Department of Engineering — Research Associate

**October 2019 – July 2020 · Cambridge, UK**

- Supported research-group software and experimental infrastructure while continuing development and validation associated with doctoral research.
- Developed and maintained support software in C++, TypeScript and Bash.
- Performed database maintenance, scripting, experimental data collection and general technical support.

## Cambridge University Technical Services Ltd — Consultant

**May 2017 – December 2017 · Cambridge, UK**

Adapted technology developed during my PhD into an externally funded distributed attention-management demonstrator for a safety-critical air-traffic-control use case.

See [Distributed Multi-Display Middleware](#distributed-multi-display-system-and-middleware-for-close-proximity-operator-gaze-and-attention-tracking--project-acc101965) below for technical details, images and demonstration video.

# Projects

## Attention-Aware System for Mixed and Augmented Reality Controls in Armoured Vehicles — Project ACC2006330

**March 2020 – February 2021**

Project delivered through [Cambridge Intelligent Systems UK Ltd](http://cambridgeintelligentsystems.co.uk/).

### Objectives

The project developed a VR simulation environment for evaluating and training operators' responses to configurable threats under different attention-aware visualisation strategies. Visual aids used operator gaze direction to adapt, activate or deactivate, alongside menu interaction using an UltraLeap sensor.

### Project Highlights and Deliverables

- Worked with DSTL/MoD stakeholders to elicit and refine system requirements.
- Designed and developed the complete Unity/C# XR/VR simulation platform.
- Delivered configurable scenarios across open snowy and urban environments.
- Developed NPCs, threat behaviours, spawning, navigation/pathfinding, animations and sounds.
- Implemented NATO-compliant threat symbology, 3D and minimap visualisations, 360-degree environmental views, threat-tagging interfaces and operator-performance logging.
- Implemented dynamic attention-aware visualisation, including attended/unattended region tracking, out-of-view threat pointers and animated NATO symbols for unattended threats.
- Integrated UltraLeap interaction and Oculus Rift VR hardware.
- Personally delivered interim and final live demonstrations to DSTL, MoD and armed-forces stakeholders.
- Software was subsequently incorporated into tank-operation training practices.

The project is included in the [UK Government DASA funded-contract listing](https://www.gov.uk/government/publications/accelerator-funded-contracts/defence-and-security-accelerator-funded-contracts-1-april-2019-to-31-march-2020#open-call-for-innovation).

![Virtual Environment For Threat Detection](/media/urban.png "Virtual Environment For Threat Detection")

[![Watch Virtual Environment For Threat Detection Video](/media/prev_urban_vid.png)]({{ site.baseurl }}/media/Demo_urban.mp4)

**Technologies:** Unity, C#, VR/XR, UltraLeap, Oculus Rift, simulation, HCI, adaptive interfaces, pathfinding, 3D visualisation

## Mixed Reality Controls for Armoured Vehicles — Project ACC2000981

**December 2018 – October 2019**

Project delivered through [Cambridge Intelligent Systems UK Ltd](http://cambridgeintelligentsystems.co.uk/).

### Objectives

The project investigated the use of mixed-reality controls inside armoured vehicles. A VR environment was used to simulate a future AR deployment, including views from inside and outside the vehicle and interaction with virtual controls.

### Project Highlights and Deliverables

- Worked with DSTL/MoD stakeholders to elicit requirements for the system.
- Designed and developed the complete Unity/C# VR prototype.
- Developed GVA-compliant interface concepts and interactable menus following domain specifications.
- Implemented spherical 360-degree simulated camera views with direct manipulation through UltraLeap gestures.
- Developed multi-axis cameras for interior and exterior vehicle views.
- Implemented a head-up interface incorporating a compass, minimap, threats and a 360-degree augmented spherical view with threat markers and pointers.
- Integrated UltraLeap hand interaction and Oculus Rift hardware.
- Investigated replacing physical vehicle controls with mixed-reality interaction to reduce physical hardware requirements and vehicle weight.
- Personally delivered interim and final demonstrations to MoD/DSTL and armed-forces stakeholders.
- Concepts subsequently informed future vehicle-development work.

![Virtual GVA Images](/media/gva.png "Virtual GVA Images")

[![Watch Virtual GVA Demo Video](/media/prev_gva_vid.png)]({{ site.baseurl }}/media/gva_demo.mp4)

**Technologies:** Unity, C#, VR, AR concepts, UltraLeap, Oculus Rift, 360-degree visualisation, GVA, HMI

## Distributed Multi-Display System and Middleware for Close-Proximity Operator Gaze and Attention Tracking — Project ACC101965

**May 2017 – December 2017**

Project delivered through [Cambridge University Technical Services Ltd](https://www.enterprise.cam.ac.uk/for-the-university/be-a-consultant/).

### Objectives

The project adapted the distributed attention-management architecture developed during my doctoral research into a separate safety-critical demonstrator. The target use case was potential deployment in air-traffic control, using eye trackers to provide attention events and information to applications through an API.

### Project Highlights and Deliverables

- Attended briefings and requirements meetings with DSTL/UK MoD and National Air Traffic Services (NATS) personnel at secured sites.
- Delivered six software packages, a live demonstrator and supporting reports.
- Deployed the system across **5 application computers with 5 eye trackers**, plus central coordination and time-synchronisation services.
- Developed C/C++ middleware capable of receiving eye-tracking data from individually connected machines and aggregating it into global attention events.
- Integrated directly with Tobii eye-tracking drivers.
- Implemented data fusion to determine operator attention focus.
- Developed a configurable discretisation grid for matching application-data changes to eye-fixation events.
- Developed a purpose-built API with subscriptions and hooks for delivering attention messages/events to applications.
- Developed a JavaScript/d3.js overlay library capable of drawing over web applications to highlight data points, visualise relative data age and show the relative position of unattended changes across displays.
- Demonstrated the system as a potential enhancement to RAF air-traffic-control systems.

![Watch Multi-display Inattention Management Middleware System Video](/media/eye.png "Multi-display Inattention Management Middleware System")

[![Watch Multi-display Inattention Management Middleware System Video](/media/prev_eye_vid.png)]({{ site.baseurl }}/media/final_cambridge_480p.mp4)

**Technologies:** C/C++, JavaScript, TypeScript, d3.js, TCP/IP, distributed systems, Tobii eye tracking, middleware, APIs, data fusion

# PhD Research

## Design, Implementation and Evaluation of an Attention Management System

**University of Cambridge · PhD Engineering (2014–2023)**

Designed, implemented and experimentally validated a distributed attention-management architecture for complex multi-display and multi-task human-in-the-loop systems.

The research covered the full engineering lifecycle from identifying human-machine-system challenges and designing the system architecture through software implementation, sensor integration, simulation, experimentation and statistical validation.

### System Architecture

Developed four integrated software systems:

1. Sensor system
2. Test application
3. Simulator
4. Attention-management system

The architecture supported distributed deployments in which multiple networked computers, displays and sensors collectively represented an operator's working environment.

### C++ Sensor and Middleware Systems

- Developed standalone multithreaded C++ sensor drivers.
- Integrated directly with Tobii eye-tracker APIs and structured-light sensors.
- Developed multithreaded C++ aggregation and routing middleware.
- Processed gaze and head-tracking information and inferred operator attention across displays and applications.
- Distributed state, data and attention events across networked computers.
- Developed purpose-built APIs for application integration.

### Python Attention Management and Simulation

Developed multithreaded Python software responsible for:

- Aggregating global application and operator state.
- Building performance baselines.
- Calculating performance indicators.
- Identifying attention-management problems.
- Generating and scheduling adaptive interventions.

Also developed a Python simulator capable of replaying captured operator actions to model alternative outcomes under different visualisation/intervention policies.

### Distributed Hardware Integration

Engineered the architecture around hardware constraints requiring independent computers for eye-tracker/display combinations.

The system architecture was capable of supporting up to:

- 8 application computers
- 8 Microsoft Kinect 2.0 structured-light sensors
- 8 eye trackers
- Dedicated coordination infrastructure
- Dedicated time synchronisation

The final research experiment used 4 application computers with eye trackers plus central coordination and time servers.

### Monitoring and Visualisation

- Developed live monitoring components in Python using TCP and WebSockets.
- Developed TypeScript/React/d3.js visualisation tools for live and retrospective operator-performance analysis.
- Developed reusable research-group libraries for live graphing, Unity prototyping, networking, sensor polling and machine-learning workflows.
- Deployed and maintained VMs and Docker containers used by the research group for experiments and computational workloads.
- Developed Python/psutil monitoring scripts for local research servers.
- Used AWS to build machine-learning models and schedule parameter-search workloads based on previous results.

### Sensor Fusion and Machine Learning

Developed an application exposing operator head pose through an API in a **5 m × 5 m room fitted with 8 Microsoft Kinect 2.0 sensors**, using a purpose-built machine-learning classifier.

This work formed part of research published at IEEE HCCS 2018.

### Experimental Software

Developed Android applications to collect data for Fitts' Law experiments used by the research group.

### Experimental Validation

Designed and conducted three iterative studies combining human-participant experimentation, simulation and system validation.

Participant cohorts included:

- Study 1: 16 participants
- Study 2: 8 participants
- Study 3: 16 participants

Study designs included within-subject experiments and Latin-square counterbalancing.

Adaptive interventions addressed:

- Poor prioritisation of targets
- Incorrect allocation of actions between tasks
- Errors caused by misunderstandings
- Poor situational awareness

Simulation results based on participant data demonstrated statistically significant improvements in primary and secondary task performance in **3 of 4 trials**.

The doctoral architecture subsequently formed the basis of externally funded MoD/RAF demonstrator work.

**Technologies:** C++, Python, TypeScript, JavaScript, React, d3.js, TCP/IP, WebSockets, Tobii eye tracking, Kinect, sensor fusion, machine learning, AWS, Docker, distributed systems, simulation, experimental design

# Education

## PhD in Engineering — University of Cambridge

**2014 – 2023 · Cambridge, UK**

- Thesis: *Design, Implementation and Evaluation of an Attention Management System*
- Supervised by Prof. Per Ola Kristensson.
- Fully funded by DSTL (UK MoD).

## MPhil in Advanced Computer Science — University of Cambridge

**2012 – 2013 · Cambridge, UK**

**Thesis:** *A Privacy-Preserving Advertisement Delivery System*

- Developed a Python advertisement-delivery server and purpose-built Chrome extension.
- Used a publish-subscribe architecture designed to prevent identification of individual users and their data preferences.
- Connectivity and privacy mechanisms used RSA and WebSockets.
- Relevant coursework: Security, Data-Centric Networks, Network Theory, Distributed Networks and Mobile Application Development.

## BSc in Computer Science — University of St Andrews

**2008 – 2012 · St Andrews, UK**

**Thesis:** *A Reduced Implementation of INLPv4 (Identifier-Locator Network Protocol) for Linux*

- Implemented a reduced version of the INLPv4 protocol described in RFC 6740 in C as a Linux kernel-level module.

# Earlier Research and Development

## University of St Andrews — Research Assistant

**January 2012 – September 2012 · St Andrews, UK**

- Worked with Dr. Per Ola Kristensson and Dr. Antti Oulasvirta investigating how users perceived their own performance while interacting with computer interfaces.
- Developed C#/XNA experimental software for Microsoft Surface PixelSense 2.0 hardware.
- Designed and supported Fitts' Law experiments.
- Performed statistical modelling and analysis using R and generated scientific visualisations.
- Research resulted in the ACM CHI 2014 publication *Modeling the Perception of User Performance*.

## iGEM Internship — University of St Andrews

**June 2011 – September 2011 · St Andrews, UK**

- Funded by SULSA and the Wellcome Trust.
- Contributed to a synthetic-biology project investigating a kill switch for delivery of a drug payload.
- Contributed to project design and laboratory experiments.
- Modelled reaction rates using MATLAB and maintained the team's wiki.
- The project received an **iGEM Gold Medal**.

## University of St Andrews — Research Assistant

**May 2011 – June 2011 · St Andrews, UK**

- Developed a Python simulator for modelling mosquito disease transmission and resistance.
- Generated constrained graphs to emulate mosquito mating patterns.
- Developed AWK and Bash scripts to automate analysis and plotting in R.
- Contributed to a second project using clustering algorithms to identify frequently visited locations and behavioural patterns from seal-tracking data.

## University of St Andrews — Software Developer

**August 2010 – September 2010 · St Andrews, UK**

- Developed functionality for a package providing binary OpenMath encoding for the GAP mathematical software.
- The package was subsequently published in the GAP package ecosystem.
- [GAP OpenMath Package](https://www.gap-system.org/Packages/openmath.html)

## Technical University of Denmark (DTU) — C Developer

**June 2010 – August 2010 · Copenhagen, Denmark**

- Developed accessibility functionality in C for the Evince PDF reader / GNOME desktop ecosystem.
- Worked on Orca screen-reader integration and navigation.
- Produced documentation and guides for blind users installing Vinux, an Ubuntu distribution for visually impaired users.

# Publications

- Nicosia, M. & Kristensson, P. O. (2024). **Risk management in human-in-the-loop AI-assisted attention aware systems.** In *Putting AI in the Critical Loop* (pp. 81–92). Academic Press.
- Nicosia, M. & Kristensson, P. O. (2021). **Design principles for AI-assisted attention aware systems in human-in-the-loop safety critical applications.** In *Engineering Artificially Intelligent Systems: A Systems Engineering Approach to Realizing Synergistic Capabilities*. Springer Nature.
- Nicosia, M. & Kristensson, P. O. (2020). **A conceptual design of an inattention management middleware with adaptive target saliency.** Proceedings of the 41st IEEE Aerospace Conference. IEEE Press.
- Nicosia, M. & Kristensson, P. O. (2018). **Inattention management middleware for human-in-the-loop multi-display applications.** Proceedings of the IEEE Workshop on Human-Centered Computational Sensing (HCCS 2018), 71–76. IEEE Press.
- Nicosia, M., Oulasvirta, A. & Kristensson, P. O. (2014). **Modeling the perception of user performance.** Proceedings of the 32nd ACM Conference on Human Factors in Computing Systems (CHI 2014), 1747–1756. ACM Press.

# Patents

## User Status Notification Method and User Support System

**Co-inventor with Y. Fukui**

- Japanese Patent Application No. **2025-063631**, filed April 2025.
- Related US patent application, filed January 2026.

# Additional Projects

## Adaptive Learning Prototype

Developed an iOS mobile application prototype in Unreal Engine using Bayesian optimisation to dynamically adapt learning experiences based on measured user performance.

# Languages

- **English:** Native
- **Spanish:** Fluent
- **German:** Business
- **Japanese:** Basic
