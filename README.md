# MERN Stack Template

Template MERN tech stack for forking

server installation

```
cd mern/server
npm install mongodb express cors
```

create config.env in server

```
ATLAS_URI=mongodb+srv://<username>:<password>@<cluster>.<projectId>.mongodb.net/employees?retryWrites=true&w=majority
PORT=5050
```

client installation

```
cd ..
cd client
npm install
```

tailwind installation (follow tailwindcss docs)

```
npm install tailwindcss @tailwindcss/vite
```

reactor dom installation

```
npm install -D react-router-dom
```

to start

```
node --env-file=config.env server (server)
npm run dev (client)
```
