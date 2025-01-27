<h1>Digital Lost And Found Management System</h1>
<h2>Overview</h2>
Institutions register directly on the system.<br>
All data (lost and found reports) is managed in a centralized database.<br>
Users interact with the centralized system, regardless of the institution where the item was lost or found.<br>
<h2>Entire Process: </h2><br>
<b>1. User Reports a Lost Item</b><br>
<p>User submits a Lost Item Report via the system. This report includes details like item description, image (if available), and the location where the item was lost.<br>
The system receives and reformats the report data for easier processing.</p><br>
<b>2. System Analyzes Report Data</b><br>
<p>Context Analysis with NLP: The system processes the textual description provided by the user using Natural Language Processing (NLP) to understand key details about the lost item.<br>
Image Recognition: If the user uploads an image of the lost item, the system uses image recognition to extract features and match it with existing database records.<br>
These two processes (NLP and Image Recognition) help create a search query for the next step.</p><br>
<b>3. Search Database for Matching Items</b><br>
<p>The system queries the Lost Item Database and the Found Item Database to check for any items that match the search criteria (based on item description, location, and image).<br>
Found Item Report: If a matching item is found, the system notifies the User and checks the Item Verification Status.</p><br>
<b>4. Item Verification</b><br>
<p>Institution Verification: Once a match is found, the Institution (such as a Lost and Found department) verifies whether the found item is indeed the lost item.<br>
The institution updates the Item Verification Status.</p><br>
<b>5. Item Return Process</b><br>
<p>User Chooses Return Method: The user can choose to either self-pickup the item from the institution or request it to be shipped.<br>
The system captures this Return Method selection.<br>
The Institution handles the return by either coordinating pickup or shipping based on the user’s choice.</p><br>
<b>6. Update Lost Item Report Status</b><br>
<p>After the item is returned to the rightful owner, the Lost Item Report Status is updated in the system to reflect that the item has been successfully returned.</p><br>
<b>7. User Reports a Found Item</b><br>
<p>If a User finds an item, they can submit a Found Item Report using the system, providing similar information (description, image, and location).<br>
This report goes through the same processing as a Lost Item Report: reformatting, context analysis, image recognition, and searching the database.</p><br>
<b>8. Institution Registration and Management</b><br>
<p>Institutions need to register on the platform to be able to verify and handle found or lost item reports.<br>
The System Administrator oversees institution registrations, ensuring proper data and process management.</p><br>
<h2><a href="https://github.com/XD-learner/LostFound/blob/main/ContextDiagram.png">Context Diagram</a></h2>
<img width="500" height="400" src="https://github.com/XD-learner/LostFound/blob/main/ContextDiagram.png"><br>
<h2><a href="https://github.com/XD-learner/LostFound/blob/main/DFD.png">DFD</a> </h2>
<img width="500" height="400" src="https://github.com/XD-learner/LostFound/blob/main/DFD.png">
<h2><a href="https://github.com/XD-learner/LostFound/blob/main/ERD..png">ERD</a></h2>
<img width="500" height="400" src="https://github.com/XD-learner/LostFound/blob/main/ERD..png"><br>
<h2>Gantt Chart</h2>
<img width="500" height="400" src="https://github.com/user-attachments/assets/5e4a3469-26c9-464f-b2bb-16f7a11984af"><br>


