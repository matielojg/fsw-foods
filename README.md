This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Setup:

* NodeJS: 18.17.0
* NPM : 9.6.7

```bash
npm install prisma --save-dev
npx prisma init --datasource-provider postgresql
npx prisma format   #format the schema.prisma file
```

## Dependencies

### [Prisma ORM](https://www.prisma.io/docs/getting-started/quickstart)

#### Migrations

[Commit Page](https://github.com/matielojg/fsw-foods/commit/fe1e9debd1855ba63ad2ccc3f0e26294f3259e9c)

```bash
npx prisma migrate dev --name init_database
```
#### Seed - TS Node

[Commit Page](https://github.com/matielojg/fsw-foods/commit/25e300a4373e3cfbbb9473f58fd638c863c2de67)
```bash
npm install -D ts-node
npx prisma db seed
prisma generate #atualiza schema
```

### Design System: [shadcn/ui](https://ui.shadcn.com/docs/installation/next)

[Commit Page](https://github.com/matielojg/fsw-foods/commit/52eb56496aa5a69db877b86a3b66cf5b87d32a23)
```bash
npx shadcn-ui@latest init
```
### [Tailwind](https://tailwindcss.com/blog/automatic-class-sorting-with-prettier)

#### Prettier

[Commit Page](https://github.com/matielojg/fsw-foods/commit/a902f8f71932e67fde4b154ffae489d002ab4ed6)
```bash
npm install -D prettier prettier-plugin-tailwindcss
```

### [Husky](https://typicode.github.io/husky/get-started.html) - Git Hooks

[Commit Page](https://github.com/matielojg/fsw-foods/commit/d44b0810b45819dc295261515ad142f9abc252fc)

```bash
 npm install -D husky lint-staged
 npx husky init
```

Options:

* ✔ Which style would you like to use? › Default
* ✔ Which color would you like to use as base color? › Slate
* ✔ Would you like to use CSS variables for colors? …  yes


### [NeonDB - Serverless Postgres](https://console.neon.tech/app/projects/proud-frost-91088754)

Logged with GitHub account
