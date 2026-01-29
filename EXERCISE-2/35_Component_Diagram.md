## Component Diagram

The component diagram illustrates the high-level components of the **Event Management Platform** and how they interact with each other.

### Components

#### User Interface
- Handles user interactions such as login, event viewing, registration, volunteer enrollment, and dashboard access.
- Provides separate interfaces for students and administrators.

#### Application Logic
- Contains the core business logic of the system.
- Manages event creation and updates, registrations, volunteer management, attendance tracking, and participation records.

#### Database
- Stores user information, event details, registration data, volunteer records, attendance information, and participation history.

### Interaction

- The **User Interface** communicates with the **Application Logic** to process user requests.
- The **Application Logic** interacts with the **Database** to store, update, and retrieve system data.
- Data retrieved from the database is processed by the application logic and presented back to users through the interface.

This component diagram helps in understanding the modular structure, responsibilities, and interactions within the **Event Management Platform**, supporting a clear and maintainable system design.
