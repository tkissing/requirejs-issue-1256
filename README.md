After running
`npm install && ./node_modules/.bin/r.js -o out=out.js include=foobar exclude=bar/foo optimize=none`
on the code in this project, `out.js` should contain the modules `foobar` and `defect`
but it only includes `foobar`.
