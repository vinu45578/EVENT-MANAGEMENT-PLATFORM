## Class Attributes and Methods

This document describes the attributes and methods of the identified classes in the **Event Management Platform**.

---

### Class: User
Represents a user of the system such as a Student, Event Organizer, or Administrator.

**Attributes:**
- userId  
- name  
- role  
- email  

**Methods:**
- login()  
- logout()  
- viewDashboard()  

---

### Class: Event
Represents an event created in the system.

**Attributes:**
- eventId  
- eventName  
- date  
- time  
- venue  
- description  

**Methods:**
- createEvent()  
- updateEvent()  
- deleteEvent()  
- getEventDetails()  

---

### Class: Registration
Represents event registration details for a student.

**Attributes:**
- registrationId  
- userId  
- eventId  
- registrationStatus  

**Methods:**
- registerEvent()  
- cancelRegistration()  
- getRegistrationDetails()  

---

### Class: Volunteer
Represents volunteer enrollment information.

**Attributes:**
- volunteerId  
- userId  
- eventId  
- roleAssigned  

**Methods:**
- enrollVolunteer()  
- updateVolunteerRole()  
- getVolunteerDetails()  

---

### Class: Attendance
Represents attendance records for events.

**Attributes:**
- attendanceId  
- userId  
- eventId  
- attendanceStatus  

**Methods:**
- markAttendance()  
- updateAttendance()  
- getAttendanceStatus()  

---

### Class: Dashboard
Represents the main interface displaying event-related information.

**Attributes:**
- totalEvents  
- registeredEvents  
- volunteeredEvents  

**Methods:**
- viewEvents()  
- viewParticipationHistory()  
- displaySummary()  

---

Identifying class attributes and methods helps in defining responsibilities of each class and supports clear object-oriented design for the **Event Management Platform**.
