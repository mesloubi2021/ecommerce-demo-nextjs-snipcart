This is a [Next.js ecommerce template](https://nextjs.org/) bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

This example showcases a Next.js ecommerce using [DatoCMS](https://www.datocms.com/) as the data source, and [Snipcart](https://snipcart.com/), to manage the shopping cart.

The purpose of this repo is to have a quick start reference that can be set up with the "one-click" button below.

Here is what the result looks like

![Ecommerce next.js preview](https://www.datocms-assets.com/205/1633080163-datocms-docs-2021-10-01-at-11-22-22.png?fm=webp&w=950)

## Deploy the demo with DatoCMS

You can install this demo right away by clicking on this button:

[![Deploy with DatoCMS](https://dashboard.datocms.com/deploy/button.svg)](https://dashboard.datocms.com/deploy?repo=datocms/ecommerce-nextjs-snipcart:main)

The wizard will create a new DatoCMS project, will clone the demo repository on your GitHub, and will deploy it on Netlify or Vercel.

### Deploying to Netlify

For the demo to work you need to go in your Netlify project > settings > build & deploy > environment variables, and create a new env variable called "NEXT_PUBLIC_SNIPCART_API_KEY". Paste in the value field, the key you find in your Snipcart project > account settings > API keys > public API key.

### Deploying to Vercel

For the demo to work you need to go in your Vercel project > settings > environment variables, and create a new variable called "NEXT_PUBLIC_SNIPCART_API_KEY". Paste in the value field, the key you find in your Snipcart project > account settings > API keys > public API key.

# Development

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Adding Snipcart and DatoCMS

Create a `.env` file by copying the `.env.sample` file. Add your Snipcart API key that you get after registration, and your Read-only DatoCMS API key that you can get from the admin area in your DatoCMS project, and your Snipcart API key that you can find in your account settings > API keys

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
