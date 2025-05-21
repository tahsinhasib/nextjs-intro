# nextjs-intro

### Necessary items to be Yes/No while installation

```bash
√ What is your project named? ... my-app
√ Would you like to use TypeScript? ...                                 Yes
√ Would you like to use ESLint? ...                                     Yes
√ Would you like to use Tailwind CSS? ...                               Yes
√ Would you like your code inside a `src/` directory? ...               Yes
√ Would you like to use App Router? (recommended) ...                   Yes
√ Would you like to use Turbopack for `next dev`? ...                   No
√ Would you like to customize the import alias (`@/*` by default)? ...  Yes
√ What import alias would you like configured? ... @/*
Creating a new Next.js app in C:\Github Repos\nextjs-intro\my-app.

Using npm.

Initializing project with template: app-tw


Installing dependencies:
- react
- react-dom
- next

Installing devDependencies:
- typescript
- @types/node
- @types/react
- @types/react-dom
- @tailwindcss/postcss
- tailwindcss
- eslint
- eslint-config-next
- @eslint/eslintrc
```


### For run project in development server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

### Important notes

| Item  | Purpose |
| ----- | ------- |
| <code>public</code>         | This is for storing images, videos, gifs etc |
| <code>src</code>            | This is for code files |
| <code>Port: 3000</code>            | This is by default, unlike nestjs this doesn't have to be manually configured |
| <code>layout.tsx</code> | inside <code>app</code> dir it loads the default black layout of nextjs. <br> Comment/Uncomment to see the changes |
| <code><></></code> | Use this tag instead of using < div > as a parent tag in export default function |
| <code>Link</code> | Use this tag instead of using < a > |
| <code>'use client'</code> | Use this in the very first line of you code file if you're writing JS (client side) in Next |

| Steps  | Process |
| ----- | ------- |
| 1 | Create directory <code>DirName</code> inside my-app/src/app/    |
| 2 | Inside the directory create page <code>page.tsx</code> <br> Note: page.tsx name is fixed  |
| 3 | Create a default function inside page.tsx (check below for template) |


#### <i>Step - 3 Breakdown</iV>
```js
export default function Home() {
    return (
        <div>
            <h1>Content</h1>
            // you should add contents here
            // a parent div must be present and it should container the items
        </div>
    )
}
```

