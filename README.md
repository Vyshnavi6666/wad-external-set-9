<img width="1017" height="312" alt="img 5" src="https://github.com/user-attachments/assets/74d56578-9943-4940-8a6f-ba10ef92cdaf" />
<img width="1507" height="390" alt="img 4" src="https://github.com/user-attachments/assets/c6070c6e-1fdf-4f24-b33f-039d41a45c34" />
<img width="1531" height="433" alt="img 3" src="https://github.com/user-attachments/assets/1f88fa88-00e0-44a0-8e76-10db5b2a1648" />
<img width="1562" height="493" alt="img 2" src="https://github.com/user-attachments/assets/967be3ff-0d25-411d-9e5e-7f0d4152512f" />
<img width="1618" height="554" alt="img 1" src="https://github.com/user-attachments/assets/33ab3171-14e7-43bd-92b4-2b53bf24db83" />

▶️ How to Run
Run the server:
node server.js
Open browser:
http://localhost:3000

🌐 Routes & Functionality
Home Route


Displays welcome message

OS Module
/os
Shows system information:
Platform
CPU architecture
Free memory
Total memory

Path Module
/path
Displays file details:
File name
Directory path
File extension

Events Module
/event
Demonstrates event-driven programming
Logs message in console when accessed

⚙️ Events Used
request_received
Triggered on every request
Logs requested URL
event_page_visited
Triggered only when /event route is accessed
Logs timestamp of visit

🧠 Key Concepts
Module      Description
http        Creates server and handles requests
os          Provides system-related information
path        Handles file and directory paths
events      Enables event-driven programming
