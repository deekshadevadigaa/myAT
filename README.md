Introduction : 
- The Android Attendance Monitoring System is a mobile application designed to simplify and automate the attendance tracking process in educational institutions. Leveraging Android devices, this app offers a user-friendly interface that allows both administrators and faculty members to efficiently manage and monitor student attendance.

Purpose :
- The project was undertaken to address the limitations of traditional, manual attendance systems used in educational institutions. Manual methods are often labor-intensive, error-prone, and lack real-time capabilities. This application provides a digital solution that streamlines attendance recording, improves accuracy, and enables real-time monitoring and reporting.

Key Features  
- Real-time Attendance Tracking: Capture and update attendance records instantly using Android devices.
- User Authentication: Secure login for faculty and administrators to ensure data integrity and access control.
- Attendance Records Viewing: View detailed attendance records by date, subject, and student.
- Automated Notifications: Send notifications to students and faculty about attendance-related updates.
- Data Analysis: Generate insights and reports to assist administrators in monitoring and managing attendance trends.

Flowchart : 
- ![Flowchart](C:\Users\DEEKSHA\OneDrive\Desktop\myAT_flowchart)

Working :

Teachers can mark attendance by selecting the section they want to take attendance for. Our 
proposed system is divided into four distinct modules described as follows:  
1. User authentication : Initially, when the teacher runs the application for the first time, a login 
screen will be displayed that will prompt the teacher to enter the username and password required 
for authentication. The teacher will be provided with a unique username which would be a 
combination of alphanumeric characters. Only when the teacher enters the correct username and 
password, a “success” message will be displayed and the teacher will get authenticated and directed 
to the next screen.   
2. Attendance Procedure: In this module, the teacher will need to select details such as the name of 
the subject for which the lecture is being taken, date of lecture and the particular year for which 
the lecture is conducted. After doing so, the teacher needs to call the web service by clicking a 
button provided on the screen. The web service thus invoked would return the list of names of all 
the students belonging to a particular semester and branch as per the input provided.  
3. Marking Attendance: After the list of students has been displayed the teacher needs to begin the 
process of marking the attendance of students. For this purpose, our application would be providing 
checkboxes against each student’s name that will allow the teacher to mark the student either 
present or absent. Accordingly, the details of the student will be sent to the remote database and 
the attendance will be marked for that particular day.   
4. Display information of student : Once the attendance has been marked successfully, the teacher 
can anytime check the attendance record of a particular student. The information thus displayed 
would include the attendance of the student for each subject, the date of class taken and the 
attendance status, attendance details of all days the classes were taken. 
  
Technologies Used :
- Development Environment: Android Studio
- Programming Language: Java
- Database Management: SQLite (Chosen for its simplicity and portability within the Android ecosystem)

Conclusion :
- The Android Attendance Monitoring System successfully provides a modern solution for managing attendance in educational institutions. It effectively addresses the challenges of traditional methods and offers significant improvements in efficiency and accuracy. Future enhancements could include integrating biometric authentication for added security and expanding reporting capabilities to provide more detailed analytics.

