# Gittron

[![freenode][freenode-image]][freenode-url]
[![travis][travis-image]][travis-url]
[![codecov][codecov-image]][codecov-url]

### Open Source GUI for Git with Electron which is used to make Atom.

If you would like to help, let me know!
There is a freenode channel for gittron in the #gittron. See badge on the header.



### Prerequisites

 - [Electron](http://electron.atom.io/)
 - [React](https://facebook.github.io/react/)
 - [Webpack](https://webpack.github.io/)
 - [NPM](https://www.npmjs.com/)

### Installation

    npm install


To watch for changes in the `src` directory:

    npm run watch

To run the actual **electron app**:

    npm start


### Distribution
To prepare the app for distribution run:

    npm run package

To publish a new version, you also need to codesign the app running `npm run codesign`.


### Tests
There are 2 linters for `js` & `scss` and unit tests with `mocha`.

    // Run all tests
    npm run test

    // Run only unit tests
    npm run mocha

    // Run unit tests with coverage
    npm run coverage

### Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request
6. Make sure tests are passing


### License
Gittron is licensed under the MIT Open Source license. For more information, see the LICENSE file in this repository.


[travis-image]: https://travis-ci.org/gittron/gittron.svg?branch=master
[travis-url]: https://travis-ci.org/gittron/gittron
[codecov-image]: https://codecov.io/gh/gittron/gittron/branch/master/graph/badge.svg
[codecov-url]: https://codecov.io/gh/gittron/gittron
[freenode-image]: https://img.shields.io/badge/chat-on%20freenode-brightgreen.svg
[freenode-url]: https://kiwiirc.com/client/irc.freenode.net/#gittron
