## Class Relationships

Class relationships describe how different classes in the **Event Management Platform** are connected to each other and interact within the system.

### Identified Relationships

- A **User** can create or participate in multiple **Events**.
- An **Event** can have multiple **Registrations** from different users.
- A **User** can have multiple **Registrations**, but each registration is associated with one event.
- A **User** can enroll as a **Volunteer** for an event.
- Each **Volunteer** record is linked to one **User** and one **Event**.
- An **Event** can have multiple **Attendance** records.
- The **Dashboard** class aggregates data from **Event**, **Registration**, **Volunteer**, and **Attendance** classes to display summaries and participation details.

### Relationship Types

- **Association:**  
  Between *User* and *Event*, and between *User* and *Registration*.

- **Aggregation:**  
  Between *Dashboard* and *Event / Registration / Attendance*, as the dashboard displays summarized data without owning it.

- **Dependency:**  
  Between *Dashboard* and *Attendance*, as dashboard views rely on attendance data to show participation status.

These relationships help in understanding the structure, dependencies, and interactions between system components in the **Event Management Platform**.
