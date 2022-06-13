# Phrase object (with palindrome detector)

This is a sample NPM module created in [_Learn Enough JavaScript to Be Dangerous_](https://www.learnenough.com/javascript-tutorial) by Michael Hartl.

The module can be used as follows:

```
$ npm install --global gregstephensjr-palindrome
$ vim test.js
let Phrase = require("gregstephensjr-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```
