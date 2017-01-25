# YouTube-Search-Client
A simple android application with following functionalities :
- Search videos on youtube of your choice.
- See description of each videos such as uploaded by, category, number of views, title, thumbnail etc.
- Functionality to play a video on the YouTube application if its present else it will try to access the web version of YouTube and play it there.

###Technical implementation details

- ListView is used to display list of videos with thumbnail, title, duration and uploaded by.
- YouTube data API v3 is used to fetch the data from YouTube.
- Piccaso library has been used for proper image caching (in case of thumbnails) and to reduce wastage of heap memory due to BitMaps.
- On clicking on a particular list item, app will take us to another screen where it show details of each video such as views, number of likes, category, title, uploaded by alomg with option to play the video.
