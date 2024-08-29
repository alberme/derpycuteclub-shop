# derpycuteclub

An online store bootstrapped with Hydrogen - Shopify’s stack for headless commerce. Hydrogen is designed to dovetail with [Remix](https://remix.run/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/1579e178-8cb8-4af7-80cf-dcd594eb2aef/deploy-status)](https://app.netlify.com/sites/derpycuteclub/deploys)

- [Check out Hydrogen docs](https://shopify.dev/custom-storefronts/hydrogen)
- [Get familiar with Remix](https://remix.run/docs/)

## Getting started

**Requirements:**

- Node.js version 18.0.0 or higher
- Netlify CLI 17.0.0 or higher

```bash
npm install -g netlify-cli@latest
```

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/netlify/hydrogen-template#SESSION_SECRET=mock%20token&PUBLIC_STORE_DOMAIN=mock.shop)

To create a new project, either click the "Deploy to Netlify" button above, or run the following command:

```bash
npx create-remix@latest --template=netlify/hydrogen-template
```

## Local development

```bash
npm run dev
```

## Building for production

```bash
npm run build
```
