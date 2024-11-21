| **Topic**               | **Key Points**                                                                                     | **Examples**                                                                                              |
|-------------------------|----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| **Technical Change Management** | Structured process for managing system modifications. Plan, assess risks, and update systems safely. | Upgrading server OS or applying security patches.                                                          |
| **Allow List / Deny List**      | Control which programs can run:                                                                 | - **Allow List**: Only approved software (e.g., Microsoft Office, Chrome). <br> - **Deny List**: Block known malicious software (e.g., malware, unapproved apps). |
| **Restricted Activities**       | Enforce permissions for changes to systems. Only authorized personnel can make changes.            | - Allowing only system admins to change network settings or deploy new software.                          |
| **Downtime**                    | Plan maintenance during off-peak hours. Minimize service interruptions.                             | - System downtime scheduled during late hours to install updates or patches. <br> - Switching to backup server to prevent service disruption. |
| **Restarts**                    | System reboots required after updates or configurations. Ensure minimal disruption.                  | - Restarting a server after applying security patches. <br> - Rebooting a database server after a configuration change. |
| **Legacy Applications**         | Older programs no longer actively supported or updated. Can be difficult to maintain.               | - Using legacy accounting software that no longer receives updates from the vendor. <br> - Maintaining an old CRM system no longer supported by its developer. |
| **Dependencies**                | Software or services that rely on each other. Changes in one part of the system may affect others.  | - A web application depends on a database service. If the database is updated, the web application might need adjustments. |
| **Documentation**               | Keep clear and updated records of system setups, configurations, and procedures.                    | - Network architecture diagrams. <br> - Configuration manuals detailing software settings and their impact. |
| **Version Control**             | Track changes to software and configurations over time. Enables rollbacks and collaborative work.    | - Using Git to track code changes in a development project. <br> - Storing configuration files in version control for easy rollback. |