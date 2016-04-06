# YouTube-Search-Client
A simple youtube search-client  android application with following functionalities :
- Search videos on youtube of your choice.
- See description of each videos such as uploaded by, category, number of views, title, thumbnail etc.
- Have functionality to play video on the youtube application, if its not present then it will try to access web and play it there.

###Technical implementation details

- List view is used to display list of videos with thumbnail, title, duration and uploaded by.
- Youtube data api v3 is used to fetch data from youtube.
- Piccaso library has been used for proper image caching ( in case of thumbnails) and reduce wastage of heap memory due to BitMaps.
- On clicking on particular list item, app will take us to another screen where it shows details of video such as views, number of likes, category, title, uploaded by and option to play the video.

