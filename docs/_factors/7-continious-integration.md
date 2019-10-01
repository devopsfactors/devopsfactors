---
title: "Continious Integration"
number: 7
anchor: continious-integration
anti_pattern:
    - "do not test the application"
    - "implement artifact delivery in scope of the CI process"
---

CI is a process describes the sequence of steps for building an application. Artifact must be created as result of the CI process. An artifact is a compiled application, ready for further delivery.
The CI process with the testing pyramid gives confidence in the artifact, and guarantees that the assembled application will definitely work. In this case, we gain confidence in the changes, and it becomes possible to deliver value to users more often.