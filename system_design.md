# System Design: From Business Requirements to Scalable Solutions

To build a system, you need to translate business requirements into designs that can be implemented. System design is the determinant of whether a system will effectively address its business needs while remaining efficient, maintainable, and scalable.

A new paradigm shift in system design is the idea of **security by default**. Security should be considered from the very beginning, not added as an afterthought.

---

## High-Level Design vs Low-Level Design

System design can be broadly subdivided into **High-Level Design (HLD)** and **Low-Level Design (LLD)**.

### High-Level Design (HLD)

High-Level Design focuses on translating business requirements into major subcomponents that make up the system. At this stage, the concern is **how these components interact** to get the work done, rather than their internal details.

This provides a bird’s-eye view of the system. Examples include:

- Databases
- Load balancers
- API gateways
- Core services and integrations

### Low-Level Design (LLD)

Low-Level Design dives into the details of the system. It explains how each part works within a subcomponent and how it interacts with components outside that subcomponent.

This includes:

- Database schemas and internal structures (derived from the high-level database design)
- API definitions and interfaces
- Class designs, workflows, and data flow

---

## Steps to Get Started with System Design

A structured approach to system design typically involves the following steps:

1. Understand the requirements
2. Define the system architecture
3. Choose the technology stack
4. Design the modules
5. Plan for scalability
6. Consider security and privacy
7. Test and validate

---

## Key Factors That Should Guide Your System Design

When designing a system, the following considerations are critical:

- **Scalability:** How will the system handle spikes in demand or continuous growth?
- **Performance:** Minimize latency and improve response time.
- **Reliability:** How will the system handle failures or attacks such as DDoS?
- **Security:** Security should be built in by default, not bolted on later.
- **Maintainability:** Well-organized code and clear documentation enable
  efficient collaboration and long-term improvement. A poorly documented
  codebase is bad even for its original author; it is a time bomb.
- **Interoperability:** The system should seamlessly interact with other services defined in the business requirements.
- **Usability:** The system should be user-friendly and easy to use.
- **Cost-effectiveness:** The system should be designed to minimize development and operational costs while still meeting all requirements.
