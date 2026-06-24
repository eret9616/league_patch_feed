# League of Legends Patch Notes RSS Feed

**English** · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt-BR.md)

An RSS feed for League of Legends patch notes, deployed on Vercel.

## Features

- Automatically scrapes the official League of Legends patch notes
- Generates an RSS feed
- Supports images and detailed descriptions

## Deployment

1. Fork this repository
2. Import your repository on [Vercel](https://vercel.com)
3. Once deployed, your RSS feed URL will be: `https://your-domain/api/rss`

## Local Development

```bash
# Install dependencies
npm install

# Run locally
npm run dev
```

## Tech Stack

- Node.js
- Axios
- Cheerio
- RSS
- Vercel Serverless Functions

## Notes

- Please make sure to comply with the terms of use of the official League of Legends website
- It is recommended to set a reasonable request interval to avoid frequent requests
