****Automated Facial Recognition Class Attendance System****
The Automated Facial Recognition Class Attendance System is a solution designed to streamline the attendance-taking process in classrooms. By leveraging RFID technology and facial recognition, this system automates the attendance tracking process, saving time and effort for both teachers and students.

****Features****
Automated authentication using RFID cards for teachers
Facial recognition for identifying students in the classroom
Real-time attendance tracking
Integration with CCTV cameras for capturing classroom footage
Storage of attendance records in Firebase database
Notification system for teachers, web app, and parents
Seamless operation during lectures with periodic attendance updates
Installation
To install the Automated Facial Recognition Class Attendance System, follow these steps:



Configure RFID reader device and CCTV camera connections.

Set up Firebase database for storing attendance records.

Update configuration files with necessary credentials and settings.

**Usage**
To use the Automated Facial Recognition Class Attendance System:


1-Teachers tap their RFID cards on the device to authenticate.
2-The system connects to the CCTV camera and performs facial recognition to mark attendance.
3-Attendance records are stored in the Firebase database.
4-Notifications are sent to the web app and parents regarding attendance updates.
5-the system utilizes multiple fallcase backups to improve the sccuracy of the system



**DEPENDENCIES****** 

opencv-python==4.5.4.60
dlib
cvzone
face-recognition 
mfrc522()
adafruit
spidev
RPI.GPIO
numpy
datetime
uagents
poetry
