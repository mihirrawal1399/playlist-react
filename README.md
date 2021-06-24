# :notes:playlistreact:musical_note:
### Web Music Playlist using [ReactJS](https://reactjs.org/) and [CORS(Cross-Origin Resource Sharing)]()
a simple Website where anyone can stream one's playlist from anywhere.

##
### Getting Started
Create a music folder for the mp3 files for your epic playlist. Suggested keeping the folder under project directory.

Then host the music files using [http-server](https://www.npmjs.com/package/http-server) and fetch the songs on the website using CORS ↓

Change directory to the music folder and run `playlistweb\music> npx http-server -a localhost -p 9000 –cors`

Start the Reactapp `playlistweb> npm start` 
##
![image](https://user-images.githubusercontent.com/54273763/123214098-6eb63900-d4e4-11eb-8cb7-f90266955b69.png)
![image](https://user-images.githubusercontent.com/54273763/123214171-81307280-d4e4-11eb-9fc4-14bb996f8c57.png)
![image](https://user-images.githubusercontent.com/54273763/123214201-8988ad80-d4e4-11eb-947a-efefdc33c24c.png)

##
### Dependencies:
```
"dependencies": {
    "axios": "^0.15.2",
    "cors": "^2.8.5",
    "http-server": "^0.12.3",
    "nodemon": "^2.0.7",
    "react": "^15.3.2",
    "react-dom": "^15.3.2"
  }
```
