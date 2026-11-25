# Cardápio Online Frontend

A React and TypeScript interface that displays menu items as cards and adds items through a form. It uses Vite, Axios and TanStack Query. The form sends a title, an image URL and a numeric price, then refreshes the menu after a successful save.

## Run locally

1. Start the [Cardápio Online API](https://github.com/MatheusHVM/Card-pio-Online) from its `master` branch. The frontend calls `GET /food` and `POST /food` at `http://localhost:8080`. Use an integer price with the Java API.
2. With Node.js and npm installed, run these commands from this repository:

   ```sh
   npm ci
   npm run dev -- --port 5173 --strictPort
   ```

3. Open `http://localhost:5173`. The backend allows CORS requests from that origin.

Run `npm run build` to type-check and build the frontend. The output goes to `dist/`.
