# real-world-nuxt

## Build Setup

```bash
# install dependencies
$ npm install

# run the mock api for request (ensure it defaults to port 3000)
$ json-server --watch db.json --port 3000

# serve with hot reload at localhost:3001.
$ npm run dev
# prepend this with port definition is dummy api server is running
$ PORT=**** npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate

# run dummy api server from project  root directory. Note: default port is localhost:3000
$ json-server --watch db.json
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).
