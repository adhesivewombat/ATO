# TECH DEBT: Code Monster in the Closet
#### Nina Zakharenko
## Common mistakes that create tech debt
* Not saying no to features
* Not unit testing
* Overly optimistic estimates
* Not writing re-usable code
* Writing overly-complicated solutions
* Lack of understanding
    * Pasted in code from the internet
## Red flags
* Smelly code
    * Half-implemented features
    * Lack of documentation
    * Broken tests
    * Commented out code
* Architecture smells
    * Parts of code that no one wants to touch
    * Brittle
    * Adding new features is difficult
    * Half-implemented features
    * Lack of documentation
> If you're going to tackle a massive debt problem do it right or don't do it at all

> sometimes you need to kill it with fire
## How to fight the monster
* Don't point fingers
* *Documented* code standards
* Pair programming
* I need a code review
    * Make sure pull requests are actually looked at
* Unit and integration tests
    * Also run the tests
* Use precommit hooks
* CI
* Don't be a perfectionist
    * Figure out the project tolerances and adjust accordingly
* Write tests before refactoring to A-B test
* Prioritize
    * Fix the things that cause the biggest problems first
    * Longer shelf-life is more valuable
> Always check in a module cleaner than when you checked it out