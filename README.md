This web application is designed for Career Camp employees to manage student data, track interview processes, and generate reports. The interface allows employees to securely sign in, add students, assign them to interviews, track interview results, and download comprehensive reports in CSV format.

FEATURES
1. Employee Authentication:
Sign Up & Sign In: Only employees can sign up and sign in to use the application.

2. Student Management:
Add Students: Add new students with relevant details like name, college, status (placed/not placed), and course scores (DSA, WebD, React).
List Students: View the list of all registered students.

3. Interview Management:
Add Interviews: Create interviews by specifying the company name and interview date.
Assign Students to Interviews: Allocate students to interviews for specific companies.
Manage Interview Results: View all students assigned to an interview and update their result status (Pass, Fail, On Hold, Didn't Attempt).

4. CSV Export:
Generate Report: Download a CSV containing student and interview details, including:
Student ID, Name, College, Status, DSA Final Score, WebD Final Score, React Final Score, Interview Date, Company Name, and Interview Result.

5. External Jobs List:
Fetch Jobs: A page to list real-time job openings for React and Node.js developers in India using open APIs (e.g., GitHub Jobs API).
Minimalistic Design: Display job details with external links for application.

API Handling: API requests for job listings are managed by the Node.js server.