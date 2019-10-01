---
title: "Continuous Delivery"
number: 8
anchor: continuous-delivery
anti_pattern:
    - "manual deployment to the environment by checklist"
---

CD describes a process for delivering an artifact. The basic concept is to unify this process for all environments. There are different delivery strategies: blue / green, canary, and others. In most cases smaller changes delivered have less 
probability to break production environment. Value delivery must always be in working state and deliver value to customers upon the first business request.
The next future of Continuous Delivery is Continuous Deployment.