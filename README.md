# :point_right: Introduction

Tradeo is an opensource financial project aiming to provide a clean and snappy user interface to view stock information of companies in (soft) real time.
The project is written in JavaScript/TypeScript leveraging full stack framework NextJS and deploying on Vercel hosting platform.



## :zap: Tech Stack

<details open>
<summary>Client</summary>

* Typescript
* Tailwind CSS
* Clerk
* Shadcn-UI
* Aceternity-UI
* Chart.JS

</details>

<details open>
<summary>Server</summary>

* Typescript
* NextJS
* Tanstack Query
* ChatGPT-3,5 Turbo

</details>

<details open>
<summary>Database</summary>

* Postgresql
* Supabass
* Prisma

</details>

<details open>
<summary>Hosting</summary>

* Vercel

</details>

## :pushpin: Features 

- ChatGPT-3.5 Bot
- Light/dark mode toggle
- Buy/sell stocks 
- Add/remove stocks from watchlist
- View transaction records
- Add/remove customizable cards
- Deposit/withdraw from trading account
- Authentication
- Search stocks
- View stock prices & company history

## :key: Environment Variables



`YAHOO_FINANCE_STOCK_SUMMARY`

`NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`

`CLERK_SECRET_KEY`

`NEXT_PUBLIC_CLERK_SIGN_IN_URL`

`NEXT_PUBLIC_CLERK_SIGN_UP_URL`

`NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL`

`NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL`

`DATABASE_URL`

`DIRECT_URL`

# :hammer: Build

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
bun run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.


Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Project Layout

```
└──./
    ├──app/
    │   ├──(auth)/
    │   │   ├──(routes)/
    │   │   │   ├──sign-in/
    │   │   │   │   └──[[...sign-in]]/
    │   │   │   └──sign-up/
    │   │   │       └──[[...sign-up]]/
    │   ├──(landing-page)/
    │   ├──(root)/
    │   │   ├──(routes)/
    │   │   │   ├──chat/
    │   │   │   │   ├──components/
    │   │   │   ├──dashboard/
    │   │   │   │   ├──components/
    │   │   │   │   │   ├──accordion/
    │   │   │   │   │   ├──account/
    │   │   │   │   │   ├──bank/
    │   │   │   │   │   ├──not-use/
    │   │   │   │   │   ├──table/
    │   │   │   └──market/
    │   │   │       ├──components/
    │   │   │       │   ├──company-profile/
    │   │   │       │   ├──company-table/
    │   │   │       │   ├──products/
    │   │   │       │   └──transaction/
    │   ├──api/
    │   │   ├──account/
    │   │   ├──chat/
    │   │   ├──dashboard-watchlist/
    │   │   ├──market-watchlist/
    │   │   └──portfolio/
    ├──components/
    │   ├──aceternity-ui/
    │   ├──shadcn-ui/
    │   └──ui/
    ├──constants/
    ├──hooks/
    ├──lib/
    ├──prisma/
    ├──providers/
    ├──public/
    │   ├──avatars/
    │   ├──employees/
    │   ├──logos/
    │   ├──products/
    ├──scripts/
    ├──types/
    └──utils/
```





