# faast-ui
A reusable Bootstrap 4 theme and set of React components for use across [faa.st](https://faa.st) products.

## Documentation

- [Bootstrap 4](https://getbootstrap.com/docs/4.0)
- [Reactstrap](https://reactstrap.github.io)

## Development

Install dependencies:

```sh
npm install
```

Run examples at [http://localhost:8080/](http://localhost:8080/) with webpack dev server:

```sh
npm start
```

## Usage

### Installation

Install faast-ui and peer-dependencies via NPM:

```
npm install --save go-faast/faast-ui reactstrap react react-dom
```

Import faast-ui CSS somewhere in in the entrypoint of your app (e.g. `src/index.js` for create-react-app):

```js
import 'faast-ui/dist/css/faast-ui.css'
```

or, directly import in your scss to have access to all bootstrap variables and mixins:

```scss
@import '~faast-ui/src/style/index.scss';
```

Import the components you need:

```js
import { Button } from 'reactstrap'
```

### Required Peer Dependencies

These libraries are not bundled with faast-ui and are required at runtime:

  * [**react**](https://www.npmjs.com/package/react)
  * [**react-dom**](https://www.npmjs.com/package/react-dom)
  * [**reactstrap**](https://www.npmjs.com/package/reactstrap)
