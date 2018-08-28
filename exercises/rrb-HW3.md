# HW3
Reading the article "An empirical study on principles and practices of continuous delivery and deployment", relate the principles and practices of continuous delivery and deployment with the main issues and benefits on Dev and Ops teams activities, mentioning - if pertinent - ITIL practices discussed in this class

Common practices: continuous integration, health checking, "Developer on Call", canary testing

Rare practices: dark launches, A/B testing

Architechtural corcerns rules CD (Continuous delivery and deployment) practices
Legacy applications require costly and difficult architectural redesign

CD practices are most commonly used in Web-based applications

Study divided in five practice categories:
- Automation
- Rollout
- Quality assurance
- Issue detection and handling
- Awareness

### Continuous Integration:
- Trunk-based Development: All teams contribute to a single branch (master)
    - Use of Feature Toggles: Flags evaluating whether a code block is to be executed (or not)
- Developer Awareness: Separate team in small groups and perform transparency between those groups

### Continuous Deployment:
- Deployment Pipeline: Organize the steps of implementation release into a structured pipeline
    - Perform manual or automated tests
- Health Checks: Post-deployment tasks for evaluating the deployed implementation
- "Developer on Call": Need for developers to be available after deployment
    - If a problem occurs, fixes can be performed faster

### Partial Rollouts:
- Canary Releases: Perform run-time releases in a subset of the existent users
    - Test small changes
- A/B Testing: Run two or more version of the same application in parallel
    - Evaluate which features performs better
- Dark Launches: Perform stealthily software features to users
    - Gradually obtain users feedback, without having abrupt experience changes
