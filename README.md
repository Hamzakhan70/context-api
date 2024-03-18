# React + Vite

to start

npm run dev

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- create context folder and make file for context like user context/employee context or anyone context etc etc and also make provider file in this way complete context store is created.
- context is basically a provider which is usefull for the providing the variable and we use it as a wrapper
- this context directory is basically a store where we store our variables and provider is used to acces that variables.
- make userContextProvider which will wrap the coming children props and share user and setUser
- in App.js where we will wrape our components with in provider.
