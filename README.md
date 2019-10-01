<p align="center">
  <h3 align="center">devopsfactors</h3>

  <p align="center">
    Methodology for building proper DevOps culture
  </p>
</p>

<br>


### 1. Priorities
Priorities for Ops and Dev teams should be the same. One managed for both teams improving culture as well. This combination allows you to implement error budget and reduce the overhead of communication between teams. Priority item is the most important and cannot be changed (and not depends on the implementation).

Design smell:
> Ops is responsible for stability, and Dev for features

### 2. Communication
Communication is very important. Communication is the foundation of DevOps. Your Soft skills are necessary and often more important than the technical background. Coming to a new company, you will most likely have to promote culture, break stereotypes and often meet poor engagement people in the near-DevOps sphere.

Design smell:
> constantly sit in the headphones, and work only on your part of the system

### 3. Automation
The concept of Infrastructure as Code is fundamental to the DevOps methodology.
IaC is important and necessary in order to recover from an incident, with a minimum of effort to move to another platform, versioned changes for transparency of management, the convenience of working on infrastructure in a team, and the ability to roll back to a previous state. Also, the infrastructure must be tested qualitatively, according to the principles of the testing pyramid (unit, integration, system tests).

Design smell:
> manual undocumented changes

### 4. Team structure
A good DevOps team should have full interchangeability, a flat structure and mutual assistance. If you have several products or dedicated parts of the system in your company, it is necessary to periodically take tasks not from your main specialization to expand your horizons and cultivate interchangeability. A good DevOps team should look like a complete system - all team members can complete the task that has arrived.

Design smell:
> assign team members to a product or part of a system

### 5. Sharing experience
A strong knowledge gap, even within the same team, always entails problems. A completely different expertise in people on different components of the platform will always lower the team’s performance and complicate the prediction of delivery. The presence of unique skills in one engineer makes him indispensable and sooner or later he turns into a living point of failure. Therefore, it is necessary to pre-determine gaps and their criticality in advance, quickly eliminate them by exchanging experience and information. High-quality documentation and transparency of the development process greatly simplifies this process.

Design smell:
> to file alone the tool, in the code and use of which only its creator can figure out, leave it without documentation and quit.
> share high priority tasks without asking for the opinions of your teammates and not share the results of its implementation.

### 6. Monitoring
DevOps team must predict problems, not just put out fires.

### 7. Continuous Integration
CI is a process describes the sequence of steps for building an application. Artifact must be created as result of the CI process. An artifact is a compiled application, ready for further delivery.
The CI process with the testing pyramid gives confidence in the artifact, and guarantees that the assembled application will definitely work. In this case, we gain confidence in the changes, and it becomes possible to deliver value to users more often.

Design smell:
> do not test the application

> implement artifact delivery in scope of the CI process

### 8. Continuous Delivery
CD describes a process for delivering an artifact. The basic concept is to unify this process for all environments. There are different delivery strategies: blue / green, canary, and others. In most cases smaller changes delivered have less 
probability to break production environment. Value delivery must always be in working state and deliver value to customers upon the first business request.
The next future of Continious Delivery is Continious Deployment.

Design smell:
> manual deployment to the environment by checklist

### 9. Continuous improvement
The main feature of DevOps methodology is continuous iterative improvement. It's not necessary to theoretically design the most fault-tolerant and stable system with ideal processes for an infinite amount of time - on the contrary, cyclically introduce improvements and receive fast feedback. In this case, it will be possible to design a platform that will meet most of your requirements in a minimum amount of time. In the process of development of the platform must be a constant professional growth.

Antipatterns:
> for a long time, to the smallest details, think through the nuances of the system design, but do not implement anything

### 10. Incident Management
If something went wrong with your production - you need to fix it first. And only when the system came to a stable working condition, you can begin to understand what's happened and how to prevent it in the future. As a rule, after notification of an incident, the support engineer quickly evaluates the problem and problem components, gathers people with this area of ​​responsibility and manages the recovery process. According to the results, it is necessary to describe the incident in the bug tracker, conduct a retrospective and make the decisions necessary to prevent it in the future.

Design smell:
> find out why the system does not work, instead of online recovery

> write documentation on how to repair, instead of preventing globally

### 11. Roadmap
A good DevOps team should have a fuzzy development plan for the next 3-6 months with the main global goal that reach business values. There is no point in creating detailed plan and describe the technical implementation - it is very likely that the team will depart from it at certain points and change the tactics of achieving the global goal.

Design smell:
> clearly and thoroughly outline the development plan for the next 10 years

### 12. Rational decision making
There are a huge number of tools to solve each individual problem, and you need to choose the right tool for the job as correctly as possible and not chase the fashion trends that are constantly appearing. This is rational for solving problems of low and medium levels. In the case of the design architectural solutions it is worth paying attention to modern practices and approaches. As a result, this will indirectly save time and money on remodeling and implementing “bicycle”. There are two good rules here: 'plan before execute' and 'code wins arguments' (in the sense that it is better to try and compare several solutions on your own tasks than blindly grab the tools from Github)

Design smell:
> a new beta version of the framework X is released, tomorrow we’ll move
