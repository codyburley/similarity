# Similarity API

Similarity is an API designed to compare two strings and return a similarity rating.

## Live Site

Deployed site at [Similarity API](https://similarity-git-main-codyburley.vercel.app/) using Vercel.

## Features

- Rate Limited API routes
- Protection of sensitive routes
- Google authentication
- Typescript
- A complete API key system to create & revoke user keys
- Radix UI Primitives
- Tailwind CSS
- Fonts with next/font
- Icons from Lucide
- Beautiful dark mode with next-themes
- Class merging with taiwind-merge
- Animation with tailwindcss-animate
- Conditional classes with clsx
- Variants with class-variance-authority

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`NEXTAUTH_SECRET`

`NEXTAUTH_URL`

`GOOGLE_CLIENT_ID`

`GOOGLE_CLIENT_SECRET`

`DATABASE_URL`

`OPENAI_API_KEY`

`REDIS_URL`

`REDIS_SECRET`

## Lessons Learned

This was a practice project in order to reinforce best practices with TypeScript and backend development, and to learn NextJS 13 and TailwindCSS.

#### Frontend Lessons

- How to use TailwindCSS and manage themes in combination with next-themes
- A multitude of TypeScript best practices and features, simple things like a custom TypeScript component code snippet to more complex interface management and features of NextJS
- How NextJS differs a lot from React, being my first project in NextJS there was a lot of growing pains but for every pain there was even more positives like built in routing

#### Backend Lessons

- How to use NextJS to build an API, this was a really fun experience to be able to manage both the frontend and backend in one project so cleanly
- Prisma made working with the database a dream
- Being my first full-stack application of this size in quite sometime, this project helped with my MySQL and database management
