▶️ How to Run
Run the server:
node server.js
Open browser:
http://localhost:3000

🌐 Routes & Functionality
Home Route
/
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
