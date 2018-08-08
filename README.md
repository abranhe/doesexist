<p align="center">
	<a href="https://www.npmjs.com/package/dtfe"><img src="https://cdn.abraham.gq/projects/dtfe/dtfe.png"></a>
	<br>
	<br>
	<br>
	<a href="https://www.npmjs.com/package/dtfe">
	dtfe</a>?: Does the file or folder exist? 🤔
</p>

<p align="center">
	<a href="https://travis-ci.org/abranhe/dtfe"><img src="https://img.shields.io/travis/abranhe/dtfe.svg?logo=travis" /></a>
	<a href="https://github.com/abranhe"><img src="https://abranhe.com/badge.svg"></a>
	<a href="https://cash.me/$abranhe"><img src="https://cdn.abraham.gq/badges/cash-me.svg"></a>
	<a href="https://www.patreon.com/abranhe"><img src="https://cdn.abraham.gq/badges/patreon.svg" /></a>
	<a href="https://github.com/abranhe/dtfe/blob/master/LICENSE"><img src="https://img.shields.io/github/license/abranhe/dtfe.svg" /></a>


</p>

# Install

```
$ npm install dtfe
```

# Example

```
├── bin
    ├── index.js
├── .travis.yml
├── LICENSE
├── package.json
├── tests
    ├── test.js
```
# Usage

```js
const check = require('dtfe');

console.log(check('package.json'));
//=> true

console.log(check('setup.py'));
//=> false

console.log(check('bin/index.js'));
//=> true

console.log(check('tests'));
//=> true
```

# API

**check(file)**

> Return a function with a boolean value checking whether a file/directory exist

# Team

|[![Carlos Abraham Logo](https://avatars3.githubusercontent.com/u/21347264?s=50&v=4)](https://19cah.com) [![Greenkeeper badge](https://badges.greenkeeper.io/abranhe/dtfe.svg)](https://greenkeeper.io/)|
| :-: |
| [Carlos Abraham](https://github.com/abranhe) |

# License

[MIT](https://github.com/abranhe/dtfe/blob/master/LICENSE) License © [Carlos Abraham](https://github.com/abranhe/)
