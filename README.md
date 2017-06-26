# cheerio-bower-build
Bower package for [cheerio] parser

### Installation steps

```sh
$ bower install cheerio-bower-build --save
```
### Usage
Include [cheerio] bundle in your index file
```html
<script src="bower_components/cheerio-bower-build/dist/cheerio.js"></script>
```
Now [cheerio] is available in global window object (Example from original documentation)
```js
const $ = cheerio.load('<h2 class="title">Hello world</h2>')

$('h2.title').text('Hello there!')
$('h2').addClass('welcome')

$.html()
//=> <h2 class="title welcome">Hello there!</h2>
```
[cheerio]: <https://github.com/cheeriojs/cheerio>
