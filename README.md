This project is an Android application that allows users to manage student information, including adding, updating, and deleting student records. It demonstrates the use of MVVM architecture, Room database for local data storage, and RecyclerView for displaying a list of students.

Features
Add Student: Users can add new students by entering their name and email.
Update Student: Users can update existing student information.
Delete Student: Users can delete student records.
Clear Input: Users can clear the input fields.

Architecture
The application follows the MVVM (Model-View-ViewModel) architecture pattern.
Model: Student data class represents the student entity, and StudentDatabase is the Room database class.
ViewModel: StudentViewModel handles data operations and communicates with the DAO (Data Access Object).
View: MainActivity handles the UI and user interactions.

Dependencies
Room: For local database management.
ViewModel: For managing UI-related data in a lifecycle-conscious way.
LiveData: For data observation.

How to Use
Add Student: Enter the student's name and email in the input fields and click the "Save" button.
Update Student: Click on a student from the list, update the information, and click the "Update" button.
Delete Student: Click on a student from the list and click the "Delete" button.
Clear Input: Click the "Clear" button to clear the input fields
