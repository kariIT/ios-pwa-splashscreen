## How to implement a custom app icon and a splash screen support for iOS PWA

![Output sample](https://github.com/kariIT/ios-pwa-splashscreen/blob/master/demo.gif)

__1. Add a service worker__

``` ng add @angular/pwa --project *project name* ```


__2. Generate icons and splashscreen images__

icons: https://realfavicongenerator.net/

splashscreens: https://appsco.pe/developer/splash-screens


__3. Add icons to manifest.webmanifest__


__4. Modify index.html__

add meta, icons and splash screen images
```
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="default">
  <meta name="apple-mobile-web-app-title" content="ios-pwa-splashscreen">```


## Build & serve
``` ng build --prod ```

``` http-server -p *port number* -c-1 dist/*projectname* ```

## Links
Angular docs: https://angular.io/guide/service-worker-getting-started

Apple docs: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html

Meta tags: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariHTMLRef/Articles/MetaTags.html
