## Use Case Documentation

This document provides detailed descriptions of selected use cases of the **Event Management Platform**.

---

### Use Case 1: Login
**Actor:** Student / Event Organizer / Administrator  

**Description:**  
Allows the user to access the system by logging in based on their role.

**Precondition:**  
User opens the Event Management Platform.

**Postcondition:**  
User is redirected to the respective dashboard based on their role.

**Main Flow:**
1. User opens the application.
2. User selects their role (Student or Administrator).
3. System validates the login credentials.
4. System grants access to the appropriate dashboard.

---

### Use Case 2: View Events
**Actor:** Student  

**Description:**  
Allows the student to view a list of upcoming and ongoing events.

**Precondition:**  
Student is logged in.

**Postcondition:**  
Event details are displayed on the screen.

**Main Flow:**
1. Student selects the *View Events* option.
2. System retrieves event details.
3. System displays the list of events with relevant information.

---

### Use Case 3: Register for Event
**Actor:** Student  

**Description:**  
Allows the student to register for a selected event.

**Precondition:**  
Student is logged in and events are available.

**Postcondition:**  
Student registration is confirmed and saved.

**Main Flow:**
1. Student selects an event.
2. Student clicks on *Register*.
3. System records the registration.
4. System confirms successful registration.

---

### Use Case 4: Volunteer Enrollment
**Actor:** Student  

**Description:**  
Allows the student to enroll as a volunteer for an event.

**Precondition:**  
Student is logged in and registered for the event.

**Postcondition:**  
Volunteer enrollment is recorded.

**Main Flow:**
1. Student selects *Volunteer Enrollment*.
2. Student chooses a volunteer role.
3. System saves the volunteer details.
4. System confirms enrollment.

---

### Use Case 5: Create Event
**Actor:** Event Organizer / Administrator  

**Description:**  
Allows the administrator to create a new event.

**Precondition:**  
Administrator is logged in.

**Postcondition:**  
Event is created and visible to students.

**Main Flow:**
1. Administrator selects *Create Event*.
2. Administrator enters event details (name, date, time, venue).
3. Administrator submits the details.
4. System saves and publishes the event.

---

### Use Case 6: Track Attendance
**Actor:** Event Organizer / Administrator  

**Description:**  
Allows the organizer to record attendance for participants and volunteers.

**Precondition:**  
Event exists and users are registered.

**Postcondition:**  
Attendance records are updated.

**Main Flow:**
1. Organizer selects an event.
2. Organizer marks attendance.
3. System saves attendance records.
4. System updates participation history.

---

These use case descriptions clearly define system behavior, actor interactions, and expected outcomes for the **Event Management Platform**, supporting effective design and implementation.
