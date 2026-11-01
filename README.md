# CampusEats Catalogue

A small web app built for the CS543 Web Services Node & Express tutorial.
A web page talks to a REST API (Node + Express) that holds a menu of dishes.

## Features

- List all dishes (GET /items)
- Get one dish by id, or a 404 if it is not found (GET /items/:id)
- Add a new dish with a form (POST /items)

## Tech used

- Node.js
- Express
- HTML, CSS, JavaScript (fetch)

## How to run

1. Install Node.js (v18 or newer).
2. Clone this repository and open the folder:

   ```
   git clone https://github.com/Ankitbuildsthings/catalogue.git
   cd catalogue
   ```

3. Install the packages:

   ```
   npm install
   ```

4. Start the server:

   ```
   node server.js
   ```

5. Open http://localhost:3000 in your browser.

## Project structure

```
catalogue/
  server.js        - Express REST API
  package.json
  public/
    index.html     - web page (fetch + form)
    style.css      - styling
```

## Note

Data is stored in memory, so added dishes disappear when the server restarts.
A database will be added in a later lecture.