# Universal Links

This repo contains a simple demonstration of a web site that is enabled for universal links.

Important:
* This site **MUST** be hosted in its own domain/subdomain for universal links to work properly
* The apple-app-site-association **MUST** be included and set properly for the app. Currently set for a POC app. The app requires additional code so you can't just add any old app and expect it to work.
* ra.html - **MUST** include the proper app store links
* ra.html - to force an immediate redirect to the app store, uncomment the <script>...</script> contained in <head>
