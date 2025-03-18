# MULTITHREADED-CHAT-APPLICATION

COMPANY : CODETECH-IT SOLUTIONS

NAME : PAYAL OJHA

INTERN-ID : CT08ULL

DOMAIN : JAVA PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

TASK-DESCRIPTION :

The Multi-User Chat Application is a real-time messaging system that enables multiple clients to communicate through a central server. This project uses Java Sockets and Multithreading to handle multiple users simultaneously. A Java Swing-based GUI provides an intuitive interface for users to send and receive messages.

The application follows a Client-Server architecture, where the server listens for incoming connections and manages message broadcasting, while clients connect to the server and interact with other users. Each client runs on a separate thread, ensuring smooth communication between multiple users.

This project is designed for scenarios requiring real-time text communication, such as team collaboration, customer support, and educational discussions.

Technology Stack : 

The following technologies are used in this project:
- Programming Language: Java (JDK 22)
- Networking: Java Sockets (TCP) for client-server communication
- Multithreading: Java Threads to handle multiple clients concurrently
- GUI: Java Swing and AWT for the graphical user interface
- I/O Streams: BufferedReader and BufferedWriterWriter for data transmission
- Development Environment: Apache Netbeans

System Architecture : 

1. Server Component (Server.java)
- Runs a ServerSocket to accept client connections.
- Creates a new thread for each client using multithreading.
- Manages client connections and removes inactive clients.
- Broadcasts messages to all connected clients except the sender.

2. Client Component (UserOne.java & UserTwo.java & UserThree.java)
- Connects to the server using a Socket.
- Sends messages to the server, which are then forwarded to other clients.
- Receives messages from the server and updates the GUI chat area.
- Uses Java Swing to provide an interactive chat interface.

Application Areas :

1.Team Collaboration Platforms:

- Used by software development teams or remote workers to communicate.
- Can be integrated into project management tools like Slack or Microsoft Teams.

2. Customer Support and Helpdesk Chat:

- Businesses can use this chat system to provide live support to customers.
- Useful for handling multiple client queries simultaneously.

3. Educational Chatrooms:

- Can be used in online classrooms where students and teachers discuss topics.
- Suitable for doubt-solving sessions and peer discussions.

4. Gaming Chat Systems:

- Real-time communication for multiplayer games.
- Can be enhanced with voice or video chat features.

5. Local Intranet Messaging for Offices:

- Employees in a company can communicate without internet access.
- Helps in secure, internal communications.

Key Features : 

✔ Real-time Messaging: Users can communicate instantly.

✔ Multiple Client Support: Handles multiple users via multithreading.

✔ Graphical User Interface (GUI): Easy-to-use chat window with Java Swing.

✔ Message Broadcasting: Every message is sent to all connected clients.

✔ Scalable Architecture: Can be extended with authentication, private messaging, or file sharing.

Output screenshots: 

1.

![Image](https://github.com/user-attachments/assets/bd41474e-cca9-4c46-9f8d-86c48ecd46a5)

2.

![Image](https://github.com/user-attachments/assets/f02501f1-65ff-41a3-9648-1039ea898f72)
