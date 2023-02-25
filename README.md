# **Phaser 3 + Typescript + Socket.io**
Heroku deployable **Phaser 3** template with **socket.io** and type checking

- This template allows you to easily deploy a **Phaser 3** game with web socket support.

- To get started, adjust */src/frontend/main.ts* to configure your game and import scenes. 

- Add your scenes to the *./scenes* folder. 

- For multiplayer, socket communication should be added to the */src/backend/GameCommunication.ts*

##  **Compile and run**
```
npm run build-front

npm run build-back

npm run start-server (or 'heroku local web' is using heroku)
```

## **Deploy to heroku**
- Sign up at heroku.com
- Install heroku cli

- Then
```
git init
git commit -m 'first commit'
heroku create your-appname-here (just make one up)
git push heroku main (or master)
(later, just do 'npm run deploy')
```