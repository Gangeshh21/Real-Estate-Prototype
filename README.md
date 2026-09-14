# EstateHub Real Estate Prototype

A Vercel-ready React + TypeScript + Vite prototype for a client demo.

## Run locally
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## Deploy to Vercel
1. Push this folder to GitHub.
2. Import the repository into Vercel.
3. Framework: Vite (usually auto-detected).
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy.

`vercel.json` is included so direct routes work on refresh.

## Demo Admin
Email: admin@realestate.com
Password: admin123

## Prototype behavior
- Registration/login is simulated with localStorage.
- Properties are stored in localStorage.
- Monthly/yearly subscriptions use a mock checkout.
- No real money is charged.
- Property details are unlocked after the mock payment.
- Admin can add/edit/delete demo properties.
- This is a frontend prototype, not a production backend.
