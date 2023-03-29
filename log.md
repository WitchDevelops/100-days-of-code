# 100 Days Of Code - Log

## Day 1: 2023-03-04

**Today's Progress**: 

* Decided to start. 
* Read a chapter on Flexbox from [Responsive Web Design with HTML5 and CSS](https://www.packtpub.com/product/responsive-web-design-with-html5-and-css-fourth-edition/9781803242712)
* Worked on the form on Sofia's website

**Thoughts:** 

There is a nice shorthand to center an element within a div using flex.
``` place-items: center; ``` - I need to remember this and use it.
Sending a webform is impossible with HTML. All it can do is open the mailing software and this is not what I want. I need to figure out how to do it using PHP.

**Link to work:** 
- [hotfix-form branch](https://github.com/WitchDevelops/Artgallery-Sofiadali/tree/hotfix-form)
- [live website](https://sofiabanchenko.com)

## Day 2: 2023-03-05

**Today's Progress**:

* started learning ancient technology (PHP).

**Thoughts:**

Why are comments so similar yet different for various languages?
``` <?php
// I'm a single line comment in php - but also in JavaScript!
# I'm a single line comment in php.
/* and I'm a multiline comment in php, but also in JavaSctipt and CSS */
```
ugh

**Link to work:**

[Learn PHP: Introduction](https://www.codecademy.com/profiles/the_witch)

## Day 3: 2023-03-06

**Today's Progress**:

* continued learning PHP

**Thoughts:**

PHP is easy. I need some mental adjusting, because whenever I need to declara a variable my instict tells me: use ```let```.

**Link to work:**

* [Learn PHP: Introduction](https://www.codecademy.com/profiles/the_witch)
* [Certificate](https://www.codecademy.com/profiles/the_witch/certificates/167925f179f648e8abbaedbdf5b43091)

## Day 4: 2023-03-07

**Today's Progress**:

* learned about destructuring syntax in ES6

**Thoughts:**

Destructuring syntax is ok. Destruturing nested objects and renaming the variables is unintuitive. Take this code snippet for example:
```const {today: {low: lowToday, high: highToday}} = LOCAL_FORECAST; ```
```LOCAL_FORECAST``` is a parent object, ```today``` is a nested object that contains ```low``` and ```high``` keys for its properties. That colon to rename them is confusing.

**Link to work:**

* [FreeCodeCamp ES6](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC)


## Day 5: 2023-03-08

**Today's Progress**:

* revised template literals, classes and constructor method in ES6
* did a bunch of challenges from FreeCodeCamp JS certification

**Thoughts:**

Repetition is the mother of learning.

**Link to work:**

* [FreeCodeCamp ES6](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC)
* [Code](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC/commit/a45b082959a417e7972151ed1870c24d920c0ef6)

## Day 6: 2023-03-10 (I skipped yesterday)

**Today's Progress**:

* revised getters, setters and promises in ES6
* finished ES6 module in the FCC JS certificaiton

**Thoughts:**

The excercise on getters and setters was confusing. Promises seem easy, I've even used them once. Web Dev Simplified explains them pretty well!

**Link to work:**

* [FreeCodeCamp ES6](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC)
* [Code: promise](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC/blob/main/handle-a-rejected-promise-with-catch.js)

## Day 7: 2023-03-11

**Today's Progress**:

* worked on PHP form

**Thoughts:**

Sending data submitted to a web form is not an easy task. Form data is first send to a server, then to an email address. This can be done with PHP using PHP mailer library.
Setting up PHP and said library, as well as Apache server on a local machine is a pain when compared to coding in JavaScript, but can be done. I managed to see PHP page run on a localhost. My main, unresolved, issue is with correct settings of an SMTP server. Can't figure it out for the life of me, I keep getting "405 access denied" error. It is exactly the same when I tried coding the backend logic with JavaScript, so I'm sure it's not code-related, but SMTP-related. Blocked gateway, firewall, whatever. Something doesn't work.

**Link to work:**

* [code: PHP form](https://github.com/WitchDevelops/PHP-form-test/tree/JS-sending) (note: branch name is incorrect, but the code is)

## Day 8: 2023-03-12

**Today's Progress**:

* worked on PHP form and gave up, used endpoint service instead
* learned some regex!

**Thoughts:**

I tried again but gave up, it's too much of a hassle and can be done easily. Using PHP mailer library is a lot of code and dependencies, while using a free endpoint serive like [Form submit](https://formsubmit.co/documentation) is a single line of code (even less, you only specify the `action="..."` attribute.
Regex is... mysterioous but powerful. It's good to understand it well, its syntax and capabilities.

**Link to work:**

* [FreeCodeCamp Regular expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6)

## Day 9: 2023-03-13

**Today's Progress**:

* continued working on regex - up to excercise 28/33 on FCC JS certification

**Thoughts:**

nada

**Link to work:**

* [FreeCodeCamp Regular expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6)

## Day 10: 2023-03-14

**Today's Progress**:

* finished the regex section in FCC JS curriculum

**Thoughts:**

Regex ain't so bad, once you get, you get it. There is a method to this maddness ;)

**Link to work:**

* [FreeCodeCamp Regular expressions](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6)

## Day 11: 2023-03-15

**Today's Progress**:

* played around with Bootstrap

**Thoughts:**

I do not like it. I see how it can be useful and speed up development, but it's just... not pretty? Especially the main navigation, I really don't like it how it slides from the top. Is there a way to easily override it?

**Link to work:**

* no link

## Day 12: 2023-03-16

**Today's Progress**:

* fix some minor issues on Sofia's website

**Thoughts:**

I am fairly satisfied with how this page looks, but I need some inspiration for how to make it look better. I tried adding animated border to buttons, but that's not it. Maybe reveal on scroll will do it?

**Link to work:**

* [repository](https://github.com/WitchDevelops/Artgallery-Sofia-Banchenko)

## Day 13: 2023-03-17

**Today's Progress**:

* solved FCC project: palindrome checker

**Thoughts:**

That was fun! Now I want to hook it up to a webpage to give it some GUI :)

**Link to work:**

* [code](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC/blob/0f16edc11a2b986ed2526a34641ceda544fb4127/palindrome-checker.js)

## Day 14: 2023-03-18

**Today's Progress**:

* worked on JS DOM manipulation

**Thoughts:**

I tried to grab user input from a form field and display the result on the screen, but this didn't work. Need to check what am I doing wrong here.

**Link to work:**

* no link today

## Day 15: 2023-03-20 (took the weekend off)

**Today's Progress**:

* added DOM manipulatio to the JS palindrome checker project

**Thoughts:**

Somethings the easiest things are so easily forgotten... I had to look up my older project (the only one in which I did DOM manipulation before) to check in the code how did I do it back then.
I've added some Bootstrap to it, just for practice.

**Link to work:**

* [code](https://github.com/WitchDevelops/Palindrome-checker)
* [live page](https://witchdevelops.github.io/Palindrome-checker/)

## Day 16: 2023-03-21

**Today's Progress**:

* continued with FCC JS certification

**Thoughts:**

no thoughst :P

**Link to work:**

* [FCC JS](https://www.freecodecamp.org/Domi_)

## Day 17: 2023-03-22

**Today's Progress**:

* worked on roman numeral converter project

**Thoughts:**

If not for Ramon, I wouldn't know how to solve it...

**Link to work:**

* [FCC JS](https://www.freecodecamp.org/Domi_)

## Day 18: 2023-03-23

**Today's Progress**:

* worked on roman numeral converter project
* fisnished basic data structures part of FCC JS curriculum

**Thoughts:**

I tried to understand the code for this project that uses a class. It makes the code less understandable (for me), but shorter and cleaner.

**Link to work:**

* [roman numeral converter JS code](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC/blob/aec909e3fa73b65af72ed9681da2e13fcec931f4/roman-numeral-converter)
* [basic data structures JS](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC/commit/6f93af93207e74d250163ae8599f7a6e1cc017e3)

## Day 19: 2023-03-24

**Today's Progress**:

* added GUI to roman numeral converter project
* messed about with group project

**Thoughts:**

Practicing DOM manipulation (sometimes I still don't really know what's going on).
Collaboration on a small codebase with a large dev group is a challenge.

**Link to work:**

* [converter](https://witchdevelops.github.io/Numeral-converter/)
* [group project](https://commit-group.github.io/Advice-generator-app/)

## Day 20: 2023-03-25

**Today's Progress**:

* finished the git and github course on CodeCademy

**Thoughts:**

That was a very helpful course, now I need to practice what I learned.

**Link to work:**

* [certificate](https://www.codecademy.com/profiles/the_witch/certificates/a8ab218d5950c29861635cc0bf12fd13)
* [syllabus](https://www.codecademy.com/learn/learn-git)

## Day 21: 2023-03-27 (Sunday was a rest day)

**Today's Progress**:

* started CS50
* continued with FCC JS curriculum
* watched Python for everybody (or was it yesterday?)

**Thoughts:**

Using indentation as a semantic part of the code (as in Python) is evil. Indentation is important for legibility and easthetic reasons, but giving meaning to spaces is devil's work.
I like the way CS50 is taught, yet I wonder if I can still catch on with the current cohort (deadline for lecture 0 was 4 months ago...)

**Link to work:**

no work, no links. Only watch.

## Day 22: 2023-03-28

**Today's Progress**:

* worked on FCC JS project: cesar cipher

**Thoughts:**

For now I can mostly follow Ramon's explanations (it looks so easy when he's doing it), but I can't see any alternative solutions. I suppose I don't have enough knowledge to see what's possible.
Anyway, here's my solution.
I plan to add GUI to it, as I did with other projects.

**Link to work:**
* [solution to the cipher project](https://github.com/WitchDevelops/JavaScript-Algorithms-and-Data-Structures-FCC/blob/main/caesars-cipher.js)

## Day 23: 2023-03-29

**Today's Progress**:

* continued with CS50, lecture 1

**Thoughts:**

C looks evil xD
But I really like how DAvid explains things. It's gonna be a good course.

**Link to work:**
* [evil C lives here](https://github.com/WitchDevelops/CS50x)
