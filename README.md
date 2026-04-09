# 🎵 Musiqale - Song Lyrics Finder🎵

## Description

Musiqale is a sleek and interactive Single Page Application (SPA) that allows users to search and view song lyrics by their favorite artists. It uses asynchronous JavaScript (fetch) to retrieve lyrics from a local db.json file powered by json-server and dynamically updates the page without reloads..

### Users can

* Search for lyrics by artist and song title
* View lyrics instantly without reloading the page
* Add new songs to a central song list
* Edit or delete existing songss
* Enjoy a responsive TailwindCSS-styled layout with mobile-friendly sections
* Return to the home (default) state by clicking the Musiqale logo

## 🚀 Live Site

View Musiqale on GitHub Pages:  
[GitHub](https://github.com/Newton-Oduor/phase-1-project)

## 🎯 Features and Functionality

|Feature|Description|
|:------|:----------|
| Local JSON Server | Uses json-server to store and manage song lyrics data |
|Event Listener No. 1|DOMContentLoaded to ensure full HTML load|
|Event Listener No. 2|click on song items to display lyrics|
|Event Listener No. 3|submit on the form to add/edit/search songs|
|Array Iteration|.forEach() used to render and attach events to songs|
|Responsive Design|TailwindCSS styling for mobile and desktop views|
|Song Management|Add, edit, and delete songs from the database|
|Form Handling|Input validation and form reset after submission|
|Single Page App (SPA)|All actions and views happen on a single HTML page, with DOM manipulation|
|Back to Home|Clicking the Musiqale logo refreshes the page to its original state (soft reload)|

## 🧱 Project File Structure

```pgsql
├── index.html
├── src
│   └── index.js
├── pics
│   └── music-logo.png
├── db.json
├── README.md
```

## Setup Instructions

1., Clone this repository:

```bash
git clone [git@github.com:Newton-Oduor/phase-1-project.git](git@github.com:Newton-Oduor/phase-1-project.git)
```

2., Open the project folder in VS Code or any code editor.

3., Install (npm install -g json-server) & Run json-server --watch db.json or json-server --watch db.json --port 3000 to start the local server

4., Open index.html in a browser or use a Live Server extension in your code editor.

5., Ensure internet connection for Tailwind CDN to load properly

6., All actions will be handled on your local machine

## 💻 Technologies Used

HTML5 Page - structure
TailwindCSS CDN - Styling and layout
JavaScript (Vanilla) - Logic and DOM manipulation
JSON Server - Local backend API for lyrics storage
Git / GitHub - Version control and deployment

## ✅ Tailwind CSS Setup

This project uses the Tailwind CDN link for styling.
No installation needed. Included in the `<head>` of index.html like this:

```html
<script src="https://cdn.tailwindcss.com"></script>
```

For more on Tailwind:
[https://tailwindcss.com/docs/installation/play-cdn](https://tailwindcss.com/docs/installation/play-cdn)

## 📌 Future Improvements

* Add user authentication for personalized playlists

* Replace local JSON server with Firebase or another cloud backend

* Add real-time suggestions while typing

* Use a lyrics API like Lyrics.ovh for dynamic data

* Add error messages, loading indicators, and animations

## 📜 License

*This project is licensed under the MIT License.
Feel free to fork and improve it.*

## 📝Acknowledgments

json-server (Fake REST API)

[Tailwind CSS](https://cdn.tailwindcss.com)

[Markdown](https://www.markdownguide.org/)

[Emojipedia](https://emojipedia.org/)

* Special thanks to Moringa School Instructors & Flatiron School for the project guidelines.

**Author**
[*Newton Oduor*](https://github.com/Newton-Oduor)
