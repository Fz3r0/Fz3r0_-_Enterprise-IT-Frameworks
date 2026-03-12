# 🔄 🛠 ☁️ IT Service Managemet (ITSM): `Service Now`

![My Video](https://user-images.githubusercontent.com/94720207/165892585-b830998d-d7c5-43b4-a3ad-f71a07b9077e.gif)

### 🐦 Twitter  : [@fz3r0_OPs](https://twitter.com/Fz3r0_OPs)
### 🐱 Github  : [Fz3r0](https://github.com/fz3r0) 

---
 
#### Keywords: `Service Now` `ITSM` `IT Service Management` `IT Governance` `Service Lifecycle` `Incident Management` `Change Management` `Problem Management` `Release Management` `Configuration Management` `Service Request Management` `Risk Management` `Operational Control` `Process Standardization` `Service Reliability` `Continuous Improvement` `Service Strategy` `Service Operations` `ITIL` `ISO 20000` `Enterprise IT`

---

<br>

# 📄 `Index`

[**🛠 IT Service Managemet (ITSM): `Change Management`**]()
- [Info  Covered]()






# 🔄 🛠 ☁️ IT Service Managemet (ITSM): `Service Now`

> **ServiceNow** is a cloud-based enterprise platform used to manage digital workflows and implement **IT Service Management (ITSM)** processes in a structured, auditable, and scalable way.

## 📘 What Is ServiceNow?

**ServiceNow** is developed by **ServiceNow, Inc.**, a company founded in **2004** by **Fred Luddy**. The platform was originally created to simplify enterprise service workflows and has since expanded into a broad cloud platform for IT, operations, customer service, HR, and business automation. 

From an ITSM perspective, ServiceNow acts as a **system of record** for operational processes such as:

* ⚠️ Incident Management
* 🔁 Change Management
* 🧠 Problem Management
* 📦 Service Request Management
* 🗂 Configuration and asset-related workflows

Its core value is not only ticket creation, but also **workflow control, visibility, traceability, and automation across service operations**. 

### 🧩 Technical Perspective

ServiceNow is a **cloud platform** built around workflow-driven applications and enterprise data models. From a development standpoint, it is strongly associated with **JavaScript-based scripting** through its platform APIs, especially the **Glide API / Glide classes**, while also supporting a strong **low-code / no-code** model for workflow design, app creation, and automation. ([ServiceNow][3])

In practical terms, this means ServiceNow can be used by:

* 👨‍💻 Technical users who script and customize logic
* 🧩 Platform administrators who configure workflows and forms
* 🏢 Operational teams who work mainly through tickets, queues, tasks, and approvals

This combination makes ServiceNow both a **technical platform** and an **operational workspace**. 

## 🎯 Why ServiceNow Matters in ITSM

Within ITSM, ServiceNow provides a centralized place to:

* 📋 Record service activity
* 🔎 Track incidents and requests
* ✅ Route approvals
* 🔁 Manage change workflows
* 🧠 Document root cause investigations
* 📊 Maintain operational visibility and auditability

In other words, **ITSM defines the process**, and **ServiceNow provides the platform used to execute that process in day-to-day operations**.



## 🎫 Main Ticket Types in ServiceNow ITSM

> In ServiceNow, different operational needs are documented through different ticket types.
> Each type triggers a distinct workflow, ownership model, and process objective.

Understanding the difference between these records is essential, because the wrong ticket type can lead to the wrong process.

| Type                          | Purpose                                                                                                                      | Example                                                                                                             | Key Idea                                         |
| ----------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| 🔁 **Change Ticket**          | Manage **planned modifications** to the IT environment through review, approval, scheduling, implementation, and validation. | A network team creates `VLAN 520`, configures an SVI on `Switch A`, and extends it to `Switch B` for a new service. | Planned changes **prevent incidents**.           |
| ⚠️ **Incident Ticket**        | Handle situations where something is **broken, degraded, or unavailable**, with the goal of restoring service quickly.       | A user cannot connect to corporate Wi-Fi or a branch loses connectivity to an internal application.                 | Incidents focus on **restoring service fast**.   |
| 🧠 **Problem Ticket**         | Investigate the **root cause** of recurring or major incidents and implement long-term solutions.                            | Users repeatedly lose access to an application and incidents only restore service temporarily.                      | Problems focus on **root cause analysis (RCA)**. |
| 📦 **Service Request Ticket** | Fulfill a **user request for a service or resource** that is not caused by a failure.                                        | A user requests application access, software installation, or new hardware.                                         | Requests focus on **service delivery**.          |
| 👥 **Case Ticket**            | Manage support interactions with **external customers** within Customer Service Management (CSM).                            | A customer reports errors in a product portal or requests help using a service.                                     | Cases support **external customer issues**.      |



## 🏷 ServiceNow: Common Naming Conventions

> Naming conventions vary by organization, but many ServiceNow environments use recognizable record prefixes to distinguish ticket types quickly.

| Record Type                    | Common Prefix | Example Format                              |
| ------------------------------ | ------------- | ------------------------------------------- |
| Change                         | CHG           | `CHG0011223`                                |
| Incident                       | INC           | `INC0011223`                                |
| Problem                        | PRB           | `PRB0011223`                                |
| Service Request / Request Item | RITM / REQ    | `RITM0011223` / `REQ0011223`                |
| Case                           | CS or CASE    | `CS0011223` or organization-specific format |


# 🚀 Typical Service Request Flow

A simplified **Service Request** flow often looks like this:

- 1️⃣ Request Creation - The request is created through the service catalog or request intake process.

- 2️⃣ Assignment - The ticket is assigned to the appropriate group or owner.

- 3️⃣ Communication - The assigned person confirms details, expectations, and due dates with the requester.

- 4️⃣ Task Delegation - If other teams must participate, supporting tasks are created and routed accordingly.

- 5️⃣ Fulfillment - The requested service or item is delivered.

- 6️⃣ Satisfaction Confirmation - The assigned owner verifies that the requester received what was needed.

- 7️⃣ Closure - The ticket is documented and closed with the relevant notes and resolution details.



# 📚🗂️🎥 Resources

- https://www.servicenow.com/docs/r/security-management/security-incident-response/t_CrtChgOrPrbFromSI.html?contentId=demyLqvOlDUMyCCEyjnScQ
- https://www.servicenow.com/company/leadership/frederic-luddy.html?utm_source=chatgpt.com "Frederic B. Luddy"
- https://www.servicenow.com/platform.html?utm_source=chatgpt.com "ServiceNow AI Platform"
- https://www.servicenow.com/docs/r/yokohama/application-development/r_GlideClassOverview.html?utm_source=chatgpt.com "Glide class overview"
- https://developer.servicenow.com/?utm_source=chatgpt.com "ServiceNow Developers"
  


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




