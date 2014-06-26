# mocha-teamcity-phantomjs

Allows you to use `teamcity` reporter with `mocha-phantomjs`.

Create a symlink to `node_modules/mocha-teamcity-phantomjs/mocha-teamcity-phantomjs.js` near your `html` page.

Add to the html page:

```html
<script src="mocha.js"></script>
<script src="mocha-teamcity-phantomjs.js"></script>
```

Run:

```
node_modules/.bin/mocha-phantomjs -R teamcity test.html
```
