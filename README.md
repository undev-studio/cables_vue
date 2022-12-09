# cables.gl vue integration and component

small component to load one or more [cables.gl](https://cables.gl/) patches in your [vue](https://vuejs.org/) app

the app was created using [npm init vue@latest](https://vuejs.org/guide/quick-start.html#creating-a-vue-application), 
check `src/App.js` for an example on how to load two patches, with default values and custom ones. `src/components/CablesPatch.js` contains the component.

to update your patches, put your exported files into `public/patch` or configure a different path when using the
component.

## requirements

* nodejs and npm in a current version

## installation

* check out this repository
* run `npm install`
* run `npm run dev`
* browser will open and show two patches overlaying
