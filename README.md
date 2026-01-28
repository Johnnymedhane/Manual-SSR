# 20-manual-ssr

A minimal example demonstrating manual server-side rendering (SSR) with React.

- Serves pre-rendered HTML from `index.html`.
- Hydrates the client UI via `client.js`.
- Uses `@babel/register` to enable JSX on the server during development.

Run the server:

```powershell
node --watch start.js
```

Open http://localhost:8000 in your browser.
