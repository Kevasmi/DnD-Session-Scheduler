# Introduction

The Dungeons and Dragons Session Scheduler allows dungeoneering parties to easily plan out their next adventure session. Have you and a group of explorers enter in time availabilities and receive a clear and concise schedule that actively tracks when all your party members are available to play!

The inspiration for the project stems from the shared frustation of all dungeon delvers - session plannings. My own group is plagued by this common woe, and with my recent experiences creating multiple different self-study projects, I thought to undertake this personal project in my free time in the hopes that my own group might use it someday.

# Planning

The project will be built using the React framework as the front-end, Jest as the testing software, and Firebase as the back-end. I hope to replace Firebase with Node.js once I've completed my studies with back-end. It will also use the Nylas Scheduler API as the main software that will compare all listed availabilities and returns valid overlapping times for groups to play.

The application will let users make accounts, which will allow them to create campaigns for them to invite other users to. They will be prompted with entering in availabilties, and once more than one user has done so, the scheduler will automatically mark and indicate where all current users have overlapping availability.

Using Figma, a website planning application, I made a simple mock-up of what the schedule page of the application might look like.

![image](https://user-images.githubusercontent.com/96889143/198142119-132007f6-ae3f-4c78-ae39-be173656dba6.png)

The application will collect user availabilities for individual campaigns and using the Nylas API, discover overlapping availabilties. The schedule will indicate with two lines where the viable times begin and end.








