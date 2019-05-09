# sample project

Phrase object (with palindrome detector) <br>
This is a sample NPM module created in Learn Enough JavaScript to Be Dangerous by Michael Hartl. <br> <br>

The module can be used as follows:<br>

$ npm install --global rpalindrome <br>
$ vim test.js <br>
let Phrase = require("rpalindrome"); <br>
let napoleonsLament = new Phrase("Able was I, ere I saw Elba."); <br>
console.log(napoleonsLament.palindrome()); <br>
$ node test.js <br>
true 