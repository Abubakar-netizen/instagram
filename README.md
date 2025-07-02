📲 Instagram Messaging System – Data Structures Project
This project simulates a real-time, two-user messaging system inspired by Instagram’s chat feature. It is built entirely using core data structures such as graphs, queues, and linked lists — without using any databases or third-party messaging services.

💡 Project Overview
📥 Send & receive messages between two users in real-time

🔁 Uses queues to handle message flow (FIFO)

🔗 Uses linked lists to store message history

🌐 Uses graphs to represent user relationships or message paths

🧵 Simulates real-time messaging using multithreading or interleaving logic

👥 System Requirements
Exactly two users logged into the system

Users can:

Send a message

Receive messages in real-time

View message history

⚙️ Technologies & Data Structures Used
Language: Python / C++ / Java (choose one based on your project)

Graph – To model user-to-user message routing

Queue – To manage real-time message delivery

Linked List – To store and retrieve message history

Stacks (optional) – For undo/redo functionality or message recall

🔁 How It Works
plaintext
Copy
Edit
[User A] ---> [Message Queue] ---> [User B]
               (FIFO Structure)

- Both users are represented as nodes in a graph.
- Messages are stored in queues per user.
- All sent messages are logged using linked lists.
🧪 Sample Features
sendMessage(user1, user2, message)

receiveMessage(user)

showHistory(user1, user2)

Optional: isConnected(user1, user2) using BFS/DFS in the graph

📁 Project Structure
plaintext
Copy
Edit
instagram_ds_project/
├── main.py / main.cpp
├── user_graph.py / .cpp       # Graph class to store users
├── message_queue.py / .cpp    # Message queue handling
├── message_history.py / .cpp  # Linked list message history
└── README.md
🎓 Academic Info
Project Title: Instagram-like Messaging Using Data Structures

Course: Data Structures and Algorithms

Semester: 3rd / 4th Semester (as applicable)

Level: Intermediate

Focus: Real-time logic with core data structures (No DB)

📚 License
This project is for academic and educational use only.
