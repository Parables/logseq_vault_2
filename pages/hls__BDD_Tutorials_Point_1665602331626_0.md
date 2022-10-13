file-path:: ../assets/BDD_Tutorials_Point_1665602331626_0.pdf
file:: [BDD_Tutorials_Point_1665602331626_0.pdf](../assets/BDD_Tutorials_Point_1665602331626_0.pdf)
title:: hls__BDD_Tutorials_Point_1665602331626_0

- BDD uses examples to illustrate the behavior of the system that are written in a readable and understandable language for everyone involved in the development.
  ls-type:: annotation
  hl-page:: 2
  id:: 6347138d-9ea7-4f0f-b0b8-84e442e2c465
- BDD – Key features Behavior Driven Development focuses on − Providing a shared process and shared tools promoting communication to the software developers, business analysts and stakeholders to collaborate on software development, with the aim of delivering product with business value. What a system should do and not on how it should be implemented. Providing better readability and visibility. Verifying not only the working of the software but also that it meets the customer’s expectations.
  ls-type:: annotation
  hl-page:: 3
  id:: 634713a9-cfda-4ba0-8f2e-68b61c473f2c
- unless requirements are obtained correctly, it would be expensive to fix the defects resulting from misunderstanding the requirements at a later stage. Further, the end product may not meet the customer’s expectations.
  ls-type:: annotation
  hl-page:: 3
  id:: 634713bc-04b3-4620-98be-ff41b66b5528
- The need of the hour is a development approach that − Is based on the requirements. Focuses on requirements throughout the development. Ensures that the requirements are met.
  ls-type:: annotation
  hl-page:: 3
  id:: 634713d5-3513-43ad-981a-33c7d43a9c53
- Behavior Driven Development − Derives examples of different expected behaviors of the system. Enables writing the examples in a language using the business domain terms to ensure easy understanding by everyone involved in the development including the customers. Gets the examples ratified with customer from time to time by means of conversations. Focuses on the customer requirements (examples) throughout the development. Uses examples as acceptance tests.
  ls-type:: annotation
  hl-page:: 3
  id:: 634713e1-89ac-45f4-a011-8ea2ec5530a5
- BDD Practices The two main practices of BDD are:
  hl-page:: 3
  ls-type:: annotation
  id:: 634713eb-29c0-43aa-8579-4718e37198d7
	- Specification by Example (SbE)
	- Test Driven Development (TDD)
- Specification by Example Specification by Example (SbE) uses examples in conversations to illustrate the business rules and the behavior of the software to be built.
  ls-type:: annotation
  hl-page:: 3
  id:: 63471412-a2e7-43a2-899e-1743ade6f059
- Specification by Example enables the product owners, business analysts, testers and the developers to eliminate common misunderstandings about the business requirements.
  ls-type:: annotation
  hl-page:: 4
  id:: 6347148f-5eec-43a3-932f-6f6ec2150616
- Test Driven Development 
  ls-type:: annotation
  hl-page:: 4
  id:: 634714a4-54be-44a3-95a0-929b446ac983
	- Test Driven Development, in the context of BDD, turns examples into human readable, executable specifications. The developers use these specifications as a guide to implement increments of new functionality. This, results in a lean codebase and a suite of automated regression tests that keep the maintenance costs low throughout the lifetime of the software.
- Agile BDD 
  ls-type:: annotation
  hl-page:: 4
  id:: 634714b7-0a62-4b04-a27d-4aba779a0ddb
	- In Agile software development, BDD method is used to come to a common understanding on the pending specifications. 
	  The following steps are executed in Agile BDD:
		- The developers and the product owner collaboratively write pending specifications in a plain text editor.
		- The product owner specifies the behaviors they expect from the system.
		- The developers:
			- Fill the specifications with these behavior details.
			- Ask questions based on their understanding of the system.
		- The current system behaviors are considered to see if the new feature will break any of the existing features.
- Agile Manifesto and BDD 
  ls-type:: annotation
  hl-page:: 4
  id:: 63471520-ebab-4413-98ae-f2482d6ae6ad
	- The Agile Manifesto states the following: We are uncovering better ways of developing software by doing it and helping others do it. 
	  Through this work, we have come to value
		- Individuals and interactions − over Processes and tools
		- Working software − over Comprehensive documentation
		- Customer collaboration − over Contract negotiation
		- Responding to change − over Following a plan
	- That is, while there is value in the items on the right, we value the items on the left more. 
	  BDD aligns itself to the Agile manifesto as follows −
		- hl-page:: 5
		  ls-type:: annotation
		  id:: 6347152a-367a-4173-b835-605cad82d560
		  |Agile Manifesto                                                           | BDD                                                                           |
		  |----------------------------------------------------|---------------------------------------------------|
		  |Alignment Individuals and interactions over processes and tools. |BDD is about having conversations.|
		  |Working software over comprehensive documentation.| BDD focuses on making it easy to create software that is of business value.|
		  | Customer collaboration over contract negotiation.| BDD focuses on scenarios based on ideas with continuous communication with the customer as the development progresses. It is not based on any promises. |
		  |Responding to change over following a plan. |BDD focuses on continuous communication and collaboration that facilitates absorption of changes.|
-
- a defect as and when it is introduced and fixing it immediately would be cost effective. Therefore, there is a necessity of writing test cases at every stage of development and testing. This is what our traditional testing practices have taught us, which is often termed as Test-early.
  ls-type:: annotation
  hl-page:: 7
  id:: 634718d0-7e11-49ad-8519-05b166400a94
- Test-First Approach 
  ls-type:: annotation
  hl-page:: 8
  id:: 63471bd7-7a5e-478a-9e8b-91b68e75cf13
	- The Test-First approach replaces the inside-out (write code and then test) to outside-in (write test and then code) way of development.
	- This approach is incorporated into the following software development methodologies (that are Agile also)
		- eXtreme Programming (XP).
		- Test Driven Development (TDD).
	- In these methodologies, the developer designs and writes the Unit tests for a code module before writing a single line of the code module. 
	  The developer then creates the code module with the goal of passing the Unit test. 
	  Thus, these methodologies use Unit testing to drive the development. 
	  The fundamental point to note that the goal is development based on testing.
	- Red-Green-Refactor Cycle
		- Test Driven Development is used to develop the code guided by Unit tests.
			- Step 1 − Consider a code module that is to be written.
			- Step 2 − Write a test
			- Step 3 − Run the test. The test fails, as the code is still not written. Hence, Step 2 is usually referred to as write a test to fail.
			- Step 4 − Write minimum code possible to pass the test.
			- Step 5 − Run all the tests to ensure that they all still pass. Unit tests are automated to facilitate this step.
			- Step 6 − Refactor.
			- Step 7 − Repeat Step 1 to Step 6 for the next code module. Each cycle should be very short, and a typical hour should contain many cycles.
		- This is also popularly known as the Red-Green-Refactor cycle, where − Red − Writing a test that fails. Green − Writing code to pass the test. Refactor − Remove duplication and improve the code to the acceptable standards.
		  ls-type:: annotation
		  hl-page:: 9
		  id:: 63471c7a-6c20-4f6f-b550-8206670a42b1
-
- Advantages of TDD
  hl-page:: 9
  ls-type:: annotation
  id:: 6347217f-fcc9-4a85-915d-6b00d314ae75
	- The developer needs to understand first, what the desired result should be and how to test it before creating the code.
	- The code for a component is finished only when the test passes and the code is refactored. This ensures testing and refactoring before the developer moves on to the next test.
	- As the suite of Unit tests is run after each refactoring, feedback that each component is still working is constant.
	- The Unit tests act as living documentation that is always up to the data.If a defect is found, the developer creates a test to reveal that defect and then modify the code so that the test passes and the defect is fixed. This reduces the debugging time. All the other tests are also run and when they pass, it ensures that the existing functionality is not broken
	- The developer can make design decisions and refactor at any time and the running of the tests ensures that the system is still working.This makes the software maintainable.
	- The developer has the confidence to make any change since if the change impacts any existing functionality, the same is revealed by running the tests and the defects can be fixed immediately.
	- On each successive test run, all the previous defect fixes are also verified and the repetition of same defect is reduced.
	- As most of the testing is done during the development itself, the testing before delivery is shortened.
-
- Story Framework As a [Role] I want [Feature] so that [Benefit] This means, ‘When a Feature is executed, the resulting Benefit is to the Person playing the Role.’
  ls-type:: annotation
  hl-page:: 14
  id:: 63473ed0-5709-4020-86e7-186ade103e41
- Example Framework Given some initial context, When an event occurs, Then ensure some outcomes. This means, ‘Starting with the initial context, when a particular event happens, we know what the outcomes should be.’ Thus, the example shows the expected behavior of the system. The examples are used to illustrate different scenarios of the system. Story and Scenarios Let us consider the following illustration by Dan North about an ATM system. Story As a customer, I want to withdraw cash from an ATM, so that I do not have to wait in line at the bank. Scenarios There are two possible scenarios for this story. Scenario 1 − Account is in credit
  ls-type:: annotation
  hl-page:: 14
  id:: 63473ee3-bbfa-4904-b3ea-c17e68c4cf43
- Given the account is in credit And the card is valid And the dispenser contains cash When the customer requests cash Then ensure the account is debited And ensure cash is dispensed And ensure the card is returned Scenario 2 − Account is overdrawn past the overdraft limit Given the account is overdrawn And the card is valid When the customer requests cash Then ensure a rejection message is displayed And ensure cash is not dispensed And ensure the card is returned The event is same in both the scenarios, but the context is different. Hence, the outcomes are different.
  ls-type:: annotation
  hl-page:: 15
  id:: 63473eef-6680-4d9d-8767-23c3f98b9e2c
-
- hl-page:: 22
  ls-type:: annotation
  id:: 634742f2-d15d-4cbc-b312-34074aad1111
  |Anti-pattern |Problems |
  |No collaboration| Many assumptions; Building wrong thing;  Testing wrong thing; Unaware when code is finished|
  |Unaware when code is finished| Hard to maintain tests; Hard to understand spec; Loss of interest from business representatives|
  |Too detailed or too UI centric examples| Hard to maintain tests; Hard to understand specifications; Loss of interest from business representatives |
  |Underestimating effort required |Teams think they have failed and get disappointed early|
- Solution to the Problems 
  hl-page:: 22
  ls-type:: annotation
  id:: 634743f7-097f-4746-bbe6-e0833eeecdd3
	- Quality Quality can be ensured by keeping a watch on the anti-patterns. To minimize the problems created by anti-patterns, you should
		- Get together to specify using examples.
		- Clean up and improve the examples.
		- Write a code, which satisfies the examples
		- Automate the examples and deploy.
		- Repeat the approach for every user story.
	- To solve the problems due to anti-patterns means adherence to:
		- Collaboration. Focusing on what. Focusing on Business. Be prepared.
- A shared, ubiquitous language is used to write the executable specifications and the automated tests such that − Domain specific terminology is used throughout the development. Everyone, including the customers and the stakeholders speak about the system, its requirements and its implementation, in the same way. The same terms are used to discuss the system present in the requirements, design documents, code, tests, etc. Anyone can read and understand a requirement and how to generate more requirements. Changes can be easily accommodated. Live documentation is maintained.
  ls-type:: annotation
  hl-page:: 28
  id:: 63474537-5eff-47e5-9ceb-ce930b84705a
- Typical Cucumber Acceptance Test Consider the following example. Feature − Sign up Sign up should be quick and friendly. Scenario − Successful sign up New users should get a confirmation e-mail and be greeted personally. Given I have chosen to sign up. When I sign up with valid details. Then I should receive a confirmation email. And I should see a personalized greeting message. From this example, we can see that − Acceptance tests refer to Features. Features are explained by Scenarios. Scenarios consist of Steps.
  ls-type:: annotation
  hl-page:: 28
  id:: 63474556-baff-47bd-8d0d-3427bc37d535
- Gherkin is designed to create requirements that are more concrete. In Gherkin, the above example looks like − Feature Feedback when entering invalid credit card details In user testing, we have seen many people who make mistakes Documentation Background Given I have chosen an item to buy, And I am about to enter my credit card number Scenario − Credit card number too short When I enter a card number that is less than 16 digits long And all the other details are correct And I submit the form Then the form should be redisplayed And I should see a message advising me of the correct number of digits
  ls-type:: annotation
  hl-page:: 34
  id:: 63474586-9fbc-4478-b2f0-aa2392e0b2d1
- Gherkin Format and Syntax Gherkin files are plain text Files and have the extension .feature. Each line that is not blank has to start with a Gherkin keyword, followed by any text you like. The keywords are − Feature Scenario Given, When, Then, And, But (Steps) Background Scenario Outline Examples""" (Doc Strings)| (Data Tables)@ (Tags)# (Comments)*
  ls-type:: annotation
  hl-page:: 34
  id:: 6347458d-afd1-4903-a497-35b16afd36ed