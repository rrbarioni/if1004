# HW4
## Continuous delivery and continuous deployment
### Reading the post of Carl Caum, discuss the main issues, differences and benefits between continuous delivery and continuous deployment.
Continuous delivery includes processes which makes code able to be inserted to the "real world" environment; it ensures business applications and services to work at expected rigorous testing environments. Continuous deployment corresponds to the act of bringing the implemented processes to the real world environment.

## Branch versus trunk-based approaches
### Reading the article of Paul Hammant, discussing branch versus trunk-based approaches, describe in your opinion the main advantages and disadvantages of each approach.
In trunk-based approaches, the duration of deploying implementation to the client side is faster. However, this approach is more prone to conflict occurences. Google and Facebook works with trunk-based approaches. In the other side, branch developing takes more time between team members integration to deployment, however it is less prone to conflict occurences.

## Heavily baked and lightly baked images
### Reading this article, explain, in your words, how are the factors that I should consider to decide between heavily baked and lightly baked images.
When deciding between heavily and lighly baked images, you should consider the amount of changes you want to perform; for small changes, lightly baked images would be your choice, once it is suitable for allowed changes at runtime, without the need for retiring all existing VMs. For bigger changes, heavily baked images is more suitable, once it not only encapsulate changes to the application, but also to the installed packages.
