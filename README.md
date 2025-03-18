## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

## commands
npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm
pnpm dev

## исправить ошибку
pnpm remove bcrypt
pnpm add bcryptjs

// /app/seed/route.ts
- import bcrypt from "bcrypt";
+ import bcrypt from "bcryptjs";