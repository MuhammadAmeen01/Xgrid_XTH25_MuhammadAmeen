# Xgrid_XTH25_MuhammadAmeen
Design Document of News Feed System
The design is very simple, whenever a user creates a post the system will define which type of content is being posted from the user's side, and it will differentiate and upload the content to respective table which is newsfeed, and if the content is video type it will store data in videocontent_tl. here i have added url option which should be public to access the video content, we can also add option that stores the data. 
Based on likes and comments the post will be user centric, and also regarding with friends and groups he has. 
Regarding non functional requirements, the database is normalized and removes many to many relations and caters avoiding repeating data in tables.
All in all this design is not perfect it might have some issues that can be found when we are actually designing backend api to make the backend work.
