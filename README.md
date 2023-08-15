# Programmable Wallets Test Server

Here is a test server designed to help kickstart your journey with Circle's Programmable Wallets. Our server implementation efficiently simulates a sequence of API calls by consolidating three POST requests into a single call. This consolidated call conveniently provides your mobile app with the user token, secret key, and challenge ID. Additionally, we've also included a separate API to refresh the user token expiration. 

## Getting Started

First, retrieve an API key from your [Circle Developer account](https://console.circle.com/).

Second, congifure your environment variables in the .env file located in the root directory. The CIRCLE_BASE_URL is https://api.circle.com/v1/w3s.
```bash
CIRCLE_API_KEY=""
CIRCLE_BASE_URL="https://api.circle.com/v1/w3s"
```

Third, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
