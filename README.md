▶️ How to Run
Run the server:
node server.js
Open browser:
http://localhost:3000

🌐 Routes & Functionality
Home Route
/<img width="1580" height="386" alt="image 3" src="https://github.com/user-attachments/assets/d839da60-4a98-408b-b6b1-c87f07c308ce" />
<img width="1689" height="416" alt="image 2" src="https://github.com/user-attachments/assets/ef3e39c1-f14a-45e5-a8a5-a851f843ccf6" />
<img width="1577" height="439" alt="image 1" src="https://github.com/user-attachments/assets/e220f9af-9649-491a-a58b-d47904853b03" />

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
