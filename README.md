# E-commerce Redux Store

![full-stack](https://img.shields.io/badge/MERN-1?label=full-stack&style=for-the-badge&labelColor=orange&color=black)

![MongoDB](https://img.shields.io/badge/-MongoDB-darkgreen) ![Express](https://img.shields.io/badge/-Express-orange) ![React](https://img.shields.io/badge/-React-yellow) ![NodeJS](https://img.shields.io/badge/-NodeJS-darkred)

![Apollo-Client](https://img.shields.io/badge/3.6.9-0?label=Apollo-Client&style=flat-square&labelColor=yellow&color=black) ![GraphQL](https://img.shields.io/badge/16.5.0-0?label=GraphQL&style=flat-square&labelColor=darkred&color=black) ![Stripe](https://img.shields.io/badge/8.67.0-0?label=Stripe&style=flat-square&labelColor=darkgreen&color=black) ![mongoose](https://img.shields.io/badge/5.9.10-0?label=mongoose&style=flat-square&labelColor=darkblue&color=black)

## Description

This project is part of a challenge to refactor the e-commerce platform so that it uses [Redux](https://redux.js.org/).

Originally, the project was managed via global state using React’s Context API. 

The Context API is quickly gaining traction as a worthy alternative or perhaps even successor to other libraries that manage global state in tandem with React, such as Flux or MobX. Nonetheless, the open source JavaScript library Redux remains the industry standard for managing complex state in a large-scale React application.

It doesn't  make sweeping changes to the code, rather it uses the Redux store to manage state via `react-redux` state management hooks.

## User Story

```md
AS a senior engineer working on an e-commerce platform
I WANT my platform to use Redux to manage global state instead of the Context API
SO THAT my website's state management is taken out of the React ecosystem
```

## Acceptance Criteria

```md
GIVEN an e-commerce platform that uses Redux to manage global state
WHEN I review the app’s store
THEN I find that the app uses a Redux store instead of the Context API
WHEN I review the way the React front end accesses the store
THEN I find that the app uses a Redux provider
WHEN I review the way the app determines changes to its global state
THEN I find that the app passes reducers to a Redux store instead of using the Context API
WHEN I review the way the app extracts state data from the store
THEN I find that the app uses Redux instead of the Context API
WHEN I review the way the app dispatches actions
THEN I find that the app uses Redux instead of the Context API
```

## Mock-Up

Following demo reviews the web application's general appearance and functionality.

![This section reviews the web application's general appearance and functionality](./client/public/images/app_demo.gif)

## Table of Contents

- [Technologies](#technologies)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## [Technologies](#table-of-contents)
---

- `M`ongoDB (Mongoose)
- `E`xpress
- `R`eact
- `N`odeJS
- GraphQL
- Apollo Server
- Apollo Client 3.0
- Stripe
- Bcrypt
- Json Webtokens
- Concurrently
- JavaScript
- React-Bootstrap
- HTML
- Deployed on GitHub Pages

## [Usage](#table-of-contents)
---

- The app is deployed at: https://mern-shopping-redux.herokuapp.com/
- The repo is at: https://github.com/umairkhalid/Ecommerce-redux-store/



```sh
git clone git@github.com:umairkhalid/Ecommerce-redux-store.git

cd Ecommerce-redux-store
```

### Install dependencies

```sh
npm install
```

### Seed the data

```sh
npm run seed
```

### Start the app

```sh
npm run develop
```
## [License](#table-of-contents)

The application is covered under the following license: [MIT](https://choosealicense.com/licenses/mit/)

## [Questions](#table-of-contents)

If you have any question about the repo, open an issue or complete the form at [Contact](https://umairkhalid.github.io/react-portfolio/#contact).

You can find more of my work at [GitHub](https://github.com/umairkhalid).

---
© 2022 Umair Khalid. Confidential and Proprietary. All Rights Reserved.