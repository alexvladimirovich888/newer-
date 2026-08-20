# Stacks Bowers Auctions

Static Web Application (SPA / AngularJS + Bootstrap).

## Local Development
```bash
npm install
npm run dev
```
Open `http://localhost:3000` in your browser.

## Deploying to Vercel
1. Push all files (including `vercel.json` and updated `index.html`) to your GitHub repository.
2. In **Vercel Dashboard**:
   - Click **Add New Project** -> Import your GitHub repository.
   - **Framework Preset**: Select **Other**.
   - **Root Directory**: `./` (leave default).
   - **Build Command**: `npm run build` or leave default.
   - **Output Directory**: Leave empty / default (root).
3. Click **Deploy**.
