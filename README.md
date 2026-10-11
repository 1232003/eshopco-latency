# eShopCo latency API

Deploy from this folder with `vercel --prod` (after authenticating with `vercel login`).
POST to `https://YOUR-PROJECT.vercel.app/api` with JSON `{"regions":["apac","emea"],"threshold_ms":163}`.
The p95 uses linear interpolation (the NumPy default). Uptime is in percentage points as stored in the telemetry.
