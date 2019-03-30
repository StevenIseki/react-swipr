## react-swipr

[![npm version](https://badge.fury.io/js/react-swipr.svg)](https://badge.fury.io/js/react-swipr)

![](https://raw.githubusercontent.com/react-z/react-swipr/master/example/screenshot.gif)

A simple react swipe component

## Install

``` js
yarn add react-swipr
```

## Use

``` js
import Swipr from 'react-swipr'
import ReactDOM from 'react-dom'
import React, { Component } from 'react'

class TestComponent extends Component {
  render () {
    return (
      <div>
        <Swipr elementId="react-swipr-1" navigation={true}>
          <li>
            <img src='https://raw.githubusercontent.com/StevenIseki/react-webpack-example/master/images/react.png' />
          </li>
          <li>
            <img src='https://raw.githubusercontent.com/StevenIseki/react-webpack-example/master/images/styled-components.png' />
          </li>
          <li>
            <img src='https://raw.githubusercontent.com/StevenIseki/react-webpack-example/master/images/webpack.png' />
          </li>
        </Swipr>
        <Swipr elementId="react-swipr-2" navigation={false}>
          <li>
            <img src='https://raw.githubusercontent.com/StevenIseki/react-webpack-example/master/images/react.png' />
          </li>
          <li>
            <img src='https://raw.githubusercontent.com/StevenIseki/react-webpack-example/master/images/styled-components.png' />
          </li>
          <li>
            <img src='https://raw.githubusercontent.com/StevenIseki/react-webpack-example/master/images/webpack.png' />
          </li>
        </Swipr>
      </div>
    )
  }
}

ReactDOM.render(
  <TestComponent />,
  document.getElementById('root')
)
```

## Development
    yarn
    npm run dev

## Build
    yarn
    npm run build
    npm login
    npm version patch
    git add -A
    git push origin master
    npm publish

## License

[MIT](http://isekivacenz.mit-license.org/)
