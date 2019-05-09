# sample project

Phrase object (with palindrome detector) \n
This is a sample NPM module created in Learn Enough JavaScript to Be Dangerous by Michael Hartl. \n \n

The module can be used as follows:\n

$ npm install --global rpalindrome \n
$ vim test.js \n
let Phrase = require("rpalindrome"); \n
let napoleonsLament = new Phrase("Able was I, ere I saw Elba."); \n
console.log(napoleonsLament.palindrome()); \n
$ node test.js \n
true \n