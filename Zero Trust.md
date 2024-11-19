| **Topic**                    | **Detailed Explanation (Using Technical Terms)**                                                                                                           |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Zero Trust**               | - Traditional networks rely on implicit trust once inside the network; Zero Trust eliminates this assumption.                                               |
|                              | - **Zero Trust** is a holistic security approach applied to **every user, every process, and every device**.                                               |
|                              | - Core principles: "Never Trust, Always Verify." Multi-factor authentication (MFA), encryption, advanced firewalls, monitoring, and analytics are critical. |
| **Planes of Operation**      | - Networks are logically separated into **functional planes**:                                                                                              |
|                              |   1. **Data Plane**: Handles actual data processing (frames, packets, network traffic). Functions include **forwarding, encryption, NAT**.                 |
|                              |   2. **Control Plane**: Manages **how the Data Plane operates**. It sets rules and policies for **packet routing, session tables, and NAT tables**.         |
|                              | - Applies to **physical, virtual, and cloud components**.                                                                                                   |
| **Extending Physical Architecture** | - Separate the **data plane** and **control plane** into functional tasks.                                                                             |
|                              | - Incorporate **hardware or software** specifically designed to isolate network management tasks.                                                           |
|                              | - This architecture simplifies implementing Zero Trust by splitting responsibilities.                                                                      |
| **Controlling Trust**        | - **Adaptive Identity**: Analyze multiple factors to authenticate access requests, such as:                                                                 |
|                              |   - Physical location, type of connection, IP address, device identity, or organization-specific relationships.                                            |
|                              | - **Threat Scope Reduction**: Decrease the number of potential entry points by segmenting access requests based on roles or risk levels.                    |
|                              | - **Policy-Driven Access Control**: Combine **adaptive identity** mechanisms with a predefined **set of rules** for granular control.                       |
| **Security Zones**           | - Network traffic is categorized into **broad zones**:                                                                                                    |
|                              |   - **Trusted Zones**: Includes internal systems like IT, HR, and finance networks.                                                                       |
|                              |   - **Untrusted Zones**: Typically external traffic or external networks (e.g., internet).                                                               |
|                              |   - Some zones are implicitly trusted, such as internal-to-internal traffic.                                                                               |
|                              | - By using zones, unwanted access can be denied implicitly (e.g., blocking untrusted-to-trusted access).                                                    |
| **Policy Enforcement Point (PEP)** | - Acts as the **gatekeeper** for all network traffic.                                                                                                  |
|                              | - Evaluates access for **subjects** (users, devices, systems, or applications).                                                                            |
|                              | - Allows, monitors, or terminates connections based on the evaluation.                                                                                     |
|                              | - Can consist of **multiple components working together** to enforce security.                                                                             |
| **Policy Decision Process**  | - **Policy Decision Point (PDP)**: The logical entity that evaluates the access decision based on preconfigured rules.                                      |
|                              | - **Policy Enforcement Point (PEP)**: Implements the access decision made by the PDP (e.g., granting or denying access).                                    |
|                              | - The process relies on a **Policy Engine** and **Policy Administrator** to:                                                                               |
|                              |   - Evaluate access decisions.                                                                                                                            |
|                              |   - Send instructions to the PEP for enforcement.                                                                                                         |
| **Zero Trust Across Planes** | - Zero Trust applies to **all operational planes** in the network:                                                                                        |
|                              |   - **Control Plane**: Enforces access policies.                                                                                                         |
|                              |   - **Data Plane**: Processes packets and follows policies defined in the control plane.                                                                  |
|                              |   - Ensures consistent and secure access across **subjects, systems, and enterprise resources**.                                                          |
