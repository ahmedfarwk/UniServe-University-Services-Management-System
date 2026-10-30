UniServe – University Services Management System

Requirements Specification

Project Name: UniServe
Full Name: University Services Management System
Document Type: Functional and Non-Functional Requirements
Version: 1.0



1. Introduction

1.1 Purpose

UniServe is a University Services Management System designed to provide a centralized platform where students can submit university service requests and track their status.

The system organizes university services into four main categories: Student Affairs Services, Technical Support Services, Maintenance Services, and Complaints and Suggestions.

1.2 Scope

The system covers the submission, management, processing, and tracking of university service requests.

The four main service categories are:

1. Student Affairs Services

- Enrollment certificate requests.
- Academic transcript requests.
- Replacement student ID card requests.
- Student personal information update requests.

2. Technical Support Services

- Laboratory technical problem reports.
- Internet connectivity problem reports.
- University account problem reports.
- Technical assistance requests.

3. Maintenance Services

- Classroom problem reports.
- Lighting problem reports.
- Air-conditioning problem reports.
- Other university facility maintenance requests.

4. Complaints and Suggestions

- Complaints about university services.
- Suggestions for service improvements.
- Reports of general problems.

1.3 Stakeholders

The main stakeholders of UniServe are:

1. Students.
2. Student Affairs Employees.
3. IT Support Staff.
4. Maintenance Staff.
5. Complaints and Suggestions Officers.
6. System Administrators.
7. University Management.



2. User Requirements

User requirements describe the services and quality expectations of the system's users.

2.1 User Functional Requirements

UFR-01: The system shall allow students to submit enrollment certificate requests.

UFR-02: The system shall allow students to request academic transcripts.

UFR-03: The system shall allow students to request replacement student ID cards.

UFR-04: The system shall allow students to request updates to their personal information.

UFR-05: The system shall allow users to report technical problems related to laboratories, internet connectivity, and university accounts.

UFR-06: The system shall allow users to request technical assistance.

UFR-07: The system shall allow users to report maintenance problems related to classrooms, lighting, air conditioning, and other university facilities.

UFR-08: The system shall allow users to submit complaints, suggestions, and general problem reports.

UFR-09: The system shall allow users to track the status of their submitted requests.

UFR-10: The system shall allow users to view updates related to their requests.

2.2 User Non-Functional Requirements

UNFR-01: The system shall provide a simple and user-friendly interface.

UNFR-02: The system shall provide clear instructions for submitting service requests.

UNFR-03: The system shall display request statuses in an understandable format.

UNFR-04: The system shall display a confirmation message when a request is submitted successfully.

UNFR-05: The system should be usable on commonly used desktop and mobile web browsers.



3. System Requirements

System requirements describe the functions and technical characteristics that the software must provide.

3.1 System Functional Requirements

SFR-01: The system shall authenticate users before granting access to protected functions.

SFR-02: The system shall assign a unique identification number to each submitted request.

SFR-03: The system shall classify requests into the four defined service categories.

SFR-04: The system shall store each request and its associated information in a database.

SFR-05: The system shall route each request to the appropriate department according to its category.

SFR-06: The system shall allow authorized employees to view and process requests assigned to their departments.

SFR-07: The system shall allow authorized employees to update request statuses.
SFR-08: The system shall maintain a history of request status changes.

SFR-09: The system shall notify users when important changes occur in their request statuses, if notifications are enabled.

SFR-10: The system shall restrict administrative functions according to assigned roles and permissions.

3.2 System Non-Functional Requirements

SNFR-01: The system shall protect stored information against unauthorized access.

SNFR-02: The system shall encrypt sensitive information during transmission over the network.

SNFR-03: Under the agreed normal operating load, the system should respond to standard user operations within two seconds.

SNFR-04: The system shall maintain data consistency when requests are created or updated.

SNFR-05: The system shall support simultaneous access by multiple users without losing or corrupting request data.

SNFR-06: The system shall support regular database backups and data recovery.

SNFR-07: The system shall be structured to support maintenance and future software updates.



4. Business Requirements

Business requirements describe the university's goals and the business processes that UniServe is intended to support.

4.1 Business Functional Requirements

BFR-01: The system shall provide a centralized platform for managing the four university service categories.

BFR-02: The system shall support the university's process for receiving and processing Student Affairs requests.

BFR-03: The system shall support assigning technical support requests to responsible IT staff.

BFR-04: The system shall support assigning maintenance requests to responsible maintenance staff.

BFR-05: The system shall provide a process for receiving and reviewing complaints and suggestions.

BFR-06: The system shall allow authorized management personnel to generate reports about submitted requests and their statuses.

BFR-07: The system shall support monitoring service requests to help the university improve service management.

4.2 Business Non-Functional Requirements

BNFR-01: The system should reduce the administrative effort required to manage university service requests.

BNFR-02: The system shall support consistent handling of requests across the four service categories.

BNFR-03: The system shall provide accurate reports to support management decisions.

BNFR-04: The system should be scalable to accommodate growth in the number of users and requests.

BNFR-05: The system should support continuity of service management through appropriate backup and recovery procedures.



5. Domain Requirements

Domain requirements arise from the rules and procedures of the university services domain.

The following requirements should be checked against the university's actual policies before final approval.

5.1 Domain Functional Requirements

DFR-01: Enrollment certificate requests shall be processed according to approved student enrollment records and university procedures.

DFR-02: Academic transcript requests shall be handled using official academic records and applicable university procedures.

DFR-03: Replacement student ID card requests shall follow the university's approved card replacement procedure.

DFR-04: Student information update requests shall follow the university's approved identity verification and data correction procedures.

DFR-05: Technical support requests shall be categorized according to the type of reported technical issue.

DFR-06: Maintenance requests shall identify the affected university facility or equipment whenever applicable.

DFR-07: Complaints and suggestions shall be forwarded to the appropriate university authority for review.

DFR-08: Requests shall be processed by authorized personnel according to their assigned responsibilities and applicable university procedures.

5.2 Domain Non-Functional Requirements

DNFR-01: The system shall comply with applicable university policies governing student records and personal information.

DNFR-02: The system shall maintain the accuracy and integrity of academic and student service records.
DNFR-03: Access to confidential academic records shall be restricted to authorized users.

DNFR-04: The system shall retain request records according to the university's approved record-retention policy.

DNFR-05: The system shall handle personal information in accordance with applicable data-protection requirements.

DNFR-06: The system shall support traceability of request processing to facilitate administrative review and accountability.



6. Assumptions and Items to Confirm

The following points should be confirmed by the project team before the requirements are finalized:

1. Whether all users must log in and which account types are supported.
2. Whether notifications will be implemented and how they will be delivered.
3. Which request statuses will be used, such as Submitted, Under Review, In Progress, Completed, or Rejected.
4. Whether management reports are included in the project scope.
5. The required performance target and expected number of simultaneous users.
6. The university's actual procedures for academic records, replacement ID cards, personal information updates, and record retention.



7. Conclusion

UniServe aims to centralize university service requests, improve request tracking, and support the departments responsible for Student Affairs, Technical Support, Maintenance, and Complaints and Suggestions.

These requirements provide an initial basis for system design and testing. They should be reviewed by the project team and relevant university stakeholders before implementation.