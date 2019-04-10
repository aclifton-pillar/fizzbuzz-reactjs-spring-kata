## FizzBuzz ReactJS and Spring Boot Kata

The goal of this kata is to build your skills around implementing a ReactJS frontend application that
interacts with a Spring Boot REST API backend.

When you've completed this kata you will have accomplished the following:

* Set up a development environment
* Test drive a ReactJS app with Jest and Cypress
    * Ideally, with a nice balance of unit, integration, e2e, and acceptance tests
* Create a ReactJS app with slightly more than trivial behavior
* Test drive a Spring Boot app with JUnit
* Create a Spring Boot app with slightly more than trivial behavior and architecture

Something important to think about in this kata is a concept called End-to-End Early.  Rather than
build front end and back end separately, can you find thin slices that drive functionality
all the way through?

### Development Environment
[Install home-brew](https://brew.sh/)

[Installing Node.js with NVM](https://gist.github.com/d2s/372b5943bce17b964a79)

[Installing yarn package management etc](https://yarnpkg.com/lang/en/docs/install/#mac-stable)

watchman

### ReactJS Project Setup
[Brief React Installation Instructions](https://reactjs.org/docs/add-react-to-a-new-app.html)

Note:  If you do a `yarn eject` after creating the app, sometimes you have to do some
variation of blowing away `node_modules` and then `yarn install` before the pre-existing unit
tests will pass.

[Alternate Way to Create React App?](https://www.npmjs.com/package/cli-react)

### Unit Testing with Jest
[Testing React with Jest](https://facebook.github.io/jest/docs/en/tutorial-react.html)

Note that, out of the box, yarn+watchman will watch for changes to your project and re-run
tests around changed code.  You can also instruct it to re-run all tests by type 'a' in
the terminal window where you ran 'yarn test.'

### E2E and Acceptance Testing with Cypress
[Integrating Cypress and Cucumber](https://medium.com/@itortv/how-to-integrate-cypress-and-cucumber-in-your-development-flow-in-just-a-few-weeks-96a46ac9165a)

### Create a RESTful Spring Boot Web Service
[Spring Boot REST](https://spring.io/guides/gs/rest-service/)


## The Magical Wonder of FizzBuzz

FizzBuzz is a deceptively simple programming problem used by countless IT recruiters to 
find out if candidates indeed have at least some of the programming skills they claim. 
You can implement it in almost any form of computer language in no more than a couple 
minutes. If you can provide input to a function, display the output, and write a couple 
conditionals, you can complete FizzBuzz.

Here are the acceptance criteria:

* Given an input integer

    * When the integer is divisible by 3, Then display Fizz

    * When it is divisible by 5, Then display Buzz

    * When it is divisible by both, Then display FizzBuzz

    * When it is an integer not divisible by 3 or 5, Then display the input number

    * When it is not an integer, Then display an error message or nothing


But wait! Don't just fixate on a bunch of if-elseif-else stuff. In interviews, FizzBuzz
can be an opportunity to show your technical depth. How would you thin slice this problem? 
Is there more than one way? How would you test drive it? What kinds of tests give you 
the best value?

And, for the implementation itself, what happens if you can't use if blocks? 
Does the implementation language give you other structures you can use? What happens if 
a number is divisible by both 3 and 5? Is there any point in checking for 3 and 5 individually?

How could you write the code in an OO style? A functional style? Could you write code 
that would do the evaluation using only binary logic operators? What if you need 
to evaluate billions of numbers really fast in a stream? How could you parallelize 
the operation? Does knowing the answer to one number make it easier to find the answer 
for another? What are the characteristics of your function? Does it run in constant time? 
Why or why not?

The point is that there's a wealth of opportunities to explore the whole of computer science,
 even with such a simple program. So enjoy doing this implementation and let it fill your 
 mind with ideas.

