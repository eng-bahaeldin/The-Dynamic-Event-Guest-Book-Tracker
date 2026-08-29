# The Dynamic Event Guest Book & Tracker

A simple front-end web app for tracking event guests and fetching a random quote from an API.

## Features
- Add guests to a dynamic attendee list
- Automatically update the total attending count
- Display a random quote from a public API
- Show a loading state while fetching the quote
- Show an error message if the network request fails

## Files
- `index.html` – page structure, styling, and JavaScript logic

## How to run
1. Open `index.html` in a browser.
2. Type a guest name and click **Add**.
3. Click **Get New Quote** to fetch a random quote.

## Notes
- The quote feature uses the browser `fetch()` API.
- If the request fails, the app displays:
  `Failed to load quote. Check your internet connection.`
