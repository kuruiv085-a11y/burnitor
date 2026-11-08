# Vii Trader Demo

Vii Trader is a responsive, English-language paper-trading interface for exploring a visual digit-strategy workflow. It includes Over, Under, Even, Odd, Matches, and Differs controls; an illustrative Volatility index list (including 1-second variants); duration input in seconds; demo stake controls; strategy blocks; and local-only simulation history.

## Important

This first build is a front-end simulation only. It does not connect to Deriv, read live prices, request credentials or API tokens, or place trades. Simulated outcomes are random and are not quotes, predictions, or a representation of expected returns. The market list is illustrative, and actual product availability must be confirmed through official Deriv resources before any future integration.

## Deploy on Vercel

1. Import the GitHub repository `kuruiv085-a11y/burnitor` into Vercel and select branch `copilot/vii-trader-vercel`.
2. Keep the project root at the repository root. The included `vercel.json` configures `npm run build`, the `dist` output directory, and routes requests to the Vii Trader demo page.
3. Use the repository's Node.js 22+ requirement. No Vii Trader environment variables are needed for this demo.
4. Deploy. The page is served from `public/vii-trader.html`.

The repository also contains its original application source; the Vercel rewrite serves the Vii Trader demo at the deployed site routes.
