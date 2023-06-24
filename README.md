# GitHub Pages PWA

## Manifest

<code>
{
    // Name of the app and short name in case there isn't enough space
    "name": "Github Page PWA",
    "short_name": "GPPWA",
    // Description what your app is
    "description": "Github Page as a Progressive Web App",
   
    // Scope and start URL - these need to change to yours
    "scope": "/offline_web/",
    "start_url": "/offline_web/",

    // "offline_page": "/index.html",

    // "fallbacks": {
    //     "/": "/index.html"
    // },
   
    // colours of the app as displayed in the installer
    "background_color": "#ffffff",
    "theme_color": "#ffffff",
   
    // Display of the app. 
    // This could be "standalone", "fullscreen", "minimal-ui" or "browser"
    "display": "standalone", 
   
    // The possible icons to display. Make sure to change the src URL,
    // the type and the size to your needs. If the size isn't correct, 
    // you may not be able to install the app. 
    "icons": [
        {
          "src": "/offline_web/favicon.jpg",
          "type": "image/png",
          "sizes": "700x700"
        }
    ]
}
</code>