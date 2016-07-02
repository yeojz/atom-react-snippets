# atom-react-snippets package
Atom React + Redux snippets (ES5, ES6, ES6+)

## About
In addition to the common lifecycle and component snippets, Some stage-0
snippets are also include.

Example: `class property initialization`
```js
class Counter extends React.Component {
  componentWillMount = () => {
    ...
  }
  ...
}
```

Some (Redux)[https://github.com/reactjs/redux] based skeleton like `reducer`,
`middleware` as well as `redux`-connected class snippets are also included.

## Credits:
A portion of the React snippets are based off the snippets in atom [react](https://atom.io/packages/react) package.

However, due the aforementioned package and [language-babel](https://atom.io/packages/language-babel) incompatibilities and I mostly depend on the snippets, I decided to fork it out as a separate repo.

If you do not use `language-babel`, you may want to consider looking at the `react` package.
