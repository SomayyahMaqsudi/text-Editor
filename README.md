# Text Editor Web Application

This is a README file for a text editor web application. The application provides a client-server architecture and utilizes various technologies and tools like npm, webpack, IndexedDB, service workers, and Heroku for development, bundling, caching, and deployment.

## User Story: 
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria:
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application

## Getting Started

To set up and run the text editor web application, follow these steps:

### Prerequisites

- Make sure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository to your local machine.
2. Open your terminal and navigate to the root directory of the application.

### Backend Setup

1. Install the required dependencies by running the following command:

   ```shell
   npm install
   ```

2. Start the backend server by running the following command:

   ```shell
   npm run start
   ```

   This will launch the server and serve the client files.

### Frontend Setup

1. Build the JavaScript files using webpack by running the following command:

   ```shell
   npm run webpack
   ```

   This will bundle your JavaScript files and generate the necessary assets.

2. Start the text editor application by running the following command:

   ```shell
   npm run start
   ```

   The application will open in your default browser.

### Usage

- Once the application is running, you can use the text editor functionality to create and edit content.
- IndexedDB will immediately create a database to store your content.
- Any changes made in the editor will be automatically saved to IndexedDB when you click off the window.
- If you close and reopen the text editor, your previously saved content will be retrieved from IndexedDB.

### Installing as a Desktop Application

- To install the web application as a desktop application, click on the "Install" button.
- This will download the application and create an icon on your desktop for easy access.
