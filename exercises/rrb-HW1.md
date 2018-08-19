# HW1

## Learning Git

<img src="../resources/HW1/learning_git/all_done.png" width="800" height="800">

### Introduction Sequence

<img src="../resources/HW1/learning_git/introduction_sequence/level1.png" width="800" height="800">
<img src="../resources/HW1/learning_git/introduction_sequence/level2.png" width="800" height="800">
<img src="../resources/HW1/learning_git/introduction_sequence/level3.png" width="800" height="800">
<img src="../resources/HW1/learning_git/introduction_sequence/level4.png" width="800" height="800">

### Ramping Up

<img src="../resources/HW1/learning_git/ramping_up/level1.png" width="800" height="800">
<img src="../resources/HW1/learning_git/ramping_up/level2.png" width="800" height="800">
<img src="../resources/HW1/learning_git/ramping_up/level3.png" width="800" height="800">
<img src="../resources/HW1/learning_git/ramping_up/level4.png" width="800" height="800">

### Moving Work Around

<img src="../resources/HW1/learning_git/moving_work_around/level1.png" width="800" height="800">
<img src="../resources/HW1/learning_git/moving_work_around/level2.png" width="800" height="800">

### A Mixed Bag

<img src="../resources/HW1/learning_git/a_mixed_bag/level1.png" width="800" height="800">
<img src="../resources/HW1/learning_git/a_mixed_bag/level2.png" width="800" height="800">
<img src="../resources/HW1/learning_git/a_mixed_bag/level3.png" width="800" height="800">
<img src="../resources/HW1/learning_git/a_mixed_bag/level4.png" width="800" height="800">
<img src="../resources/HW1/learning_git/a_mixed_bag/level5.png" width="800" height="800">

### Advanced Topics

<img src="../resources/HW1/learning_git/advanced_topics/level1.png" width="800" height="800">
<img src="../resources/HW1/learning_git/advanced_topics/level2.png" width="800" height="800">
<img src="../resources/HW1/learning_git/advanced_topics/level3.png" width="800" height="800">


## Hooks

![](/resources/HW1/hooks/post_commit.gif)

## Concepts

### In your own words, explain the difference between continuous integration, continuous delivery, and continuous deployment.
Continuous integration refers to the practice of merge new changes and features to the main track as often as possible, in order to avoid big conflicts as new features are added. Continuous delivery contemplates integration, but also provides the possibility to release new changes to clients in a required frequency (daily, weekly, monthly and so on). Continuous deployment is very similar to delivery, but in this case, releases are performed with no human intervention.

### How does DevOps team model (e.g., site reliability engineer) differ than a a NoOps team model (e.g. Netflix team)? What differences in architecture allow for a NoOps model?
A DevOps team model proposes the alignment of all development team with the operation team, in order to perform releases faster and better by standardized release processes, as well as more flexible implementations and tests. A NoOps team is similar to a DevOps team, but in this case, its processes are intended to be performed automatically.

### Explain the principle of Every Feature is an Experiment
This principle proposes that every new deployed feature will have its maintainance based on evidences. Different from features that are carefully designed and built, instanly deployed features are evaluated using performance and stability metrics, while being used by clients.

### Explain the principle of Be Fast to Deploy, Slow(er) to Release.
In this principle, the idea is to, when creating new features, it is important to explicit it to clients as gradual as possible, in order to not abruptly impact its usage.
