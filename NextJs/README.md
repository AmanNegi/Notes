# NextJS - 13
The documentation is based on NextJS-13 `(/app)`, which includes folder routing.

- [NextJS - 13](#nextjs---13)
  - [Predefined file types 📃](#predefined-file-types-)
  - [Folder Structure (Backend) 📁](#folder-structure-backend-)
  - [Folder Structure (Frontend) 📂](#folder-structure-frontend-)
  - [Caching 🔰](#caching-)
  - [Resources 📝](#resources-)


## Predefined file types 📃
> https://blog.logrocket.com/next-js-13-app-directory/

- **page.tsx**: A page file defines a single route in your Next.js application. It is typically used to render a React component.

- **layout.tsx**: A layout file is a special type of page file that can be used to share common UI elements across multiple pages. It is typically used to wrap other page files and provide a consistent look and feel for your application.

- **loading.tsx**: A loading file is used to render a loading indicator while your application is loading. It is typically used when your application is making an API request or loading a large amount of data.

- **error.tsx**: An error file is used to render an error message if something goes wrong in your application. It is typically used when your application encounters an unexpected error or an unexpected response from an API.

- **template.tsx**: It is similar to the layout.tsx file, but upon navigation, a new instance of the component is mounted and the state is not preserved.

- **route.tsx**: Used to define API Handlers in `/api` folder. 

## Folder Structure (Backend) 📁

| Name | Usecase |
|:---: | :---: |
| api | Contains API Handlers |
| api/folder/route.ts | Defines api for `api/folder` |
| api/folder/[id] | Defines dynamic api for `api/folder/1`, `api/folder/2` |


## Folder Structure (Frontend) 📂
> Reference: https://www.builder.io/blog/next-13-app-router

| Name | Usecase |
|:---: | :---: |
| api | Contains API Handlers |
| folder/page.tsx | Routable |
| **_**folder | Non-Routable & Private Folder |
| **(**folder**)** | Avoid folder name in path eg: `/login` instead of `auth/login` |
| **[**folder**]** | Dynamic Routing eg: `products/1`, `products/2` |
| **[**___slug**]** | Nested Dynamic Routing eg: `docs/1/h2`, `docs/2/h2/p` |



## Caching 🔰
``` js  
// Generates statically like getStaticProps.
fetch(URL, { cache: 'force-cache' });

// Generates server-side upon every request like getServerSideProps.
fetch(URL, { cache: 'no-store' });

// Generates statically but revalidates every 20 seconds
fetch(URL, { next: { revalidate: 20 } });
```

## Resources 📝
 
- Industry Level NextJS Codebase: https://github.com/sadmann7/skateshop
- Folder Structure and Colocation: https://nextjs.org/docs/app/building-your-application/routing/colocation
