# Contact Manager -

> ## Run Application
>
> > [[Here]](https://billjenner.github.io/contactmanager/)

### Setup

> npm --version

- no longer globaly supported

  > npm uninstall -g create-react-app

- react, react-dom, react-scripts

  > npx create-react-app contactmanager

- bootstrap

  > npm install bootstrap

- gen new GUID utility

  > npm install uuid

- client side validation utility

  > npm install classnames

- React routing utility

  > npm install react-router-dom

- Axios

  > npm install --save axios

- Github pages

  > npm install gh-pages

- enable Emmit for React

  > settings > search emmet > include languages, add item (javascript, javascriptreact)

- React Developer Tools

  > Chrome > Home > Extensions > React Developer Tools

- Redux Stat manager
  > Chrome > Home > Extensions > Redux DevTools

#### Rebuild

> npm install
> Verify / update package.json

- Run local

  > npm run start > http://localhost:3000

- Push to Github Pages

  > npm run deploy

#### Visual Studio Extentions

> Bracket Pair Colorizer
> ES7/React/Redux/GraphQL/React-Native snippets (rcc)
> Live Server
> Prettier - Code formatter

- VS Code settings > CTRL ,

  ```
  editor.formatOnSave" true

  emmit.includeLanguages: {
    javascript: "javascriptreact"
  }
  emmet.syntaxProfiles: {
    javascript: "jsx"
    javascript: "html
  }
  ```

```

"scripts": {
"test": "echo \"Error: no test specified\" && exit 1",
"start": "lite-server"
}

```

#### Notes

```
  <div id="root"></div>

index.js
  ReactDOM.render(
    <React.StrictMode>
      <App />
    </React.StrictMode>,
    document.getElementById('root')
  );

// context api, redux manager for application level state
// jsx
  htmlfor
  <br />
  return - a single parent element

  function Contact() {
  return (
    <div className="App">
      <h1>Hello</h1>
    </div>
  );

  class Contact extends Component {
  render() {
    return (
      <div className="App">
        <h1>Hello</h1>
      </div>
    );
  }

  export default Contact;

  App.js
    <Contact />
}
}

  // bootstrap navbar shortcut
  nav.navbar.navbar-expand-sm.navbar-dark.bg-danger.mb-3.py-0
```

### References

- [ES6 Refresser](./es6_refresher_start/main.js)

- [Node JS](https://nodejs.org/en/)

- [Git](https://git-scm.com/)

- [Babel](https://babeljs.io/)

- [Parcel](https://parceljs.org/)

- [Axios](https://github.com/axios/axios)

- [React](https://reactjs.org/)

- [Font Awsome](https://fontawesome.com/icons?d=gallery)

- [React Tutorial #3.5 - React Dev Tools](https://www.youtube.com/watch?v=TRPfZ4INN9w)

- [React & Webpack 4 From Scratch - No CLI](https://www.youtube.com/watch?v=deyxI-6C2u4&t=977s)

- [React & Webpack 4 From Scratch - Github](https://github.com/bradtraversy/react_webpack_starter)

- [Providers & Consumers](https://reactjs.org/docs/context.html)

### Course

- [React Front to Back](https://www.udemy.com/course/draft/1812112/learn/lecture/11138502#overview/)

### Certificate

![Certificate](./images/certificate.png)
