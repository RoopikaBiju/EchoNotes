# EchoNotes

## Basic Details
### Team Name: BitWise

### Team Members
- Member 1: Roopika Biju - Muthoot Institute of Technology and Science
- Member 2: Jenna Sara Babu - Muthoot Institute of Technology and Science

### Hosted Project Link
[mention your project hosted project link here]

### Project Description
EchoNotes is a collaborative journal application that allows two users to create, edit, and share daily notes. It provides a clean, intuitive interface where users can log in, record memories, track edits, and navigate through past notes. Think of it as a shared digital scrapbook where users document their thoughts, experiences, and special moments.

### The Problem statement
In today’s fast-paced world, capturing memories, thoughts, and daily moments is often overlooked. EchoNotes addresses the need for a collaborative, easy-to-use digital journal that encourages people to write, reflect, and share their thoughts with someone they care about.

### The Solution
We’ve created a simple yet effective platform where users can log in, add notes, share them with another user, and track edits over time. No more scrambling to find that one journal entry you were looking for—everything is organized and accessible by date. Plus, the collaborative aspect lets you and a friend or partner create shared memories in real-time.

## Technical Details
### Technologies/Components Used
For Software:
- **Languages used**: 
  - HTML
  - CSS
  - Python

- **Frameworks used**: 
  - Django
    
- **Tools used**: 
  - SQLite (for database management)
  - Git (for version control)
    
## Table of Contents

1. Features
2. Installation
3. Usage
4. Contributing
5. Acknowledgments

###  1. Features

- User Login: Allows users to log in and access their shared scrapbook.
  
- Shared Notes: Users can create, edit, and view notes shared between them for specific dates.

- Edit Tracking: Displays who last edited a note and when, providing transparency and history.

- Date Navigation: Navigate through the notes by date to view past entries.

- Simple UI: A clean, user-friendly interface with basic HTML/CSS, ensuring ease of use.

###  2. Installation
  To set up the project locally, follow these steps:
  
  1. **Clone the repository:**
     ```bash
     git clone https://github.com/RoopikaBiju/EchoNotes
     
  2. **Navigate to the project directory:**
      ```bash
      cd EchoNotes
  
  3. **Install the required dependencies:**
      ```bash
      pip install -r requirements.txt

  4. **Migrate the database:**
        ```bash
        python manage.py migrate
  5. **Start the application:**
      ```bash
      python manage.py runserver
    
###  3. Usage
    - Register: Create a new account to start using the application.
    - Login: Use your credentials to log in.
    - Create Note: Click on "Create New Journal" to add a new note.
    - Edit Note: Click on the "Edit" button next to any note to modify it.
    - Delete Note: Click on the "Delete" button to remove a note.
    - View Notes: Your notes will be displayed in chronological order.
    
###  4. Contributing
    Contributions are welcome! If you would like to contribute to this project, please follow these steps:

    - Fork the repository: Click the "Fork" button at the top right of the repository page on GitHub to create your own copy of the repository.
    - Clone your fork: Use the following command to clone your forked repository to your local machine: 
        git clone https://github.com/RoopikaBiju/EchoNotes.git
    
    - Create a new branch: Before making changes, create a new branch for your feature or bug fix: 
        git checkout -b feature/YourFeature
    
    - Make your changes: Edit the code as needed
    - Commit your changes: After making changes, commit them with a descriptive message: 
        git commit -m "Add some feature"
    
    - Push to your branch: Push your changes to your forked repository: 
        git push origin feature/YourFeature

    - Open a pull request: Go to the original repository on GitHub and click the "New Pull Request" button. Select your branch and submit the pull request.
  Thank you for considering contributing to EchoNotes!

###  5.Acknowledgements
    Thanks to the Django community for their excellent documentation and support.
    Inspiration from various open-source projects that promote collaborative development.

## Screenshots

Here are some screenshots of EchoNotes in action:

1. Login Screen:

    ![image](https://github.com/user-attachments/assets/404e3a56-ed4c-41d0-952f-09e6bacdc1e3)

This is the login screen where users enter their credentials to access their shared scrapbook. Users can sign in to start collaborating and creating notes with others.

2. Register Page:
  ![image](https://github.com/user-attachments/assets/e81937b6-cb34-4dec-83f9-e00e43d777c4)

This is the registration page where new users can create an account. Users enter their details such as username and password to get started with the app. Once registered, they can log in and start collaborating on notes.

3. Dashboard Page
  ![image](https://github.com/user-attachments/assets/3717706e-5c75-4eea-861a-8af641105634)
  ![image](https://github.com/user-attachments/assets/b9d48576-f0a2-4488-a3cf-eaf34d03ffe8)

The dashboard (journal page) displays a list of all notes, with the latest notes appearing first. Users can view, edit, and delete their notes

4. Create Note Page
  ![image](https://github.com/user-attachments/assets/160e6819-b718-4995-8099-1337a07f8ae2)

This is the "Create Note" page where users can add new notes to their journal. The page includes a simple text editor where users can type their thoughts, and a save button to store the note. After saving, the note will appear in the dashboard, sorted by date.

5. Edit Note Page
    **Before Editing (Dashboard):**
    ![image](https://github.com/user-attachments/assets/9e9d59e0-1dbd-4388-87dc-a35138fe74e8)

   **Before Editing (In Edit page):**
    ![image](https://github.com/user-attachments/assets/81282f57-0f2f-4281-8bb8-62fb4f9ea04f)
    
   **After Editing (In Edit Page):**
   ![image](https://github.com/user-attachments/assets/7e405ce5-34da-4b44-aac6-48c6a316f90c)
   
    **After Editing (Dashboard):**
    ![image](https://github.com/user-attachments/assets/bd91bd16-972f-4418-9428-8660b326df09)

The edit page allows users to modify the content of a note. The page also shows the last editor’s name and the date when the note was last updated, providing full edit tracking.

6. Delete a Note Page:
   **Before Deleting Page:**
    ![image](https://github.com/user-attachments/assets/d1389d10-4dc3-4c0c-8763-7c38278caaa1)
    
  **During Deleting Page:**
    ![image](https://github.com/user-attachments/assets/639d702b-db2a-4453-b67c-22be7c3978bf)

  **After Deleting Page:**
    ![image](https://github.com/user-attachments/assets/3f66953d-8ecb-441d-8371-ea9b981f4299)

The Delete Page in an app or website is typically used to remove or permanently delete a specific page or data from the system

### Project Demo
# Video
https://www.loom.com/share/1146067388c242d8bdd372461577e949?sid=0fadf081-cb82-466f-813c-caf8e00196f5

I created a new user named der, then logged in with that ID using its password. I created a new note for jenn and later created another new note for the user ultramadness, which was then edited. Finally, I logged out from the user der.

Now, I logged in as the user jenn. User jenn edited the note sent by der and deleted the note sent by the user sen.

## Team Contributions

    - Roopika Biju: Led the project development and implemented the backend logic using Django.
    - Jenna Sara Babu: Designed the frontend interface and contributed to the user experience design.

