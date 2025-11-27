# Donation Info for Taipo Fire in Hong Kong

A simple webpage that consolidates multiple donation links.

## Deploy to Cloudflare Pages

1. Push this project to a GitHub repository

2. In Cloudflare Dashboard:
   - Go to **Pages** > **Create a project**
   - Connect your GitHub repository
   - Configure:
     - **Framework preset**: None
     - **Build command**: (leave empty)
     - **Build output directory**: `/` (root directory)

3. Click **Save and Deploy**

## Local Development

Simply open the `index.html` file locally, or use any static file server:

```bash
# Using Python
python3 -m http.server 8000

# Or using Node.js http-server
npx http-server
```

Then open `http://localhost:8000` in your browser

## File Structure

- `index.html` - Main webpage file
- `links.json` - Donation links data
- `README.md` - Documentation

## Modify Links

Edit the `links.json` file to add or modify donation links.
