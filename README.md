## Purpose

The purpose of this database is to provide a structured solution for record-keeping and work tracking within construction projects. It is tailored for civil engineers and building technologists who often face challenges in managing large volumes of project data across multiple domains such as land acquisition, design planning, procurement, labor, and service management. By integrating these aspects into a single relational database, the system enhances transparency, accountability, and efficiency throughout the project lifecycle.

**Scope**

This database covers the essential components of a building project, from initial land acquisition to design, procurement of materials, engagement of skilled trades, utilities, and finishing works. It ensures that all records are traceable to the client and project, allowing stakeholders to monitor budgets, timelines, and resources with greater accuracy. The database also supports decision-making by consolidating diverse project data into an organized structure.

## Entity Descriptions

**Client:** Central entity capturing project details, including client name, project title, location, start and end dates, budget, and status. Acts as the parent reference for all other entities.

**Land and Acquisition:** Tracks land procurement processes by recording agencies, roles, required documents, and estimated costs. Ensures compliance and proper documentation during acquisition stages.

**Design Planning:** Documents design-related activities, including planning items, responsible professionals, deliverables, and cost estimates. Supports strategic project planning and ensures alignment with client expectations.

**Procurement of Building Materials:** Manages materials needed for construction. Stores data on categories, specifications, suppliers, quantities, and unit costs to improve procurement accuracy and supplier tracking.

**Skilled Trades:** Records details of labor teams, including roles, lead persons, daily rates, team size, and start dates. Enables efficient workforce scheduling and cost control.

**Utilities and Services:** Handles essential services required during or after construction, such as providers, categories, CAPEX, and OPEX. Ensures operational readiness and service accountability.

**Finishing and Aesthetic Works:** Connects design plans with specific finishing activities, covering work items, descriptions, quantities, rates, and amounts. Ensures quality control and cost tracking during the final project stages.

## Relationships 

<img width="932" height="841" alt="Screenshot 2025-08-27 145140" src="https://github.com/user-attachments/assets/0a58b9f6-82df-44f4-8078-204e7069a38b" />

- Each **client** can have multiple design plans, land acquisitions, material procurements, skilled trades, finishing works, and service requirements.

- **Design planning** links directly with both **finishing works** and **utilities**, ensuring consistency between planned designs and implemented services.

- **Procurement** and **skilled trades** relate back to the client, allowing tracking of both resource and workforce allocations under the same project.

**Benefits**

- Provides a **centralized repository** for construction project data.

- Improves **record accuracy** by linking all activities to client and project details.

- Enhances **work tracking** by monitoring tasks, timelines and costs at every project stage.

- Facilitates **decision-making** through structured and accessible data.

- Supports **accountability** among engineers, technologists and contractors.


