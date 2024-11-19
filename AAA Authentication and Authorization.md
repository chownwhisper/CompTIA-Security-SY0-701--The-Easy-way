| **Feature**                | **RBAC (Role-Based Access Control)**       | **ABAC (Attribute-Based Access Control)**  |
|----------------------------|---------------------------------------------|---------------------------------------------|
| **Access Basis**           | Based on pre-defined roles.                | Based on attributes (user, resource, context). |
| **Flexibility**            | Limited; static roles.                     | Highly flexible; supports dynamic policies.   |
| **Scalability**            | Suitable for small to mid-sized systems.   | Better for large, complex organizations.     |
| **Policy Definition**      | Role-permission mappings.                  | Attribute-based policies using rules.        |
| **Example**                | "Managers can view reports."               | "Allow access if User.Department = 'Finance' AND it’s work hours." |
