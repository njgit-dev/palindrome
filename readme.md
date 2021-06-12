
This is a sample NPM module created in *[Learn Enough JavaScript to Be Dangerous](https://www.learnenough.com/javascript)* by Michael Hartl.

The module can be used as follows:

```
$ npm install --global njewell-palindrome
$ vim test.js
let Phrase = require("njewell-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true

```
