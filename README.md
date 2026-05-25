# Physical AI Expo — thephysicalaiexpo.com

Website for the Physical AI Expo, London Q3 2027.

## Stack

Single-file static site — `index.html` only. No build step, no dependencies, no framework. Deployed via Vercel.

## Repo structure

```
physical-ai-expo/
├── index.html        ← the entire website
├── vercel.json       ← Vercel config (headers, redirects, clean URLs)
└── README.md
```

## Deploying

Connected to Vercel. Every push to `main` auto-deploys to [thephysicalaiexpo.com](https://thephysicalaiexpo.com).

Preview URLs are generated for every commit — check Vercel dashboard before going live.

## Updating the site

1. Edit `index.html`
2. Commit to `main`
3. Vercel deploys automatically (~20 seconds)

## DNS

Domain registered on GoDaddy. DNS records point to Vercel:
- `A` record → Vercel IP (76.76.21.21)
- `CNAME` www → cname.vercel-dns.com

## Contact

Physical AI Expo — VC Eleven  
hello@thephysicalaiexpo.com
