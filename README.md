# How to start this project

1. Run `yarn start` in `/react` folder to start a React application;
2. Run `yarn start` in `/server` folder to start a Node.js server;
3. To generate segments run `node generate.mjs` in `/server/src`

## Basically, we have three Players

1. Chunks and File players requesting a video file from a server in a “simple” way → fetch video file by a link.

2. Segments players work a bit differently → it fetches m3u8 list with the segment file names and timecodes at first and then file by one at a specific time
