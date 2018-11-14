# sarlacc-app
An app for memorizing things to make them available for quick search

## Concept
The app will allow use to quickly throw in some data for a fast search later. Internally, the app indexes the data and tries to categorize it into several categories like "useful data", "reminders", "links", "thoughts" etc. If it comes across the URL, its' contents will be processed too.
You can go back to the app later and enter keywords to find the things you've put. Also, the app should suggent to revisit some things based on the last access time and other heuristics.

## Tools
The app should be available from the desktop and mobile devices, so it is either Electron or anything else web-based. It would be good to try noSQL DB. Also, webworkers would suit well to send some notifications to the device. 
