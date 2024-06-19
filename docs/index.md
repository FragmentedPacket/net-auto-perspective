# A Perspective of Network Automation

These are all my own opinions and only offer a perspective from my experience working in and along many different organizations. I will try and cover many topics related to network automation and I hope to be able to convey the **why**, **what**, **how** and **who** of network automation.

I think the first question we need to ask is **why**?

## Reasons WHY

If we take a look at some of the reasons **why** an organization may want to adopt network automation.

- **Enhancing Operational Efficiency** to optimize engineer time to be able to increase business value delivered without increasing the head count linearly.
- **Cost Reduction and Resource Optimization** to reduce the operating and capital costs associated with managing the network.
- **Enhancing Security and Compliance** is critical in today's security landscape and in some industries it is a mandate to retain configuration drift for auditing purposes.

There are a lot more reasons **why** an organization may want to adopt network automation, but I think we need to ask ourselves **why** we (network engineers) may want to adopt network automation.

- **Provide self-service for the network** to provide simple interfaces for users to consume the network that helps **enhance operational efficiency** AND allows you to get away from constantly logging into devices and provisioning a new VLAN that was needed by the server team yesterday, but they just told you today.
- **Manage the network as code** to be able to write tests for network changes, configuration rendering and remediation, etc. to **enhance security and compliance** AND allows you to automate your documentation of the implementation and rollback tasks before that pesky CAB meeting that nobody listens to anyways.
- **Telemetry to enable robust alerting and reporting** to allow business units to retrieve valuable network data to make data driven business decisions such as **cost reduction or resource optimization** AND allows you to manage the data collection rather than the business logic or color scheme of the report.

I hope these points help tie together that we can both deliver business value that matches our organization's goals and benefit from this shift in **how** we work when we adopt network automation.

## Network Automation Strategies

There are many strategies when it comes to network automation adoption, but at this point in time, I think there are three overarching strategies. These strategies will typically follow the organizational structure, but sometimes an organizational structure may need to change depending on the strategy that is chosen.

- **Centralized**
- **Decentralized**
- **Hybrid**

Overall, each organization needs to determine what benefits they stand to gain from each strategy, but realize that picking a strategy boils down to what each group of engineers are expected to deliver as business value and stay as closely aligned to each groups core competency.

## Network Automation Platform

The platform is a critical component in accelerating automation adoption. The requirements need to be clear as to why the platform should exist, what the business problems the platform will be solving, and how users (**who**) will be utilizing the platform. In the majority of context, we want to make the platform is consumable and simplifies creating automation for network engineers.

The platform should be the foundation and be treated as a product. The platform is typically a bunch of different components(tools) that are integrated together. A few of the benefits of treating the platform as a product.

- The platform will evolve naturally by implementing bug fixes and new features that are raised by users of the platform.
- As the platform matures and new teams are on-boarded to it, they gain the benefits of the features and bug fixes that came before them.
- It allows the users to remain users and focus on their core competency.
- Allows for standardized implementations of common use cases.
- Tailored training for how users can consume the platform and increase speed of adoption.
