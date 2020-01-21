# ios-pwa-splashscreen
How to implement custom app icon and splash screen support for iOS to PWA

# add a service worker
ng add @angular/pwa --project *project name*

# generate icons and splashscreen images
icons: https://realfavicongenerator.net/
splashscreens: https://appsco.pe/developer/splash-screens

# add icons to manifest.webmanifest

# modify index.html
add meta, icons and splash screen images

# build & serve
ng build -prod
http-server -p *port number* -c-1 dist/*projectname*

# Links
Angular docs: https://angular.io/guide/service-worker-getting-started
Apple docs: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html
Meta tags: https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariHTMLRef/Articles/MetaTags.html
