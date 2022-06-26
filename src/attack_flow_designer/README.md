# attack-flow-designer

## Local build and deploy

Local deploy (for testing only):

```
npm install
npm run serve
```

Build a static version for hosting:

```
npm install
npm run build
```

## Dockerized build and deploy


Build:

```
docker build -t attack-flow-designer:current .
```

Run:

```
docker run --name milanko -p 8888:80 -d attack-flow-designer:current
```

and visit [http://localhost:8888/](http://localhost:8888/) afterwards.
