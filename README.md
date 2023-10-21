# CS360

This application was designed to help warehouses track inventory. Some of the requirements included a login screen that connects to a database to store and retrieve usernames and passwords, and a 
screen that utilizes a grid layout to display items. This grid layout screen also utilizes a database to store and retrieve item information. The last requirement was a screen where the user can 
enable or disable notifications. My design's weren't very flashy, they were simple and get the job done. For this specific application's use case, I believe a simpler design is appropriate. I like 
how the items are color-coded, but would like to implement how colors are assigned differently in the future. Currently, the colors are assigned in the recycler view's Bind method, and is based
on the item's name length. I believe a better way to do this would be to randomly assign the items color, and store the hex code in the database. This way, items with the same name length aren't 
all one color, and the colors won't change when buttons are clicked. 

When programming the app, I worked on one screen at a time. Once the screen was functional and working correctly, I started working on the next one. This helped me pace my development and not feel 
overwhelmed with the amount of work that was needed. I believe that setting little goals and reaching them helps keep motivation high throughout development. The recycler view was by far the hardest
to implement. I worked on it for an entire day and it just wasn't working correctly. I decided that I needed to not be attached to the code, and scrap the entire thing to start from scratch. I believe 
that my implementation of the databse and SQLite was good and it is what I'm most proud of. This was my first non-console application and I am very proud of how it turned out. There is still much
to learn though, and I look forward to learning more about mobile development. 
