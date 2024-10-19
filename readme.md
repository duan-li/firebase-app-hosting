# Firebase app hosting

## next.js


```
npx create-next-app@latest
npm run build
npm run start
```

✔ What is your project named? … next-app
✔ Would you like to use TypeScript? … No / **Yes**
✔ Would you like to use ESLint? … No / **Yes**
✔ Would you like to use Tailwind CSS? … No / **Yes**
✔ Would you like to use `src/` directory? … No / **Ye**s
✔ Would you like to use App Router? (recommended) … No / **Yes**
✔ Would you like to customize the default import alias (@/*)? … **No** / Yes
Creating a new Next.js app in /work/apps/next-app.



git remote add origin git@github.com:duan-li/firebase-app-hosting.git
## NX workspace

```
npx create-nx-workspace
npx create-nx-workspace@19.6
```

✔ Where would you like to create your workspace? · org
✔ Which stack do you want to use? · react
✔ What framework would you like to use? · none
✔ Integrated monorepo, or standalone project? · integrated
✔ Application name · org
✔ Which bundler would you like to use? · webpack
✔ Test runner to use for end to end (E2E) tests · cypress
✔ Default stylesheet format · css
✔ Which CI provider would you like to use? · github


First time using Nx? Check out this interactive Nx tutorial.

https://nx.dev/react-tutorial/1-code-generation

```
nx run firebase-app:serve
```
