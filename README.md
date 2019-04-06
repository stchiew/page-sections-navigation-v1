# Page Sections Navigation

spFx web part to add sections navigation to the SharePoint page. A clone of the react-page-sections-navigation at [SharePoint Framework Samples](https://github.com/SharePoint/sp-dev-fx-webparts/tree/master/samples/react-page-sections-navigation)



## Used SharePoint Framework Version 
![drop](https://img.shields.io/badge/drop-1.7.1-green.svg)
Maintaining at 1.7.1 to see if the position:sticky polyfill still applies

## Applies to

* [SharePoint Framework](http://dev.office.com/sharepoint/docs/spfx/sharepoint-framework-overview)
* [Office 365 developer tenant](http://dev.office.com/sharepoint/docs/spfx/set-up-your-developer-tenant)


## Version history

Version|Date|Comments
-------|----|--------
1.0|April 06, 2019|Initial release

## Disclaimer
**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

* clone this repo
* move to right folder
* in the command line run:
  * `npm install`
  * `gulp bundle --ship`
  * `gulp package-solution --ship`
* from the _sharepoint/solution_ folder, deploy the .sppkg file to the App catalog in your tenant
* in the site where you want to test this solution
  * add the app named _page-sections-navigation-client-side-solution_
  * edit a page
  * add _Page Sections Navigation_ web part
  * add as much _Page Sections Navigation Anchor_ web parts as you want - each anchor adds an item to the navigation
  * configure web parts

## Features

This sample illustrates how to use SharePoint Framework Dynamic Data features to connect web parts on the page.
It also can be used as ready-to-go solution to add page sections navigation to SharePoint pages.

## Custom CSS
The web parts in the sample allow to use custom CSS to override the styles. You can set _Custom CSS URL_ property of *Page Sections Navigation* web part and include css classes for both Navigation and Anchor in referenced file.
Please, refer [custom css sample](./assets/psn-custom.css) for the CSS sample.