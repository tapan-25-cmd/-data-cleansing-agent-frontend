# Data Cleansing Agent Frontend

React and Vite chat interface for uploading, monitoring, previewing, and downloading UOM-cleansed Excel workbooks.

## Local setup

```bash
npm install
cp .env.example .env
npm run dev
```

Open `http://localhost:5173`. With `VITE_API_BASE_URL` empty, Vite proxies `/api` requests to `http://localhost:8000`.

For a separately deployed backend, set the public backend origin before building:

```dotenv
VITE_API_BASE_URL=https://api.example.com
```

The backend must allow the frontend origin through its `FRONTEND_ORIGIN` setting.

## Validation

```bash
npm run build
```

