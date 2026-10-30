# UniServe – University Services Management System
## User Stories Document

**Project Name:** UniServe  
**Project Type:** University Services Management System  
**Document:** User Stories  
**Version:** 1.0

---

## 1. Project Overview

UniServe is a web-based platform designed to simplify university services by allowing students to submit service requests, track their progress, and communicate with the responsible departments.

The system also provides staff members with tools to manage assigned requests and administrators with full control over users, services, and requests.

## 2. User Roles

The system has three main user roles:

1. **Student:** Can browse services, submit requests, and track personal requests.
2. **Staff:** Can view assigned requests, update their status, and communicate with students.
3. **Admin:** Can manage users, services, staff assignments, and all requests.

---

## 3. Student User Stories

### US-01: Student Registration
As a Student,  
I want to create an account using my personal and university information,  
So that I can access the university services platform.

**Acceptance Criteria:**
- The student can enter their name, university email, student ID, and password.
- The system validates the submitted information.
- The system prevents duplicate accounts.
- The password is stored securely.

### US-02: Student Login
As a Student,  
I want to log in using my email and password,  
So that I can access my personal dashboard.

**Acceptance Criteria:**
- The student can log in with valid credentials.
- Invalid credentials are rejected.
- The system creates an authenticated session.
- Students cannot access admin or staff pages.

### US-03: View Available Services
As a Student,  
I want to browse all available university services,  
So that I can find the service I need.

**Acceptance Criteria:**
- The system displays available services.
- Each service has a name and description.
- Inactive services are not available for new requests.

### US-04: Submit a Service Request
As a Student,  
I want to submit a request by selecting a service and providing the required details,  
So that the responsible department can process my request.

**Acceptance Criteria:**
- The student can select an available service.
- The student can enter a request title and description.
- The system validates required fields.
- The system generates a unique request number.
- The request is created with Pending status.

### US-05: View My Requests
As a Student,  
I want to view all requests I have submitted,  
So that I can keep track of my service history.

**Acceptance Criteria:**
- The student can view their own requests.
- Each request displays its ID, service, submission date, and status.
- Students cannot view other students' private requests.

### US-06: Track Request Status
As a Student,  
I want to view the current status and update history of my request,  
So that I know how my request is progressing.

**Acceptance Criteria:**
- The system displays the current request status.
- The system displays previous status updates.
- The student can view comments related to their request.

### US-07: Receive Notifications
As a Student,  
I want to receive notifications when my request status changes,  
So that I stay informed about its progress.

**Acceptance Criteria:**
- A notification is generated when the request status changes.
- The student can view their notifications.
- The system indicates whether a notification has been read.

---

## 4. Staff User Stories

### US-08: View Assigned Requests
As a Staff Member,  
I want to view requests assigned to me,  
So that I can manage the tasks I am responsible for.

**Acceptance Criteria:**
- Staff members can view their assigned requests.
- Each request displays its details and current status.
- Staff members cannot access requests outside their authorized scope.

### US-09: Update Request Status
As a Staff Member,  
I want to update the status of an assigned request,  
So that students can follow the progress of their requests.

**Acceptance Criteria:**
- Staff members can update authorized requests.
- Available statuses include In Progress, Completed, and Rejected.
- The system records every status change.
- The student can see the updated status.

### US-10: Add Request Comments
As a Staff Member,  
I want to add comments to a request,  
So that I can communicate updates or required information to the student.

**Acceptance Criteria:**
- Staff members can add comments to assigned requests.
- Comments are saved with the author's information and date.
- Authorized students can view relevant comments.

---

## 5. Admin User Stories

### US-11: View Admin Dashboard
As an Admin,  
I want to view an overview of users and service requests,  
So that I can monitor the overall system activity.

**Acceptance Criteria:**
- The dashboard displays total users and requests.
- The dashboard displays Pending, In Progress, and Completed requests.
- The dashboard displays request statistics.

### US-12: Manage University Services
As an Admin,  
I want to add, edit, and deactivate university services,  
So that I can keep the available services updated.

**Acceptance Criteria:**
- The admin can create a new service.
- The admin can edit service information.
- The admin can activate or deactivate a service.
- Only authorized admins can manage services.

### US-13: Manage Service Requests
As an Admin,  
I want to view and manage all submitted requests,  
So that I can supervise the service process.

**Acceptance Criteria:**
- The admin can view all requests.
- The admin can search and filter requests.
- The admin can view request details.
- The admin can monitor request status.

### US-14: Assign Requests to Staff
As an Admin,  
I want to assign requests to the appropriate staff members,  
So that each request is handled by the responsible department.

**Acceptance Criteria:**
- The admin can select a staff member.
- The system saves the assigned staff member.
- The assigned staff member can see the request.
- The student can see relevant assignment updates if enabled.

### US-15: Manage Users
As an Admin,  
I want to view and manage student and staff accounts,  
So that I can maintain proper control over system access.

**Acceptance Criteria:**
- The admin can view registered users.
- The admin can view user roles.
- The admin can activate or deactivate accounts.
- Role changes are restricted to authorized admins.

---

## 6. General System User Stories

### US-16: Secure Logout
As a User,  
I want to log out of my account securely,  
So that my account cannot be accessed by another person using my session.

**Acceptance Criteria:**
- The system provides a logout option.
- The current session is invalidated after logout.
- Protected pages require authentication.

### US-17: Role-Based Access Control
As a System Administrator,  
I want the system to enforce permissions based on user roles,  
So that each user can access only the features they are authorized to use.

**Acceptance Criteria:**
- Students can access student features only.
- Staff members can access authorized staff features.
- Admins can access administrative features.
- Unauthorized access attempts are denied on the server side.

---

## 7. Request Status Definitions

| Status | Description |
|---|---|
| Pending | The request has been submitted and is awaiting review. |
| In Progress | The responsible staff member is working on the request. |
| Completed | The requested service has been completed. |
| Rejected | The request has been rejected with a reason. |

## 8. Project Scope – Version 1.0

The first version of UniServe will focus on:

- Student registration and authentication.
- Displaying available university services.
- Creating and tracking service requests.
- Staff request management.
- Admin dashboard.
- Service and user management.
- Role-based access control.

Advanced features such as online payments, appointment scheduling, and integration with official university systems are outside the scope of Version 1.0.

---

**End of Document**  
**UniServe – University Services Management System**