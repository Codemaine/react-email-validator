# email-validator
A simple module to validate an e-mail address

[![travis build](https://img.shields.io/travis/manishsaraan/email-validator.svg?style=flat-square)](https://travis-ci.org/manishsaraan/email-validator)
[![version](https://img.shields.io/npm/v/email-validator.svg?style=flat-square)]((http://npm.im/email-validator))
[![downloads](https://img.shields.io/npm/dm/email-validator.svg?style=flat-square)](https://npm-stat.com/charts.html?package=email-validators&from=2015-08-01)


## Installation
Install via NPM:

```bash
npm install react-email-validator

```



## Usage

#### javascript

```javascript

var validate = require("react-email-validator");

validate("test@email.com"); // true

validate("test.com"); // false

```

#### TypeScript

```typescript

import { validate } from 'email-validator';

validate("test@email.com"); // true

validate("test.com"); // false

```

