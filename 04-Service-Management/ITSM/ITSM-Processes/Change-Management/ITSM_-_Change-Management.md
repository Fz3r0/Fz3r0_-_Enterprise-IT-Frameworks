# 🔄 🛠 📊 IT Service Managemet (ITSM): `Change Management`

![My Video](https://user-images.githubusercontent.com/94720207/165892585-b830998d-d7c5-43b4-a3ad-f71a07b9077e.gif)

### 🐦 Twitter  : [@fz3r0_OPs](https://twitter.com/Fz3r0_OPs)
### 🐱 Github  : [Fz3r0](https://github.com/fz3r0) 

---
 
#### Keywords: `ITSM` `IT Service Management` `IT Governance` `Service Lifecycle` `Incident Management` `Change Management` `Problem Management` `Release Management` `Configuration Management` `Service Request Management` `Risk Management` `Operational Control` `Process Standardization` `Service Reliability` `Continuous Improvement` `Service Strategy` `Service Operations` `ITIL` `ISO 20000` `Enterprise IT`

---

<br>

# 📄 `Index`

[**🛠 IT Service Managemet (ITSM): `Change Management`**]()
- [Info  Covered]()



# 🛠 IT Service Managemet (ITSM): `Change Management`

> A structured approach to controlling modifications in enterprise Information Technology (IT) environments in order to reduce risk and increase service reliability.

## 📘 Introduction

Change Management is a core process within **IT Service Management (ITSM)**.

In enterprise Information Technology (IT) environments, change is constant. Infrastructure evolves, applications are updated, configurations are modified, and services are improved.

However, **uncontrolled changes are one of the primary causes of service disruption.**

Change Management exists to ensure that changes are:

* 📋 Properly documented
* 🔍 Risk-assessed
* ✅ Authorized before implementation
* 📅 Scheduled in a controlled manner
* 🔄 Reviewed after execution

When structured correctly, Change Management reduces incidents and increases operational stability.

## 🧩 What Is a Change?

A **Change** is:

- **The addition, modification, or removal of any authorized, planned, or supported service or service component that may affect Information Technology (IT) services.**

_If it can impact availability, performance, security, or reliability, it qualifies as a change._

- 💡 **`IMPORTANT!!!`** :: **Planned and properly controlled changes reduce the number of incidents.**

_Change Management transforms reactive operations into controlled evolution._

## 🎯 What Is Change Management?

**Change Management** is the practice of maximizing the number of successful service and product changes by:

- 🔍 Ensuring risks are properly assessed
- ✅ Authorizing changes before implementation
- 📅 Managing change schedules
- 🤝 Coordinating resources
- ⚠️ Reducing unintended service disruption

_The objective is not to prevent change, it is to enable change safely._

## 🖥 Practical Examples of Changes

Changes vary in urgency and impact. Examples include:

- 🟢 **Standard Change** :: (Pre-authorized, low-risk, repeatable, and does not require approval each time it is executed) : e.g.: Adding a pre-approved Virtual Local Area Network (VLAN) tag to an access interface using a documented procedure 
- 🚦 **Normal Change** :: (Requires risk assessment and formal approval; may be low, medium, or high impact and is not pre-approved) : e.g.: Creating a new VLAN with a Switched Virtual Interface (SVI) and deploying it across multiple switches.
- ⚠️ **Emergency Change** :: (Implemented urgently to resolve a major incident or prevent significant business impact) : e.g.: Reverting a faulty routing configuration to restore service during a production outage.
- ⏱️ **Expedited Change** :: (time-sensitive but not necessarily tied to an active outage; follows an accelerated review process) : e.g.: Deploying a security patch within a shortened approval window due to a vulnerability alert.

The complexity of the task does not define whether it is a change. The potential impact does.

## 🔍 Why Change Management Matters

Uncontrolled changes increase:

* ⚠️ Service outages
* 📉 Business disruption
* 🛡 Security vulnerabilities
* 📊 Compliance risk

Structured Change Management enables:

* 📐 Defined processes
* 🏛 Governance and oversight
* 🤖 Approval workflows
* 👁 Process visibility
* 📊 Reduced incident rates




# 👥 Role Definitions in Change Management

To better understand how roles interact, consider the following example change:

> **Example Change:** Create `VLAN 666` with a Switched Virtual Interface (SVI) on `Switch A` and replicate `VLAN 666` on `Switch B` to enable routing for a new internal service.

This change affects switching, routing, and potentially service availability if misconfigured.

Clearly defined roles:

* 🧭 Reduce ambiguity
* 🚫 Prevent unauthorized implementation
* 🏗 Improve accountability
* 🛡 Strengthen governance
* 📈 Increase change success rate

Strong role definition is a foundational element of mature IT Service Management (ITSM).




## 📝 Change Requester / Initiator

Responsible for submitting the change request and providing key information about the proposed modification.

### Responsibilities:

* 📌 Define scope and objective of the change
* 🧾 Provide business or technical justification
* 🛠 Describe implementation approach
* ⚠️ Identify potential impact

**Example in this scenario:**
The requester is a `Network Engineer` who wants to configure a **new VLAN on XYZ location for a new Wireless SSID**. He submits a change ticket stating the need to create `VLAN 666` with an SVI on `Switch A`, assign an IP address for routing, and replicate `VLAN 666` on `Switch B` to maintain Layer 2 consistency. He is also part of the Network Infraestructure `Technical Team` (but he can't be his own tech approver, even if he is part por the Technical Team).


## 🏢 Technical Approver

Reviews the technical validity of the proposed change.

### Responsibilities:

* 🔎 Validate technical design
* 🔙 Confirm rollback plan
* 🛡 Ensure mitigation steps are defined

**Example in this scenario:**
The Technical Approver verifies that removing `VLAN 666` from both `Switch A` and `Switch B` can be safely executed if the deployment fails. He is also part of the Network Infraestructure `Technical Team`.

## 👨‍💻 Technical Teams / Implementation Teams

Responsible for planning, building, testing, and executing approved changes.

### Responsibilities:

* 🧩 Develop technical implementation plan
* 🧪 Perform system and unit testing
* 🚀 Execute the change in production
* 🔄 Perform post-implementation validation
* 🧠 Conduct root cause analysis if needed

**Example in this scenario:**
The technical team configures `VLAN 666`, creates the SVI on `Switch A`, verifies trunk propagation to `Switch B`, validates routing tables, and confirms end-to-end connectivity. In this example the Network Infraestructure `Technical Team` is composed by 10 Network Engineers, including the requester and the technical approver for this specific change request, but only 1 engineer will push this configuration (in this case, it will be the change requester)



## 🏛 IT Service Owner

Accountable for the service affected by the change.

### Responsibilities:

* 🔎 Assess impact to service performance and availability
* 📊 Prioritize the change request
* ✅ Approve or reject the change
* 🎯 Ensure alignment with service-level objectives

**Example in this scenario:**
The IT Service Owner evaluates whether creating `VLAN 666` and enabling routing on `Switch A` could impact existing services, trunk configurations, or routing policies before approving.


## 💼 Business Owner

Represents business interests and operational impact.

### Responsibilities:

* 📈 Evaluate business risk and impact
* 🗳 Participate in approval decisions
* 🧪 Support User Acceptance Testing (UAT)
* ✔ Validate the change meets business needs

**Example in this scenario:**
The Business Owner confirms that the new service requiring `VLAN 666` is aligned with operational requirements and verifies connectivity after deployment.



## 🎯 Change Manager

Oversees the Change Management process end-to-end.

### Responsibilities:

* 📚 Maintain policies and governance standards
* 🔍 Ensure risk assessment is completed
* 📅 Coordinate approvals and scheduling
* 📏 Monitor compliance with change procedures
* 🧑‍⚖️ Chair Change Advisory Board (CAB) meetings

**Example in this scenario:**
The Change Manager ensures that the configuration of `VLAN 666` on both `Switch A` and `Switch B` includes a rollback plan and is scheduled during an approved maintenance window.



## 📦 Deployment Coordinator (Optional Role)

Coordinates release or deployment activities.

### Responsibilities:

* 📅 Schedule deployment window
* 🛎 Ensure environment readiness
* 🔁 Confirm execution sequence
* 📣 Communicate status updates

**Example in this scenario:**
The Deployment Coordinator confirms that both `Switch A` and `Switch B` are available during the maintenance window and not involved in other concurrent changes.



## 🧑‍⚖️ Change Advisory Board (CAB)

A governance body composed of technical and business representatives.

### Responsibilities:

* 📋 Review higher-risk or major changes
* 🧠 Provide recommendations
* 🗓 Advise on scheduling conflicts
* 👁 Ensure organizational risk visibility

**Example in this scenario:**
If adding `VLAN 666` introduces routing policy updates or impacts multiple network segments, the CAB reviews the change before approval. They can organize a meeting with the requester and implementation teams for better understanding and validation of the change. 





## 📌 Leadership / Local Governance Roles

In some organizations, enterprise-level or regional leaders review:

* 🔴 High-risk changes
* ⚠️ Emergency changes
* ⏱ Expedited changes

**Example in this scenario:**
If `VLAN 666` supports a critical production environment, leadership may require additional oversight before implementation.
















# ⚖️ Risk Assessment in Change Management

> Risk Assessment evaluates the potential exposure of a proposed change before it is approved for implementation. Risk Assessment introduces discipline, transparency, and accountability into the change decision-making process. It ensures that change is not only controlled, but intelligently controlled.

In Change Management, decisions should not be based solely on urgency. They must be supported by structured evaluation of impact and probability.

A mature **IT Service Management (ITSM)** process evaluates risk using three core dimensions:

* 📏 Scale
* 🎲 Likelihood
* 💥 Consequence

Together, these determine the overall risk level of a change.

To illustrate, we will use the same example as last section:

> **Example Change:** Create `VLAN 520` with a Switched Virtual Interface (SVI) on `Switch A` and replicate `VLAN 520` on `Switch B` to support a new internal service.


## 📏 Scale

Scale measures how broadly the change affects the organization.

It evaluates the scope of impact based on the number of users, locations, or business services involved.

### Categories:

* 🏢 **Enterprise** :: The change affects multiple locations, critical shared services, or organization-wide systems.

* 👥 **Group** :: The change impacts several users, a department, or a defined business unit.

* 👤 **Individual** :: The change affects a single service instance, location, or limited user base.

### Example (Our Scenario)

* 👤 **Individual**
  Deploy `VLAN 520` with an SVI only in a single office, for a new local service that is not yet in production, such as onboarding a new server segment or a new security network in that site only.
  Example: Configure `VLAN 520` and its SVI on `Switch A` and replicate it on `Switch B` only for `Site X`.

* 👥 **Group**
  Roll out `VLAN 520` across a defined set of locations within a region, such as 4 offices out of 50, where the same change must be implemented consistently across multiple sites.
  Example: Deploy `VLAN 520` and routing updates across `Site X`, `Site Y`, `Site Z`, and `Site W`.

* 🏢 **Enterprise**
  Introduce a new standard network segment that must exist everywhere, requiring consistent deployment across all branches and data centers.
  Example: Implement `VLAN 520` (or a new enterprise subnet standard) across all sites, including creating SVIs, updating trunks, routing policies, and validation procedures globally.



## 🎲 Likelihood

Likelihood evaluates the probability that the change may fail or cause service disruption.

This dimension considers:

* 🔎 Previous implementation history
* 🧪 Availability of pre-implementation testing
* 🔄 Existence of rollback procedures
* 🧩 Technical complexity
* 📚 Familiarity of the technical team with the change

### Categories:

* 🔴 **Very Likely** :: The change cannot undergo proper testing, has not been implemented before, or introduces unknown behavior.

* 🟠 **Likely** :: The change will be tested, but similar implementations have previously resulted in disruption.

* 🟢 **Unlikely** :: The change follows a validated and repeatable procedure with adequate testing and rollback preparation.

### Example (Our Scenario)

* 🟢 If creating `VLAN 520` and its SVI has been performed many times in similar environments, likelihood may be **Unlikely**.

* 🟠 If modifying trunk configurations between `Switch A` and `Switch B` introduces new routing policies never tested before, likelihood may be **Likely**.

* 🔴 If the change involves untested interactions with production routing tables, likelihood could be considered **Very Likely**.


## 💥 Consequence

Consequence represents the level of business impact that would occur if the change fails, even after executing a rollback plan.

It reflects the highest-priority incident that could result from unsuccessful implementation.

### Categories:

* 🔴 **P1 – Critical Business Interruption** :: Severe outage affecting core production systems, multiple business units, or essential operations.

* 🟠 **P2 – Significant Service Impact** :: Major degradation affecting a department, critical workflow, or large user group.

* 🟡 **P3 – Moderate Operational Impact** :: Limited disruption affecting a group of users or non-core service, with workarounds available.

* 🟢 **P4 – Minor or Isolated Impact** :: Localized issue affecting a single user, lab system, or low-priority service.

### Example (Our Scenario)

- If misconfiguring `VLAN 520` causes routing instability across multiple segments connected through `Switch A`, the consequence may be **P1**.

- If only a department loses access due to improper trunk propagation on `Switch B`, it may be classified as **P2 or P3**.

- If the change impacts only a test workstation connected to `Switch B`, the consequence would likely be **P4**.



## 🧮 Overall Risk Determination

Risk is typically calculated by combining:

**Scale × Likelihood × Consequence**

This structured evaluation allows organizations to:

* 📊 Apply objective risk scoring
* 🛡 Improve approval decisions
* 📅 Schedule high-risk changes carefully
* 👁 Provide visibility to governance bodies

Higher combined scores require increased oversight and potentially additional approvals.

### 📌 Important Considerations

* 🔵 Risk Assessment is typically required for **Normal Changes**.
* ⏱ It may also apply to **Expedited Changes**, depending on urgency and impact.
* 🟢 **Standard Changes** are pre-approved and generally do not require full risk evaluation.
* ⚠️ **Emergency Changes** may undergo risk review retrospectively after implementation.





# 📚🗂️🎥 Resources

- 



  
---

<span align="center"> <p align="center"> ![giphy](https://user-images.githubusercontent.com/94720207/166587250-292d9a9f-e590-4c25-a678-d457e2268e85.gif) </p> </span> 



&nbsp;

<span align="center"> <p align="center"> _I hope this information was useful for someone_ </p> </span> 
<span align="center"> <p align="center"> _and please, don't forget to enjoy your days..._ </p> </span> 
<span align="center"> <p align="center"> _...It is getting dark... so dark..._ </p> </span> 

&nbsp;

<span align="center"> <p align="center"> _In the mist of the night you could see me come, where shadows move and Demons lie..._ </p> </span> 
<span align="center"> <p align="center"> _I am [Fz3r0 💀](https://github.com/Fz3r0/) and the Sun no longer rises..._ </p> </span> 

---






---

> ![hecho en mexico 5](https://user-images.githubusercontent.com/94720207/166068790-fa1f243d-2db9-4810-a6e4-eb3c4ad23700.png)
>
> _- Hecho en México - by [Fz3r0 💀](https://github.com/Fz3r0/)_  
>
> _"In the mist of the night you could see me come, where shadows move and Demons lie..."_ 

