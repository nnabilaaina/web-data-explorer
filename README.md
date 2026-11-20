# Web Data Explorer

A responsive web dashboard that retrieves data from a public REST API and allows users to search, save, and manage their favourite records.

## Overview

Web Data Explorer is a JavaScript-based web application developed as part of a JavaScript assessment. It demonstrates how to retrieve data from a REST API, dynamically display information using a Data-First Render Pattern, and manage user favourites with browser storage.

The application provides a simple interface where users can explore API records, search by keyword, and save their favourite items for later access.

## Features

- **REST API Integration** – Fetches data from a public API using JavaScript `fetch()`.
- **Asynchronous Data Retrieval** – Uses `async/await` to handle API requests.
- **Loading and Error Handling** – Displays loading messages and handles failed requests.
- **Keyword Search** – Allows users to search API records by title.
- **Dynamic Rendering** – Updates the dashboard using a central state object and a dedicated `render()` function.
- **Favorites Management** – Allows users to save and remove favourite records.
- **Event Delegation** – Handles dynamically generated button interactions.
- **Local Storage** – Saves favourite records and restores them after a browser refresh.

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JavaScript)
- REST API
- Fetch API
- Browser localStorage

## API

This project uses [JSONPlaceholder](https://jsonplaceholder.typicode.com/) as its public REST API.

API endpoint:

`https://jsonplaceholder.typicode.com/posts`

## Project Structure

```text
web-data-explorer/
│
├── index.html
├── style.css
├── app.js
└── README.md
```

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/web-data-explorer.git
   ```

2. Open the project folder in Visual Studio Code.

3. Open `index.html` using the Live Server extension.

4. Explore the dashboard, search for records, and manage your favourites.

## Learning Outcomes

Through this project, I practised:

- Connecting a web application to a public REST API.
- Working with asynchronous JavaScript functions.
- Managing application data using a central state object.
- Dynamically generating HTML content.
- Implementing event delegation.
- Using `JSON.stringify()` and `JSON.parse()` for browser data persistence.

## Project Preview

Screenshots of the application can be added to the `screenshots/` folder.

## Author

Developed as part of a JavaScript assessment.

**Web Data Explorer** | JavaScript Project
