# The backend for Ani-Creations
This will be the backend for the chat app. Based on Django.

## Database solutions

### Current
Currently going to use postgresql because it is the most modern db supported by django. 

### Other options
* Mongo DB: Maybe beter performance and code readability because it is nosql. However needs a special thing that overrides django's sql to python thingy
* Supabase DB: Based on postgresql, but is not officially supported, so will be harder to implement.

## Hosting 

### Current
Going to use pythonanywhere (it is by Annaconda, so I might switch to Anaconda notebooks). It provides free hosting, but deactivates every 3 months. 
Implementing a solution where github actions will just upload it to pythonanywhere automatically after a realease is created or when master is updated. 

### Other options
* Could use self-hosting if I eventually get my hands on a server.
* Could use other things like AWS or Azure
