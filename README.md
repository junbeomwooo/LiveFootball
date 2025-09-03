# Fotbold: Live Football Scores & Comprehensive Football Info

![WEBSITE](./public/fotbold_mockup.jpg)
![WEBSITE](./public/fotbold_mockup_dark.jpg)

• [Visit the website here](https://fodbold.vercel.app/en)

<br /> <br />
## Introduction
This website uses the API-Football platform to provide real-time football scores and information on matches, players, teams, and leagues.

It supports English, Danish,and Korean, with both dark and light themes for an optimized user experience. 

This website uses the free version of the API, allowing a total of 100 API requests per day.

Inspired by FotMob, it offers comprehensive and accessible football data.

<br /> <br />
## Development Environment
• Client : HTML, Next.js, Tailwind CSS

• Deployment environment : Vercel

• Design : Adobe Illustrator, Adobe Photoshop
<br /> <br />
## Project structure  
```
.
├── README.md
├── components.json
├── darkfieldMobile.png
├── messages/
│   ├── da.json
│   ├── en.json
│   └── ko.json
├── next-env.d.ts
├── next.config.mjs
├── package-lock.json
├── package.json
├── postcss.config.mjs
├── public/
│   ├── example.js
│   ├── fotbold_mockup.jpg
│   ├── fotbold_mockup_dark.jpg
│   ├── img/
│   │   └── ...
│   ├── next.svg
│   └── vercel.svg
├── src/
│   ├── app/
│   │   └── [locale]/
│   │       ├── (home)/
│   │       │   ├── loading.tsx
│   │       │   └── page.tsx
│   │       ├── (leagues)/
│   │       │   └── leagues/[id]/[league]/
│   │       │       ├── matches/
│   │       │       ├── overview/
│   │       │       ├── playoff/
│   │       │       ├── stats/
│   │       │       └── tables/
│   │       ├── (matches)/matches/[vs]/[id]/
│   │       ├── (players)/players/[id]/[name]/
│   │       └── (teams)/teams/[id]/[name]/
│   │           ├── fixture/
│   │           ├── overview/
│   │           ├── squad/
│   │           ├── tables/
│   │           └── transfer/
│   │       ├── StoreProvider.tsx
│   │       ├── layout.tsx
│   │       └── provider.tsx
│   ├── components/
│   │   ├── fixtures/
│   │   ├── footer/
│   │   ├── header/
│   │   ├── league/
│   │   ├── main/
│   │   ├── players/
│   │   └── teams/
│   ├── constants/
│   │   └── api.ts
│   ├── i18n.ts
│   ├── lib/
│   │   ├── features/
│   │   │   ├── fixtureSlice.tsx
│   │   │   ├── leagueSlice.tsx
│   │   │   ├── locationSlice.tsx
│   │   │   ├── playerSlice.tsx
│   │   │   └── teamsSlice.tsx
│   │   ├── ...
│   ├── middleware.ts
│   ├── styles/
│   │   └── global.css
│   └── types/
│       └── colorthief.d.ts
├── tailwind.config.ts
└── tsconfig.json
```

<br /> <br />
## APIs Used  
• API-Football: Provides real-time data on football matches, teams, players, and leagues.  