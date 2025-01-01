1|[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fcommerce&project-name=commerce&repo-name=commerce&demo-title=Next.js%20Commerce&demo-url=https%3A%2F%2Fdemo.vercel.store&demo-image=https%3A%2F%2Fbigcommerce-demo-asset-ksvtgfvnd.vercel.app%2Fbigcommerce.png&env=COMPANY_NAME,SHOPIFY_REVALIDATION_SECRET,SHOPIFY_STORE_DOMAIN,SHOPIFY_STOREFRONT_ACCESS_TOKEN,SITE_NAME,TWITTER_CREATOR,TWITTER_SITE)
2|
3|# Next.js Commerce
4|
5|A high-performance, server-rendered Next.js App Router ecommerce application.
6|
7|This template uses React Server Components, Server Actions, `Suspense`, `useOptimistic`, and more.
8|
9|## Providers
10|
11|This repository is actively maintaining a Shopify version.
12|
13|Vercel is happy to partner and work with any commerce provider to help them get a similar template up and running and listed below. Alternative providers should be able to fork this repository and swap out the `lib/shopify` file with their own implementation while leaving the rest of the template mostly unchanged.
14|
15|- Shopify (this repository)
16|- [BigCommerce](https://github.com/bigcommerce/nextjs-commerce) ([Demo](https://next-commerce-v2.vercel.app/))
17|- [Ecwid by Lightspeed](https://github.com/Ecwid/ecwid-nextjs-commerce/) ([Demo](https://ecwid-nextjs-commerce.vercel.app/))
18|- [Geins](https://github.com/geins-io/vercel-nextjs-commerce) ([Demo](https://geins-nextjs-commerce-starter.vercel.app/))
19|- [Medusa](https://github.com/medusajs/vercel-commerce) ([Demo](https://medusa-nextjs-commerce.vercel.app/))
20|- [Saleor](https://github.com/saleor/nextjs-commerce) ([Demo](https://saleor-commerce.vercel.app/))
21|- [Shopware](https://github.com/shopwareLabs/vercel-commerce) ([Demo](https://shopware-vercel-commerce-react.vercel.app/))
22|- [Swell](https://github.com/swellstores/verswell-commerce) ([Demo](https://verswell-commerce.vercel.app/))
23|- [Umbraco](https://github.com/umbraco/Umbraco.VercelCommerce.Demo) ([Demo](https://vercel-commerce-demo.umbraco.com/))
24|- [Wix](https://github.com/wix/nextjs-commerce) ([Demo](https://wix-nextjs-commerce.vercel.app/))
25|- [Fourthwall](https://github.com/FourthwallHQ/vercel-commerce) ([Demo](https://vercel-storefront.fourthwall.app/))
26|
27|## Running locally
28|
29|You will need to use the environment variables [defined in `.env.example`](.env.example) to run Next.js Commerce. It's recommended you use environment variables for this, but a `.env` file is all that is necessary.
30|
31|> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control your Shopify store.
32|
33|1. Install CLI: `npm i -g vercel`
34|2. Link local instance with your accounts (creates `.vercel` directory): `vercel link`
35|3. Download your environment variables: `vercel env pull`
36|
37|```bash
38|pnpm install
39|pnpm dev
40|```
41|
42|Your app should now be running on [localhost:3000](http://localhost:3000/).
43|
44|## Integration Guide
45|
46|You can use this comprehensive [integration guide](https://vercel.com/docs/integrations/ecommerce/shopify) with step-by-step instructions on how to configure Shopify as a headless CMS using Next.js Commerce as your headless Shopify storefront.
