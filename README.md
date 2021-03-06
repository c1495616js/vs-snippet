# Frontend Booster - NextJS

This codebase is a NextJS boilerplate. It is intended to be used as a
[Booster](https://github.com/jared-jewitt/booster-guidelines) for my [Launchpad](https://github.com/jared-jewitt/launchpad).
However, that being said, it can still be used completely on its own - CI/CD and infrastructure (IaC) come pre-configured.

#### Requirements:

- [Docker](https://www.docker.com/) (Optional)
- [Node](https://nodejs.org/en/) (Required - unless Docker is used)
- [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (Optional - only for Windows users)

#### Features:

- ๐๐ผ Next 10
- โ๏ธ React 17
- โ๏ธ Type safety via TypeScript
- ๐ Private, public, and shared routes
- ๐ Write SCSS & future CSS with PostCSS + preset-env
- ๐ฏ Browserslist for specific browser support
- ๐ Add SVGs, images, and custom fonts
- ๐ Path aliasing for streamlined imports
- ๐ Prettier for consistent code style
- ๐ Lint your code with ESLint & StyleLint
- ๐บ Husky + lint-staged for code quality assurance
- ๐งช Jest + React Testing Library for tests

#### Developers:

- [Jared Jewitt](https://jared-jewitt.github.io/)

## ๐ Getting Started

Run the frontend via either option below, then visit the client at `http://localhost:3000`

**_Docker:_**

```
make run
```

**_NPM:_**

```
npm install
npm run dev
```

## โจ๏ธ Commands

**_Docker:_**

| Command        | Description                                                         |
| -------------- | ------------------------------------------------------------------- |
| make run       | Launches the client                                                 |
| make close     | Closes the client                                                   |
| make purge     | Purges the client containers, images, networks, volumes             |
| make workspace | Shells into the client to run one-off commands. e.g. `npm run test` |

**_NPM:_**

| Command      | Description                                                   |
| ------------ | ------------------------------------------------------------- |
| npm run prod | Builds and runs the client on $PORT &#124;&#124; 4000         |
| npm run dev  | Runs the client with hot reloading on $PORT &#124;&#124; 3000 |
| npm run test | Runs the suite of Jest tests                                  |
| npm run lint | Runs Prettier, ESLint, and StyleLint formatters               |

## ๐ Deployment

[Instructions here](DEPLOYMENT.md).

## โ๏ธ License

Code released under the [MIT License](LICENSE).
