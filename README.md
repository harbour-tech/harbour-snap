# Harbour Ramp Snap for Metamask

## Publishing to npm

Pre-requisites:
1. run npm install to download all dependencies
2. npm run build to build the snap

Then to publish to npm:
1. Update version in package.json
2. `npx mm-snap manifest --fix`
3. `npm publish --access public`
