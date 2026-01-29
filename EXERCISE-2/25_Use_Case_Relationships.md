## Use Case Relationships

Use case relationships describe how different use cases of the **Event Management Platform** are related to each other and how they interact to achieve system functionality.

### Relationships Between Use Cases

- The **Login** use case is a prerequisite for accessing all other use cases in the system.
- The **Register for Event** use case depends on the **View Events** use case, as students must view event details before registering.
- The **Volunteer Enrollment** use case extends the **Register for Event** use case by providing additional functionality for volunteering.
- The **Track Attendance** use case depends on the **Register for Event** and **Volunteer Enrollment** use cases to record participation.
- The **View Participation Records** use case depends on **Track Attendance** to display accurate participation history.
- The **Manage Events** use case includes **Create Event**, as event creation is a core part of event management.

### Relationship Types Used

- **Include**: Used when one use case always invokes another (e.g., *Manage Events* includes *Create Event*).
- **Extend**: Used when a use case adds optional behavior to another (e.g., *Volunteer Enrollment* extends *Register for Event*).
- **Dependency**: Used when one use case relies on the completion of another (e.g., *View Participation Records* depends on *Track Attendance*).

These relationships help in understanding system behavior, dependencies, and interaction flow within the **Event Management Platform**.
