## react-swipe

[![npm version](https://badge.fury.io/js/react-swipr.svg)](https://badge.fury.io/js/react-z-swipe)

![](https://raw.githubusercontent.com/react-z/react-swipe/master/example/screenshot.gif)

A simple react swipe component

## Install

``` js
yarn add react-z-swipe
```

## Use

``` js
import Swipe from 'react-z-swipe'
import ReactDOM from 'react-dom'
import React, { Component } from 'react'

class TestComponent extends Component {
  render () {
    return (
      <div>
        <Swipe elementId="react-swipe-1" navigation={true}>
          <li>
            <img src='react.png' />
          </li>
          <li>
            <img src='styled-components.png' />
          </li>
          <li>
            <img src='webpack.png' />
          </li>
        </Swipe>
        <Swipe elementId="react-swipe-2" navigation={false}>
          <li>
            <img src='react.png' />
          </li>
          <li>
            <img src='styled-components.png' />
          </li>
          <li>
            <img src='webpack.png' />
          </li>
        </Swipe>
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
    yarn run dev

## Test
    yarn run test

## Build
    yarn
    yarn run build

## Publish
    npm login
    npm version patch
    git add -A
    git push origin master
    npm publish

## License

[MIT](http://isekivacenz.mit-license.org/)
