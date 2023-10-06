# [Backstage Developer Portals](https://backstage.io)

Developer portals using Backstage App!

To start the app, run:

```sh
yarn install
yarn dev
```

## Features
- create software templates
- check the dependecy between services
- CI/CD
- AWS CDK

## Docker
- install docker locally
- run docker image build
```sh
yarn install
yarn ts
yarn build:backend
yarn build-image
```
- docker run
```sh
docker run -it -p 7007:7007 backstage
```