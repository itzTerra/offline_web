# GitHub Pages PWA

## Manifest

```json
{
    "name": "Github Page PWA",
    "short_name": "GPPWA",
    "description": "Github Page as a Progressive Web App",
    "dir": "ltr",

    // Display of the app ("standalone", "fullscreen", "minimal-ui" or "browser")
    "display": "fullscreen", 
    "orientation": "portrait",
   
    // "scope": "/offline_web/",
    // "start_url": "/offline_web/",

    // "offline_page": "/",

    // "fallbacks": {
    //     "/": "/"
    // },
   
    // colours of the app as displayed in the installer
    "background_color": "#ffffff",
    "theme_color": "#ffffff",
   
    "categories": [],
    "shortcuts": [],
    "screenshots": [],
   
    // The possible icons to display. Make sure to change the src URL,
    // the type and the size to your needs. If the size isn't correct, 
    // you may not be able to install the app. 
    "icons": [
        {
          "src": "/offline_web/favicon.jpg",
          "type": "image/png",
          "sizes": "512x512"
        }
    ]
}
```