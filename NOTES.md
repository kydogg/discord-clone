organization folder structure that does not affect the route
() put the title of what you want in ()

you can create hte layout in the same organizational folder and it will adopt the styling of the parent. peep the login example of 31 within the tutorial if you want to reference back to this!!!

1. Setting up Cleark
   https://clerk.com/docs/quickstarts/nextjs

- add application
- choose the authentication we want
- create an .env file
- paste the keys into .env file
- npm install @clerk/nextjs
- mount <ClerkProvider /> into main layout
  app > layout.tsx
- create middleware.ts
