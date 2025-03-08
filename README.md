# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

+> Navigate to the project folder in cmd / terminal.
=> After cloning the repo, run `npm install`. If you encounter with vulnerabilities, run `npm audit fix`, even after this there are errors then run `npm audit fix --force`. To look at the information run `npm fund`.

=> Before running, goto RapidAPI website and search Coinkranking and get your apikey.
=> Paste the API key directly into `src\services\cryptoApi.js`

`const cryptoApiHeaders = {
  "X-RapidAPI-Key": 'YOUR_API_KEY',
  "X-RapidAPI-Host": 'coinranking1.p.rapidapi.com',
};`

=> Finally, run this `npm run dev`, as wer're using VITE. 
=> You'll find the localhost link in the termina, "Ctrl + click" the link.
=> Now, you could see the website and you could surf the website.


