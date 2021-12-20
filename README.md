# Sheep NFT
### Use Docker to run this Demo

```
## run this demo in Docker container
$ docker run -u node --name cennz-nft-demo -it --rm -p "3000:3000" -v "$PWD:/app" -w "/app" node:12 bash

## Inside your docker container run the following
$ yarn install && yarn run start

```

## Setup

There are a couple steps required for installation:

- Ensure you have [Node js](https://nodejs.org/en/) and [yarn](https://classic.yarnpkg.com/en/docs/install/#mac-stable) installed
- Run `yarn` to install dependencies
- _Optional_ - Install the [Cennznet Browser Extension](https://chrome.google.com/webstore/detail/cennznet-extension/feckpephlmdcjnpoclagmaogngeffafk?hl=en) for managing transactions between Dapps & accounts. Only required if you want to connect to your wallet via the browser extension and not via Keyring. The App supports both options.
- Simply run `yarn start` to launch the app
- Connect to `localhost:3000` on a browser to view the demo
