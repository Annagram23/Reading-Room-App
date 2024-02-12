# The Blurb Presents…

## The Reading Room

### The Reading Room is a mobile app designed to encourage good reading habits in children of Primary School Age; it works as a digital reading record.

Upon logging in, the reader is reminded of what they last read and what they noted about it. Children are then encouraged to set a stopwatch for their reading session, to record its length. Afterwards, they are prompted to write notes (with support from a parent or educator) and are then rewarded for their efforts with a prize - a choice of a colourful accessory for their monster avatar.

Table of Contents

1. Problem Statement

2. Idea / Solution

3. Dependences / Limitations

4. Future Scope

5. Setting up a Local Environment and Tech Stack

6. Authors

7. Acknowledgements
 
## Problem Statement

Educators and Parents are looking to find ways to support children who may struggle to form good reading habits on their own.

In UK Primary Schools, children are encouraged to develop their reading skills through daily reading sessions at home and 1:1 reading sessions in school with a teacher or teaching assistant. All too often, a reading record isn’t filled in, or is left at home/school, causing problems when a child next comes to read and doesn’t know where they got up to; they perhaps don’t remember what happened in the book last time. Furthermore, reading might not be that enticing to children when there are other things they could spend their time doing e.g. playing on an electronic device. 

## Idea / Solution

Our solution to this problem was to build a child-friendly, simple app that encourages children to read through its colourful interface, option to challenge oneself with a timer, a monster avatar and a rewards room. 

## Dependences / Limitations

Initially, our app ideas covered the entire population - our research was with a diverse demographic and we tried to tailor an app to everyone. We found that the scope was far too big and we were limited by time (4 weeks to build the app). We narrowed our focus down to Primary-aged children and carried out more research with parents and educators.

We are using a free tier of Vercel to host our app, which may result in the app being slow to load

## Future Scope

Our next sprint goal would be to display all data recorded by the app user, so that they can see their progress over time. 

Following that, we would develop the app further by creating a kind of ‘rewards shop’ with different coins needed for different items; this may further motivate children to read to earn top-level prizes.


## Setting up a Local Environment and Tech Stack

We used Visual Studio Code as our source code editor to work locally and installed NodeJS and its relevant packages - we ran the server using ‘npm run dev’ in the terminal to check its function.

As a team, we researched our tech stack and decided to use the NextJS React framework because of its SSR (server-side rendering) and built-in routing system.

We decided to use the popular Chakra UI, which is a react component library in our front-end because it was easy to navigate and had a wide variety of components to use and adapt. 

We used Supertest Node JS library to test our code and make HTTP requests and assertions.

As a team, we decided to use Github Flow to work in small groups and independently and add regular commits to our Github repository; we deployed the app regularly to ensure it looked and functioned as intended. 

## Authors
- Anna [Anna](https://github.com/Annagram23)
- Jacob[Jacob](https://github.com/jacobfield/jacobfield)
- Jordan[Jordan](https://github.com/Jordan-Walters-23)
- Marika[Marika](https://github.com/marikaferrari)
- Melissa[Melissa](https://github.com/melvinJD)
- Mickey[Mickey](https://github.com/mickeymarse/mickeymarse)

## Acknowledgements
A big thank you to the School of Code for their support and guidance!
[title](https://github.com/SchoolOfCode)




This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
