# TECH DEBT: Code Monster in the Closet
#### Nina Zakharenko
## Common mistakes that create tech debt
* not saying no to features
* not unit testing
* overly optimistic estimates
* not writing re-usable code
* writing overly-complicated solutions
* lack of understanding
    * pasted in code from the internet
## Red flags
* smelly code
    * half-implemented features
    * lack of documentation
    * broken tests
    * commented out code
* architecture smells
    * parts of code that no one wants to touch
    * brittle
    * adding new features is difficult
    * half-implemented features
    * lack of documentation
> If you're going to tackle a massive debt problem do it right or don't do it at all

> sometimes you need to kill it with fire
## How to fight the monster
* don't point fingers
* *documented* code standards
* pair programming
* I need a code review
    * make sure pull requests are actually looked at
* unit and integration tests
    * also run the tests
* use precommit hooks
* CI
* don't be a perfectionist
    * figure out the project tolerances and adjust accordingly
* write tests before refactoring to A-B test
* prioritize
    * fix the things that cause the biggest problems first
    * longer shelf-life is more valuable
> Always check in a module cleaner than when you checked it out