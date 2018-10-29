# CSS as a Service
#### Shay Howe

## What's Bad
### Lots of copy pasta css across different code-bases
* Re-used styles become "archaic"
* Bloat
* Lots of friction when creating new projects
### Style guide first can be "unrealistic"
* Don't actually get used in the indtended way
### Bad selectors
* Using fragile selectors
    * ex. selecting all h2 under a class
* Selectors that are tied to each-other
## What's Good
### Modular css
* Write it only once
* Separate out common components into their own services
    * Maybe even have separate packages for styles??
* Every class should have a single responsability
    * Make them reusable
    * Similar to BEM
### Style guide as documentation instead of instruction
### Folder structure system
* What we do already
* sass can be split up into different folders
    * variables
    * mixins
    * functions

## Takeaways
### Naming consistency is important
* BEM is a pretty good way of enforcing these concepts if followed correctly
* Make your naming system flat
* smacks?
* OO css?
### CSS as shared code
* We can do better at this
* We can also be a bit smarter with how we use SASS
    * Use more functions for creating classes
### Write out everything first then get rid of duplication
### [Sassmeister](https://www.sassmeister.com/)
### Analyze
* [Stylestats](https://github.com/t32k/stylestats)
* [CSSCSS](https://zmoazeni.github.io/csscss/)
* CSS lint
* [Webpagetest](https://www.webpagetest.org/)