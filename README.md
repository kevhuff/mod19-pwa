# Light Weight Text Editor PWA

This is a text editor web application with the following features and functionality.

![Screenshot 2023-09-10 212034](https://github.com/kevhuff/mod19-pwa/assets/3771399/8047c759-b992-43b5-baf0-762fa518853f)


## Getting Started

### Folder Structure

The project is organized into a client-server folder structure for clarity.

### Starting the Application

To start the application, run the following command from the root directory:

```
npm run start
```


This command will initiate both the backend server and serve the client-side application.

#### Webpack Bundling
Webpack is used to bundle JavaScript files for optimal performance.

#### Webpack Plugins
Running Webpack plugins generates the following files:

- HTML file
- Service worker
- Manifest file

### Application Features
Next-gen JavaScript

The application supports the use of next-gen JavaScript without errors.

#### IndexedDB
IndexedDB immediately creates a database storage upon opening the text editor.
Content entered in the text editor is automatically saved to IndexedDB when clicking off the DOM window.
Content is retrieved from IndexedDB when reopening the text editor.

### Desktop Icon Installation
Clicking the "Install" button allows users to download the web application as an icon on their desktop.

#### Service Worker
The web application has a registered service worker using Workbox for offline caching and improved performance.

#### Static Asset Precaching
Static assets are pre-cached by the service worker upon loading, including subsequent pages and assets.

#### Deployment
View the app in action at my deployment below.
L.W.T.E
(sheltered-harbor-68273-21d0b53db6f6.herokuapp.com)
(Links to an external site.)

## License
This project is licensed under the MIT License
