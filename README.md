# Boyd

A movie site built with Vite and React.

## Project Structure

```
index.html
src/
  ├── main.jsx
  ├── App.jsx
```

## Environment Setup

Create a `.env.local` file in your project root:

```
VITE_TMDB_KEY=your_tmdb_api_key_here
```

## Usage

Access your API key in your app:

```javascript
const API_KEY = import.meta.env.VITE_TMDB_KEY;
```
