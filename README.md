 **Features**

 
 Distribute files to active storage nodes.

 Simulate node failures and revivals dynamically.

 Real-time activity logs of all operations.

 Web interface using HTML, CSS, and Flask (Python).(working)

 Simple backend logic to simulate distributed file handling.

 Fault Tolerance ensures no file is written to offline nodes.

 

**GUI_Overview**

 
The interface allows you to:

Input a filename to distribute.

Toggle node status (Online/Offline).

View live logs of actions.

Revive nodes using buttons.



** How_It_Works**
 
Nodes (Node1, Node2, Node3) are simulated as online or offline.

Files are only stored in online nodes (one copy per request).

If no node is online, the system logs a failure message.

Users can take a node offline or revive it using the GUI.

All activities are logged and shown on the web page.
