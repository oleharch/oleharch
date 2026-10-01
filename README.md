<h1 align="center">Oleh Molchanov</h1>

<p align="center">
  <strong>Shopify Developer</strong> · React / Next.js · WordPress · Kyiv, Ukraine<br>
  6+ years in web development, 2+ years building Shopify stores
</p>

<p align="center">
  <a href="https://oleh-molchanov.vercel.app">Portfolio and CV</a> ·
  <a href="https://www.linkedin.com/in/olehmolchanov/">LinkedIn</a> ·
  <a href="mailto:oleg.molchanow@gmail.com">oleg.molchanow@gmail.com</a>
</p>

<table align="center">
  <tr>
    <th align="center">Shopify</th>
    <th align="center">Frontend</th>
    <th align="center">WordPress</th>
  </tr>
  <tr>
    <td align="center">
      <img alt="Shopify" src="https://img.shields.io/badge/Shopify-95BF47?logo=shopify&logoColor=white">
      <img alt="Liquid" src="https://img.shields.io/badge/Liquid-1E1E1E?logo=shopify&logoColor=95BF47">
      <img alt="Dawn" src="https://img.shields.io/badge/Dawn-OS%202.0-1E1E1E">
      <img alt="GraphQL" src="https://img.shields.io/badge/Admin%20API-E10098?logo=graphql&logoColor=white">
    </td>
    <td align="center">
      <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000">
      <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
      <img alt="React" src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB">
      <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white">
      <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=white">
      <img alt="Sass" src="https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white">
    </td>
    <td align="center">
      <img alt="WordPress" src="https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=white">
      <img alt="WooCommerce" src="https://img.shields.io/badge/WooCommerce-96588A?logo=woocommerce&logoColor=white">
      <img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white">
      <img alt="ACF" src="https://img.shields.io/badge/ACF-00A0D2">
    </td>
  </tr>
</table>

I help DTC brands get a Shopify store that is fast, easy for the merchant to edit and easy for the
customer to buy from on a phone. Custom themes in Liquid, Figma designs turned into pixel-perfect pages,
apps and tracking wired in, stores migrated without data loss. For complex product UIs I work in React
and Next.js, and I still build custom WordPress and WooCommerce sites when that is the right tool.

## Shopify

| Area | What I do | Tools |
|---|---|---|
| **Themes** | Custom themes from scratch and customization of Dawn and paid themes. Merchant-editable sections and blocks with a clean schema, metafields and metaobjects for content, section groups, JSON templates. | Liquid, Online Store 2.0, Dawn, Theme Check, Shopify CLI |
| **Figma to store** | Pixel-perfect, mobile-first builds of product, collection, landing and content pages. The phone layout is designed, not shrunk. | Figma, CSS, Web Components |
| **Product and landing pages** | Pages built for conversion: clear buy box, sticky add to cart, upsells, FAQ with structured data, trust blocks, fast media. | Liquid, Section Rendering API, JSON-LD |
| **Custom features** | Quizzes, configurators, product options, bundles, age gates, store availability per location, cart logic within what the platform allows without Plus. | Liquid, JavaScript, Ajax Cart API, metafields |
| **Apps and integrations** | Setup and theme integration of marketing, reviews and subscription apps. Custom app work: OAuth install, Billing API, webhooks, theme app extensions. | Klaviyo, Judge.me, ReCharge, GemPages, Admin API (GraphQL), Node.js |
| **Speed** | Core Web Vitals audits and fixes: image sizing, deferred scripts, font loading, third-party cleanup. 90+ PageSpeed as the baseline. | Lighthouse, PageSpeed Insights |
| **Tracking** | Correct events for ads and analytics, server-side where possible. | GA4, Google Tag Manager, Meta Pixel, Conversions API |
| **Store setup and migrations** | Stores set up from zero: catalog, collections, navigation, payments, shipping, markets and languages. Migrations to Shopify with products, customers and orders kept intact. | Shopify admin, CSV imports, Admin API |

## React and Next.js

Complex product UIs when a store or a client needs more than a theme: SaaS front ends, admin panels, CRMs and dashboards.
React 19, Next.js (App Router), TypeScript, TanStack Query, Zustand, Tailwind CSS, shadcn/ui, next-intl, Vitest and Playwright.
I work next to a backend team on Node.js, Prisma and GraphQL APIs.

## WordPress and WooCommerce

Custom themes from scratch with ACF and custom post types registered in code, WooCommerce cart and checkout
customization through hooks and template overrides, multilingual sites on Polylang or WPML, lead forms with
webhooks to CRM, deploys from GitHub Actions.

## Featured work

| Project | What it is | Built with |
|---|---|---|
| [dawn-sections](https://github.com/oleharch/dawn-sections) | Drop-in sections for Dawn and any OS 2.0 theme: age gate, sticky add to cart, FAQ with JSON-LD. One Liquid file each, Theme Check clean, no apps. | Liquid, Web Components |
| [learn-liquid](https://github.com/oleharch/learn-liquid) | Interactive Liquid trainer for Shopify developers, in Ukrainian: 18 lessons with auto-checked tasks, a 92-page reference, a live sandbox and 131 interview questions. | React 19, TypeScript, Vite, LiquidJS |
| [react-modal-context](https://github.com/oleharch/react-modal-context) · [demo](https://react-modal-context.vercel.app) | Modals by id: `ModalProvider`, a `useModal` hook and a `<Modal>` on the native `<dialog>`. Zero dependencies, tested. | React, TypeScript, Vitest |
| [Accordion](https://gist.github.com/oleharch/021ef0542e9b22711043febcd4391713) | Dependency-free accordion with data attributes and `max-height` animation. | Vanilla JS |

Client stores and apps are under NDA. Public ones and more details are in the [portfolio](https://oleh-molchanov.vercel.app).

## How I build

- Liquid first. A section with a schema the merchant can edit beats hard-coded markup and beats an app.
- Theme code goes through Shopify Theme Check. Scripts are deferred custom elements, styles are scoped to the section.
- Figma to pixel-perfect, mobile-first. The phone layout is designed, not shrunk.
- Every page gets a PageSpeed check before launch. 90+ is the baseline, not the goal.
- Clean, maintainable code and short READMEs, so the next developer can take over without a call.
- Clear communication, realistic estimates, on-time delivery. Quick fixes and long-term work are both fine.

## Experience

- **Shopify Developer**, Landing.ua (digital agency, Kyiv), Jun 2024 to present
- **Frontend Developer**, Unio-IT, Feb 2022 to May 2024
- **Freelance Web Developer**, Freelancehunt, Jun 2020 to Feb 2022: 26 reviewed projects, 5.0 rating, 100% success

M.Sc. in Software Engineering, Zaporizhzhia Polytechnic National University.

<p align="center">
  <img alt="GitHub stats" height="165" src="https://github-readme-stats.vercel.app/api?username=oleharch&show_icons=true&count_private=true&hide_border=true&theme=transparent">
  <img alt="Top languages" height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=oleharch&layout=compact&hide_border=true&theme=transparent">
</p>

## Open to

Shopify Developer roles: office in Kyiv, hybrid or remote. Write to
[oleg.molchanow@gmail.com](mailto:oleg.molchanow@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/olehmolchanov/).
