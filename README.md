# spotify-enhance

## local

```sh
npm i
npm run dev
```

.env in root folder

```sh
SPOTIFY_CLIENT_ID=
SPOTIFY_CLIENT_SECRET=
```

## netlify (client)
```sh
Base directory: client
Build command: CI=false npm run build
Publish directory: client/build
```

## heroku (server)
```sh
heroku create spotify-serv-backend
heroku config:set SPOTIFY_CLIENT_SECRET=
heroku config:set SPOTIFY_CLIENT_ID=
heroku config:set FRONTEND_URI=
heroku config:set REDIRECT_URI=
git push heroku master
```
