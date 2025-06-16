# University-Search-App

This is a simple web app that allows users to search for colleges by country using an API and displays the results in a responsive list.

## Features

- Centered heading, input box, and search button.
- Placeholder text centered inside the input field.
- Makes API calls to fetch college data based on user input.
- Displays search results dynamically in a flexible, evenly spaced list.
- Responsive and clean UI with minimal CSS styling.
- Uses Axios library for HTTP requests.

## Usage

1. Open `index.html` in a modern web browser.
2. Enter the country name in the input box.
3. Click the **Search** button.
4. The app will make an API call to fetch colleges in the specified country.
5. The results will be displayed dynamically below the input field in a list format.

## Files

- `index.html` - Main HTML structure of the page.
- `style.css` - CSS styles for layout and design.
- `app.js` - JavaScript code handling API calls and dynamic rendering of results.

## API

- The app uses a public or custom API endpoint to retrieve college information.
- Axios CDN is included in the project for making HTTP requests.

## How to Customize

- Modify the API endpoint and parameters in `app.js` as needed.
- Adjust styles in `style.css` for layout and design changes.
- Extend functionality to handle errors, loading states, or pagination.

## Dependencies

- Axios (included via CDN): [https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js](https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js)

## Example HTML structure

```html
<div class="box">
  <input placeholder="Enter country" />
  <button>Search</button>
  <ul id="list"></ul>
</div>
