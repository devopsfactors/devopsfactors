---
title: "Incident Management"
number: 10
anchor: incident-management
anti_pattern:
    - "find out why the system does not work, instead of online recovery"
    - "write documentation on how to repair, instead of preventing globally"
---

If something went wrong with your production - you need to fix it first. And only when the system came to a stable working condition, you can begin to understand what's happened and how to prevent it in the future. As a rule, after notification of an incident, the support engineer quickly evaluates the problem and problem components, gathers people with this area of ​​responsibility and manages the recovery process. According to the results, it is necessary to describe the incident in the bug tracker, conduct a retrospective and make the decisions necessary to prevent it in the future.