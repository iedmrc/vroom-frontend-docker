## VROOM Frontend Docker

This repository contains dockerized [**VROOM Frontend**](https://github.com/VROOM-Project/vroom-frontend)


## Usage

Just modify the `api.js` file as you wish and build the image. The image runs [**VROOM Frontend**](https://github.com/VROOM-Project/vroom-frontend) and serves through the port `9966` by default. You should modify `api.js` to specify [**VROOM-express API**](https://github.com/VROOM-Project/vroom-express)'s *`host`* and *`port`* which defaults `http://localhost:3000`

### Compose File
---
See the gist [here](https://gist.github.com/iedmrc/51d02fefa9e3ee91a5608c02c452c965) for the "*`docker-compose` file stack*" I created.