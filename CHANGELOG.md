# Change Log

### [1.1.0] 2020-05-01
### Bug fixing
- https://github.com/creativetimofficial/ct-nextjs-material-kit-pro/issues/7
- https://github.com/creativetimofficial/ct-nextjs-material-kit-pro/issues/6
- https://github.com/creativetimofficial/ct-nextjs-material-kit-pro/issues/5
- https://github.com/creativetimofficial/ct-nextjs-material-kit-pro/issues/3
- https://github.com/creativetimofficial/ct-nextjs-material-kit-pro/issues/2
### Major style changes
- `assets/scss/plugins/_plugin-react-image-gallery.scss`
- `assets/jss/nextjs-material-kit-pro/pages/productStyle.js`
- `assets/jss/nextjs-material-kit-pro/components/customDropdownStyle.js`
### Deleted components
### Added components
- Add `pages/404.js` to stop NextJS warning of not having a 404 page
### Deleted dependencies
### Added dependencies
### Updated dependencies
```
@material-ui/core        4.3.2   →    4.9.12
@material-ui/icons       4.2.1   →     4.9.1
next                     9.0.5   →     9.3.6
next-images              1.1.2   →     1.3.1
node-sass               4.12.0   →    4.14.0
nouislider              14.0.2   →    14.2.0
react                   16.9.0   →   16.13.1
react-dom               16.9.0   →   16.13.1
react-image-gallery     0.8.18   →     1.0.7
react-swipeable-views   0.13.3   →    0.13.9
webpack                 4.40.2   →    4.43.0
@types/googlemaps       3.37.6   →    3.39.4
```
### Warning
_The following warnings come from some of our dependencies, however they do not affect the UI or the functionality of the product - if the issues will perssit and will change into errors in the next version of React (v17), we will drop their usage and replace with other dependencies:_
```
npm WARN deprecated popper.js@1.16.1: Popper changed home, find its new releases at @popperjs/core
npm WARN deprecated request@2.88.2: request has been deprecated, see https://github.com/request/request/issues/3142
npm WARN deprecated mkdirp@0.5.3: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)
npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
```
_The following dependencies raise warnings (of deprecation or renamed) in develpment mode: Component, DateTime, ReactSwipableView, TagsInput, withGoogleMap(Component), withScriptjs(withGoogleMap(Component)). If the warnings will perssit, and will become errors in React 17, we will drop their usage and replace them with other plugins._

## [1.0.0] 2019-09-23
### Original Release
- Started project with NextJS
- Added Material-UI as base framework
- Added React Hooks
- Added design from Material Kit PRO React by Creative Tim
