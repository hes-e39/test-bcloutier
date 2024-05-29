# Setting up a React app with routing and deployment

1. Create repository
2. Clone
3. `npx create-react-app .`
4. `npm i --save react-router-dom`
5. Add `"homepage": "https://<user|org>.github.io/<repo>/"` to `package.json`
6. Add workflow file
7. Push to GH
8. Wait until fist action finishes, this will create a new branch `gh-pages`
8. In GH:
  Settings -> Pages -> Build and deployment -> Branch -> gh-pages