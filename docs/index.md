# A Perspective of Network Automation

These are all my own opinions and only offer a perspective from my experience working in and along many different organizations. I will try and cover many topics related to network automation and I hope to be able to convey the why, what, how and who of network automation.

I think the first question we need to ask is **why**?

## Reasons WHY

If we take a look at some of the reasons **why** an organization may want to adopt network automation:

- **Enhancing Operational Efficiency** to optimize engineer time to be able to increase business value delivered without increasing the head count linearly.
- **Cost Reduction and Resource Optimization** to reduce the operating and capital costs associated with managing the network.
- **Enhancing Security and Compliance** is critical in today's security landscape and in some industries it is a mandate to retain configuration drift for auditing purposes.

There are a lot more reasons **why** an organization may want to adopt network automation, but I think we need to ask ourselves **why** we may want to adopt network automation.

- **Provide self-service for the network** to provide simple interfaces for users to consume the network that helps **enhance operational efficiency** AND allows you to get away from constantly logging into devices and provisioning a new VLAN.
- **Manage the network as code** to be able to write tests for network changes, configuration rendering and remediation, etc. to **enhance security and compliance** AND reduces the amount of times you will have to diff two different snapshots to get an answer to your boss ASAP.
- **Telemetry to enable robust alerting and reporting** to allow business units to retrieve valuable network data to make data driven business decisions such as **cost reduction or resource optimization** AND allows you to manage the data collection rather than the reporting and business logic.

## Network Automation Strategies

There are many strategies when it comes to network automation adoption, but at this point in time, I think there are three overarching strategies. These strategies will typically follow the organizational structure, but sometimes an organizational structure may need to change depending on the strategy that is chosen.

- **Centralized**
- **Decentralized**
- **Hybrid**

## Network Automation Platform

The platform is a critical component in the decision making process. The requirements need to be clear as to why the platform should exist and what the business problems the platform will be solving, and how users (who) will be able to utilize the platform. In the majority of context, we want to make the platform consumable and easy to use by network engineers.
