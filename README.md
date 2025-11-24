# Garry-activity-planner
**Garry** is a personal AI assistant that plans activities according to  local weather, public events and user hobbies/personal info.  He has an integrated conversational model that retrieves user details through friendly and natural conversation while avoiding the collection of overly sensitive information.

**Loading user data:**
Data are loaded after the Insert button is pressed.
User credentials are stored in a JSON file and are automatically loaded the next time the application starts.

<img width="856" height="513" alt="User_load_example" src="https://github.com/user-attachments/assets/32da1af8-1a2e-4500-bae8-01fd243a9f4c" />

**NoteBot: conversationally gathering user information**
When the user clicks Save and Return, the model extracts relevant information from the conversation and organizes it into the appropriate categories.
The structured data is subsequently stored in a JSON file.

<img width="935" height="660" alt="notebot_example" src="https://github.com/user-attachments/assets/e78f9c8d-484c-41a8-a87e-83c932fcfa8d" />

**Activity recommendation relevant to user's interests**
This view shows:
1. The user profile stored in a JSON file by the Notetaking model (right window).
2. An activity recommendation generated for the current day.
The model combines the saved user data with the weather report retrieved with the API and result of search of nearby events that match the user’s hobbies.

<img width="867" height="500" alt="completion_example" src="https://github.com/user-attachments/assets/21d51571-596c-4417-b1b9-313849d9ad09" />

**Event suggestion based on hobby and local data**
Model suggested interesting event in the future.

<img width="861" height="513" alt="completion_event_example" src="https://github.com/user-attachments/assets/b9079496-c1a6-4938-973e-ce18646b650b" />

# More detailed README is in the garry folder.
