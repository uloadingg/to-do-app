# To-Do List App

A lightweight task tracker that runs in the browser and remembers your list between visits.

## Features

- **Add tasks:** type a task and submit it; blank entries are ignored and extra spaces are trimmed
- **Mark tasks complete:** tick the checkbox to cross a task off
- **Delete tasks:** remove any single task with the ✕ button
- **Clear completed:** remove every finished task in one click
- **Live counter:** shows how many tasks are still open
- **Saves automatically:** tasks are stored in the browser's `localStorage`, so your list is still there after you close or refresh the page

## Built with

- HTML, CSS and JavaScript (no frameworks)
- GitHub Pages for hosting

## How it works

Each change (adding, completing or deleting a task) updates the list on screen and saves the full list to `localStorage`. When the page loads, the app reads that saved list back and rebuilds it.

## Roadmap

- Filter views: All, Active and Completed
- Edit a task's text after it's added
- Due dates and priority labels

## Run it locally

Clone the repo and open `index.html` in any browser. No build step is needed.
