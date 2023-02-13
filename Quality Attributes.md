Quality Attributes
ID | Quality Attribute | Scenario | Associated Use Case
------------- | ------------- | ------------- | --------------------- | 
QA-1 | Availability | If the system fails during normal operation then log the fault and resume operations in 1 second. | All
QA-2 | Usability | If the user wants to change the system language to Dutch or English during normal operations. They will be able to do so by clicking a button and the system will change language in 3 seconds. | All
QA-3 | Security, Performance | If a student logins into the system, it returns a student profile UI with no downtime. | UC4: Private Login
QA-4 | Security, Performance | A user performs a change in system data during normal operations. It  is possible to know who performed the operation and when it was performed 100% of the time. System data is changed within 24 hours | UC1: Course Registration, UC3: Subscribe to Exams, UC5: Edit Grades, UC6: Schedule an Exam
QA-5 | Interoperability, Performance | A student requests data from the system during normal operations. The system sends the data to the student and continues to operate with no downtime. | UC2: Check Grades For Registered Courses
QA-6 | Modifiability | It is expected that new students, lecturers, and courses will be added to the system in the future. They should be able to be added to the system with minimal changes. | UC2:  Check Grades For Registered Courses, UC1:Course Registration
