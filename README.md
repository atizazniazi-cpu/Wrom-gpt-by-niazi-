# MIAN X NIAZI AI Chat

## Run locally
1. Install Node.js 18+.
2. Copy `.env.example` to `.env`.
3. Put your WormGPT API key in `WORMGPT_API_KEY`.
4. Run `npm install`.
5. Run `npm start`.
6. Open `http://localhost:3000`.

## Deploy
Set the environment variable `WORMGPT_API_KEY` in your hosting dashboard. Do not put the secret key in `public/index.html`.

The backend sends POST requests to:
`https://api.wormgpt.pw/v1/chat/completions`
with Bearer authentication and the messages array.
