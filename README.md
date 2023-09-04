This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## ecommerce-admin

### Stack
- Next.js
- App Router
- React
- Tailwind
- Prisma
- MySQL (PlanetScale.com)
- Typescript
- Clerk Authentication (clerk.com)
- Zustand (state management)
- Axios
- Cloudinary.com (Image uploads)
- next-cloudinary

### Setup
- npx create-next-app@latest . --typescript --tailwind --eslint
- npx shadcn-ui@latest init
- npm run dev
- npm install zustand
- npm install axios
- npm install react-hot-toast
- npm install next-cloudinary
- npm install date-fns
- npm install @tanstack/react-table

### Install Components
- npx shadcn-ui@latest add button
- npx shadcn-ui@latest add dialog
- npx shadcn-ui@latest add form
- npx shadcn-ui@latest add input
- npx shadcn-ui@latest add popover
- npx shadcn-ui@latest add command
- npx shadcn-ui@latest add separator
- npx shadcn-ui@latest add alert
- npx shadcn-ui@latest add badge
- npx shadcn-ui@latest add table
- npx shadcn-ui@latest add dropdown-menu

### Clerk Authentication
- npm install @clerk/nextjs

### Prisma
- npm install -D prisma
- npm install @prisma/client
- npx prisma init
- npx prisma generate
- npx prisma db push
- npx prisma migrate reset

### References
- https://ui.shadcn.com/docs/installation/next
- https://nextjs.org/docs/app/building-your-application/routing/route-groups
- https://ui.shadcn.com/docs/components/button
- https://clerk.com/docs/quickstarts/nextjs
- https://clerk.com/docs/components/user/user-button
- https://ui.shadcn.com/docs/components/dialog
- https://ui.shadcn.com/docs/components/form
- https://ui.shadcn.com/docs/components/input
- https://ui.shadcn.com/docs/components/combobox
- https://ui.shadcn.com/docs/components/popover#installation
- https://ui.shadcn.com/docs/components/command#installation
- https://ui.shadcn.com/docs/components/separator
- https://ui.shadcn.com/docs/components/alert
- https://ui.shadcn.com/docs/components/badge
- https://next.cloudinary.dev/installation
- https://ui.shadcn.com/docs/components/data-table
- https://ui.shadcn.com/docs/components/dropdown-menu