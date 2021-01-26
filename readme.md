# idgp - Identification Key Generating Program.

## Installation

To install, in the command line, just enter
`npm i idgen --save`

## Description

This is a program made in javascript which is open source. It generates ids and identification keys to be used in many cases.

## Example

<br>

```javascript

const idgen = require('idgen');

console.log(idgen(4));

```

The output would be a random string with 4 characters.

like `ryw3`.

## Syntax

```javascript

idgen(4);
/* ^  ^--------------| 
  function        length of the random generated string.
*/
```

## In HTML

```sh
$ npm init -y

# initialize npm in the directory

$ npm i idgp

# To install idgp
```

Then in html provide the following script tags

```HTML
<script src="./node_modules/idgp/idgen.js"></script>
```

## Open source

we are awaiting for your pull requests. If you face any issue, run `npm test`, which will give to the test report, or report issue on github.

## Enjoy your powerfull library.
