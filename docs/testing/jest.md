---
permalink: /testing/jest/
---

[Jest](https://jestjs.io/) will be the first testing framework I will check out and document. This is the framework currently favoured by [Kent C. Dodds](https://kentcdodds.com/).

Testing criteria:
* Ease of use
	* To set up
	* To create tests
	* To run the tests
	* To set up with Typescript
* Types of testing supported

	I'm currently thinking about Unit testing. What else can it be comfortably used with?
* What can be tested:
	* Basic testing
	* Call backs
	* Promises
* Support:
	* What documentation is available
	* Git activity
	* Stackoverflow
* Code coverage

# First impressions
The website looks rather good. There are links to a quickstart guide and to the documentation.
Further skimming of the homepage suggests that this is a zero-config tool and it has builtin code coverage analysis. It professes to be fast by running tests in parallel (with independent global state). After setting page zoom to 180%, I was able to appreciate the screenshots of the feedback messages available. These give different responses for issues with:
* values received
* types
* properties passed
* passing the wrong function

Mocking is mentioned, I'm familiar with the concept but haven't needed to do it so far. Snapshots is new to me.

# First tests
Following the [Getting Started guide](https://jestjs.io/docs/en/getting-started).

## Installation
I ran `yarn add --dev jest` it was interesting to see that yarn was mentioned first. From my experience it's usually mentioned as an alternative to npm.
Jest has 316 dependencies. Including babel, Typescript types and istanbul.

