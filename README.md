## chdate

A command-line app that prints the next n Gregorian (Western) dates on which a given Chinese lunar month (yue) and day (ri) occur

Usage: `chdate yue ri [n]`

If not specified, `n` defaults to 3.

Example: When are the next three Double Ninth Festivals?\
Command: `chdate 9 9`\
Result: [ '2020-10-25', '2021-10-14', '2022-10-04' ]

### Installation

Depends on `npm` and `node` from https://www.npmjs.com/get-npm, and the `lunar-javascript` node module.

If you install node and lunar-javascript globally (`sudo npm install npm -g`; `sudo npm install lunar-javascript -g`),
then you can copy chdate to any folder on your path.

Make chdate executable (`chmod +x chdate`) and it's ready to use.