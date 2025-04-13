This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Dependencies

- Clerk (Authentication service) - http://clerk.com/
- ShadCN/UI (Open source components built on tailwind) - https://ui.shadcn.com/docs
- Lucide React (Icon library / comes with ShadCN/UI out of the box) - https://lucide.dev/guide/packages/lucide-react
- Radix UI - Radix UI (component library) - https://www.radix-ui.com/
- react-themes - dark mode and system theme support
- react-hot-toast - Notifications for React apps - https://react-hot-toast.com/docs
- Prisma - ORM for database schema management and migrations - https://www.prisma.io/react-server-components
- @uploadthing/react - File uploads for React - docs.uploadthing.com

## Environment variables

An example .env file can be found in .env.example

```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
DATABASE_URL=
UPLOADTHING_TOKEN=
```

## Database

Setup your own free serverless database provided by Neon. Sign up at https://neon.tech/

## Production server

I'm using Vercel to host this application

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

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## ShadCn/UI

### Adding new dependencies.

npx shadcn@latest add <component-name>

A full list of components is available here 

https://ui.shadcn.com/docs/components

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
