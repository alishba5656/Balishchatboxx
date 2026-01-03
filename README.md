Project Title: Balish Chat Box
Course: Mobile Application Development
Program: BSCS / BSSE – Semester 5
________________________________________
1) List of Ten Features / Functional Requirements
(Balish Chat Box – Chat Application)
The Balish Chat Box is an Android-based chat application that allows users to communicate through text messages while maintaining application state across various Android OS events. The following are the core functional requirements of the project:
1.	User Registration
Allows new users to create an account using a username and password stored locally.
2.	User Login & Authentication
Enables registered users to securely log in to the application using local data storage.
3.	One-to-One Chat Messaging
Allows users to send and receive text messages in a chat interface.
4.	Message History Storage
Saves chat messages locally so that previous conversations can be viewed later.
5.	User Session Management
Maintains login state even when the app is minimized or reopened.
6.	State Preservation on Screen Rotation
Preserves typed messages and chat state during screen rotation or configuration changes.
7.	Background and Foreground Handling
Ensures chat data remains intact when the app moves between background and foreground.
8.	Low-Memory Process Recovery
Restores user and chat state if the app is killed due to low memory.
9.	Simple and User-Friendly Interface
Provides a clean and intuitive UI for smooth user interaction. 
10. Logout Functionality
Allows users to safely log out and clear session data.







2) Feasibility Study
(Mapping Features to Resources / APIs / Libraries)
Feature No.	Feature Name	Resources / APIs / Libraries Used	Feasibility Explanation
1	User Registration	SQLite Database	SQLite allows efficient local storage of user credentials without internet dependency.
2	User Login	SQLite + SharedPreferences	SQLite validates credentials; SharedPreferences stores login state.
3	One-to-One Chat	RecyclerView	RecyclerView efficiently displays chat messages in list form.
4	Message History	SQLite Database	Messages are stored locally for persistence and retrieval.
5	Session Management	SharedPreferences	Stores login status to maintain session across app restarts.
6	Rotation Handling	onSaveInstanceState()	Saves UI state during configuration changes like rotation.
7	Background/Foreground Handling	Lifecycle Methods (onPause/onResume)	Ensures smooth transition without data loss.
8	Low-Memory Recovery	ViewModel / Bundle	Restores critical data when app is recreated.
9	User Interface	XML Layouts + Material Components	XML ensures responsive UI with minimal overhead.
10	Logout	SharedPreferences	Clears saved session data safely and efficiently.




3) Technical Developer Guide (Short)
Feature 1: User Authentication
Firebase Authentication is used to register and log in users using email and password. The login and signup screens are created using XML. FirebaseAuth methods handle user creation, login, and session management. Logged-in users are redirected directly to the chat screen.
Feature 2: Real-Time Chat Messaging
Firebase Realtime Database / Firestore is used to store and retrieve chat messages. Messages are sent to Firebase on button click and displayed using RecyclerView. Real-time listeners automatically update the chat interface when new messages are added.
Feature 3: State Preservation
Android lifecycle methods and Firebase session handling are used to preserve app state during screen rotation, background execution, and app restarts. User login state and chat history are restored automatically to ensure smooth user experience.

PROJECT PCTURES:
<img width="360" height="759" alt="image" src="https://github.com/user-attachments/assets/45e7e8aa-6702-4e8a-8079-0c62458dc64d" />
<img width="400" height="815" alt="image" src="https://github.com/user-attachments/assets/f65204a1-4288-44da-8314-2d0ca4afa063" />
<img width="356" height="754" alt="image" src="https://github.com/user-attachments/assets/945e3e00-73c3-4fbe-a45e-988e9269dac6" />
<img width="359" height="760" alt="image" src="https://github.com/user-attachments/assets/1dd2a20d-a9dd-44ea-a30c-1f059152f632" />
<img width="358" height="764" alt="image" src="https://github.com/user-attachments/assets/a31e1c02-7efe-4833-a083-3a46046d6f84" />
<img width="365" height="763" alt="image" src="https://github.com/user-attachments/assets/946a0f8a-e882-4a47-a67e-c7a7bd98e8c0" />
<img width="364" height="771" alt="image" src="https://github.com/user-attachments/assets/aa9916c4-2aff-4f3a-962c-f2c9932607a7" />
<img width="390" height="860" alt="image" src="https://github.com/user-attachments/assets/5733ee57-09ea-490a-a925-439a33c231f0" />









 

https://github.com/alishba5656/Balishchatboxx/blob/main/Balishchatbox-master.zip
