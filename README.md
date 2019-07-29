# ionic
Ionic CLI Docker Image

## Example Usage
`docker run -it --rm -v $(pwd)/app skypress/ionic:latest `

## Notes
- Base image is `node:12-alpine`
- Everything is ran as the `node` user
- Includes `ionic` globally
- `/app` is the default `WORKDIR`

## Credits
- [Docker Node](https://hub.docker.com/_/node/)
- [NPX](https://ionicframework.com/)
