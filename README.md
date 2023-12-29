# Two sets of numbers

A simple api serving two urls, every url serves a hardwired array of strings.
The two sets of strings have:
- some elements in common
- some element only in set `one`
- some element only in set `two`

## How to run
`npm install`

`npm start`

## URLs
`/api/one.json`

`/api/two.json`

## How it works
It leverages [serve](https://www.npmjs.com/package/serve) on two static files.
