# QUIZ-MANAGEMENT-SYSTEM
PROBLEM STATEMENT:

The primary objective of the application is to streamline and enhance the process of quiz management within educational settings. By leveraging modern technology, this application serves as a comprehensive platform that caters to the needs of both educators and students. 
For educators, the application offers a user-friendly interface that enables the seamless upload and management of quiz questions. Teachers can easily create, modify, and organize quizzes, fostering a dynamic and efficient environment for the assessment of students' understanding and knowledge retention.
On the student front, the application provides a centralized hub where quizzes are made available. Students can access and participate in quizzes, thereby contributing to a more engaging and interactive learning experience. The system also allows students to review their performance by generating PDF documents containing quiz solutions.
Furthermore, the application incorporates robust user authentication mechanisms, ensuring secure access for both educators and students. The integration with a Microsoft Access database enhances data storage capabilities, facilitating efficient retrieval and management of quiz-related information.
In essence, the application serves as a multifaceted tool that not only simplifies the quiz creation and management process for educators but also empowers students to actively participate in their learning journey by 
offering them a platform for quiz engagement and self-assessment.

FEATURES:
1. Database Interaction: The code interacts with a Microsoft Access database using the pyodbc library. It includes functions for saving and retrieving questions, user information, and quiz results from the database.

2. GUI Components: The code creates a GUI with a window consisting of various frames and components (labels, entry fields, buttons, radio-buttons etc.) using Tkinter. The consistent color scheme and usage of different font styles enhances the tkinter window

3. Quiz Functionality: Teachers can upload quiz questions, and students can check available quizzes, answer questions, and receive results. The code handles randomization of questions using random module, result calculation, and storage of results in the database.

4. PDF Generation: There is functionality for generating PDF documents for both student and teacher views. This includes generating a solution PDF for students and a compiled result PDF for teachers. The module dominate has been used to generate the PDF file and CSS for styling of the PDF.

5. Security Features: The code includes a security feature for password recovery or change, where users need to answer a security question to update their password.

6. Authentication: Users can log in with a username and password. There is a signup feature for creating new accounts, with an option to specify whether the user is a teacher or a student.

7. Modular Structure: The code is organized into functions, making it modular and easier to maintain. Different functions handle specific tasks, such as quiz creation, result generation, and authentication.

8. HTML to PDF Conversion: The code utilizes the pyhtml2pdf library to convert HTML files to PDF documents, enabling the creation of PDFs for quizzes and results.


