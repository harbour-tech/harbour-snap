# Harbour Ramp Snap for Metamask

## Publishing to npm

Pre-requisites:
1. run `npm install` to download all dependencies
2. run `npm run build` to build the snap
3. run `npm adduser` to authenticate with the registry
4. make sure your npm user has access to the `harbour-fi` organization

Then to publish to npm:
1. Update version in package.json
2. `npx mm-snap manifest --fix`
3. `npm publish --access public`
