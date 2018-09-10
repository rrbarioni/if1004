# HW12
## Forward and backward compatibility
### Forward and backward compatibility allows for independent upgrade for services under your control. Not all services will be under your control. In particular, third-party services, libraries, or legacy services may not be backward compatible. In this case, there are several techniques you can use, although none of them are foolproof.
- Discovery
- Exploration
- Portability layer
### How do they work? What is the differences among them? And the similarities?

Discovery: Requires the client to be aware of the version of the service being required; clients can request to be connected to a particular version of the service, while satisfying a set of constraints;

Exploration: Use introspection on the third-party system, in order the client to determine the version of the service, once Discovery assumes that a service registers with a registry;

Portability Layer: Provides a single interface for translating the variety of interfaces from similar systems.

## Rolling back strategies
### Research and discuss your understanding of the following rolling back strategies:
- Not using feature toggles
- Using feature toggles

Feature toggles are a technique in sofware development, in order to maintain and manage multiple changes (feature branches)in code, so that new features can be tested without being ready for release. You can use feature toggles when you want to keep a close distance between the production code and the development version. It is important to not used feature toggles for enabling code that is not complete and ready for deployment.

## Deployment approaches
### Search for some tools/solutions for the following deployment approaches:
- heavily baked
- lightly baked

Heavily baked images: Chef

Lightly Baked images: Docker
