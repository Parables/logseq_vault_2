file-path:: ../assets/A_Handbook_of_Agile_Software_Craftsmanship_By_Robert_C_Martin.pdf_(_PDFDrive_)_1667838275744_0.pdf
file:: [A_Handbook_of_Agile_Software_Craftsmanship_By_Robert_C_Martin.pdf_(_PDFDrive_)_1667838275744_0.pdf](../assets/A_Handbook_of_Agile_Software_Craftsmanship_By_Robert_C_Martin.pdf_(_PDFDrive_)_1667838275744_0.pdf)
title:: hls__A_Handbook_of_Agile_Software_Craftsmanship_By_Robert_C_Martin.pdf_(_PDFDrive_)_1667838275744_0

- LeBlanc’s law: Later equals never.
  ls-type:: annotation
  hl-page:: 35
  id:: 6369373a-2b19-4faa-951b-efba255acb02
- We will never be rid of code, because code represents the details of the requirements. At some level those details cannot be ignored or abstracted; they have to be specified. And specifying requirements in such detail that a machine can execute them is programming. Such a specification is code.
  ls-type:: annotation
  hl-page:: 33
  id:: 636937ba-bdbb-490d-80eb-c8051ff93566
- Most managers want good code, even when they are obsessing about the schedule. They may defend the schedule and requirements with passion; but that’s their job. It’s your job to defend the code with equal passion.
  ls-type:: annotation
  hl-page:: 37
  id:: 63693a07-cfb4-43b2-904d-cad64fa9b8c7
- The only way to make the deadline—the only way to go fast—is to keep the code as clean as possible at all times.
  ls-type:: annotation
  hl-page:: 37
  id:: 63693ace-5834-4a11-a709-d2d3c2292ee2
- Writing clean code requires the disciplined use of a myriad little techniques applied through a painstakingly acquired sense of “cleanliness.” 
  ls-type:: annotation
  hl-page:: 38
  id:: 63693b60-8c0c-42a9-b7c6-387f90aa776e
- a programmer who writes clean code is an artist who can take a blank screen through a series of transformations until it is an elegantly coded system.
  ls-type:: annotation
  hl-page:: 38
  id:: 63693bd2-0aa7-4f07-9f85-07d59350792b
- Bjarne Stroustrup, inventor of C++ and author of The C++ Programming Language I like my code to be elegant and efficient. The logic should be straightforward to make it hard for bugs to hide, the dependencies minimal to ease maintenance, error handling complete according to an articulated strategy, and performance close to optimal so as not to tempt people to make the code messy with unprincipled optimizations. Clean code does one thing well.
  ls-type:: annotation
  hl-page:: 38
  id:: 63693c32-f065-4e58-a049-daf2507b78f2
- Pragmatic Dave Thomas and Andy Hunt said this a different way. They used the metaphor of broken windows.3 A building with broken windows looks like nobody cares about it. So other people stop caring. They allow more windows to become broken. Eventually they actively break them. They despoil the facade with graffiti and allow garbage to collect. One broken window starts the process toward decay.
  ls-type:: annotation
  hl-page:: 39
  id:: 63693d37-346a-45fc-be91-80963d208c8e
- Bad code tries to do too much, it has muddled intent and ambiguity of purpose. Clean code is focused. Each function, each class, each module exposes a single-minded attitude that remains entirely undistracted, and unpolluted, by the surrounding details.
  ls-type:: annotation
  hl-page:: 39
  id:: 63693de1-c5ab-4a2a-b195-0dc0c7832833
- Grady Booch, author of Object Oriented Analysis and Design with Applications Clean code is simple and direct. Clean code reads like well-written prose. Clean code never obscures the designer’s intent but rather is full of crisp abstractions and straightforward lines of control.
  ls-type:: annotation
  hl-page:: 39
  id:: 63693e0c-a18e-4b06-b9a6-3f980aa15bef
- . Like a good novel, clean code should clearly expose the tensions in the problem to be solved. It should build those tensions to a climax and then give
  ls-type:: annotation
  hl-page:: 39
  id:: 63693ed1-93f1-4c20-abc3-2e77d750b925
- Our code should be matter-of-fact as opposed to speculative. It should contain only what is necessary. Our readers should perceive us to have been decisive.
  ls-type:: annotation
  hl-page:: 40
  id:: 63693f42-7326-4fed-a3b7-ea2a3f3af86f
- “Big” Dave Thomas, founder of OTI, godfather of the Eclipse strategy Clean code can be read, and enhanced by a developer other than its original author. It has unit and acceptance tests. It has meaningful names. It provides one way rather than many ways for doing one thing. It has minimal dependencies, which are explicitly defined, and provides a clear and minimal API. Code should be literate since depending on the language, not all necessary information can be expressed clearly in code alone.
  ls-type:: annotation
  hl-page:: 40
  id:: 63693fa1-0e15-4530-9580-5e857023de3a
- Michael Feathers, author of Working Effectively with Legacy Code I could list all of the qualities that I notice in clean code, but there is one overarching quality that leads to all of them. Clean code always looks like it was written by someone who cares. There is nothing obvious that you can do to make it better. All of those things were thought about by the code’s author, and if you try to imagine improvements, you’re led back to where you are, sitting in appreciation of the code someone left for you—code left by someone who cares deeply about the craft.
  ls-type:: annotation
  hl-page:: 41
  id:: 636940d8-98bd-49d6-b198-04bee690cbc3
- Ron Jeffries, author of Extreme Programming Installed and Extreme Programming Adventures in C# Ron began his career programming in Fortran at the Strategic Air Command and has written code in almost every language and on almost every machine. It pays to consider his words carefully. In recent years I begin, and nearly end, with Beck’s rules of simple code. In priority order, simple code:• Runs all the tests;• Contains no duplication;• Expresses all the design ideas that are in the system;• Minimizes the number of entities such as classes, methods, functions, and the like. Of these, I focus mostly on duplication. When the same thing is done over and over, it’s a sign that there is an idea in our mind that is not well represented in the code. I try to figure out what it is. Then I try to express that idea more clearly. Expressiveness to me includes meaningful names, and I am likely to change the names of things several times before I settle in. With modern coding tools such as Eclipse, renaming is quite inexpensive, so it doesn’t trouble me to change. Expressiveness goes
  ls-type:: annotation
  hl-page:: 41
  id:: 6369435c-554e-4b15-ab36-7b97f65dc1b7
- beyond names, however. I also look at whether an object or method is doing more than one thing. If it’s an object, it probably needs to be broken into two or more objects. If it’s a method, I will always use the Extract Method refactoring on it, resulting in one method that says more clearly what it does, and some submethods saying how it is done. Duplication and expressiveness take me a very long way into what I consider clean code, and improving dirty code with just these two things in mind can make a huge difference. There is, however, one other thing that I’m aware of doing, which is a bit harder to explain. After years of doing this work, it seems to me that all programs are made up of very similar elements. One example is “find things in a collection.” Whether we have a database of employee records, or a hash map of keys and values, or an array of items of some kind, we often find ourselves wanting a particular item from that collection. When I find that happening, I will often wrap the particular implementation in a more abstract method or class. That gives me a couple of interesting advantages. I can implement the functionality now with something simple, say a hash map, but since now all the references to that search are covered by my little abstraction, I can change the implementation any time I want. I can go forward quickly while preserving my ability to change later. In addition, the collection abstraction often calls my attention to what’s “really” going on, and keeps me from running down the path of implementing arbitrary collection behavior when all I really need is a few fairly simple ways of finding what I want. Reduced duplication, high expressiveness, and early building of simple abstractions. That’s what makes clean code for me. Here, in a few short paragraphs, Ron has summarized the contents of this book. No duplication, one thing, expressiveness, tiny abstractions. Everything is there.
  ls-type:: annotation
  hl-page:: 42
  id:: 63694380-17cc-4a8c-a164-14a353988671
- Ward Cunningham, inventor of Wiki, inventor of Fit, coinventor of eXtreme Programming. Motive force behind Design Patterns. Smalltalk and OO thought leader. The godfather of all those who care about code. You know you are working on clean code when each routine you read turns out to be pretty much what you expected. You can call it beautiful code when the code also makes it look like the language was made for the problem.
  ls-type:: annotation
  hl-page:: 42
  id:: 63694484-7b3f-4ad9-ae9b-d4a07de1b299
- it’s our responsibility to make the language look simple! Language bigots everywhere, beware! It is not the language that makes programs appear simple. It is the programmer that make the language appear simple!
  ls-type:: annotation
  hl-page:: 43
  id:: 63694688-9306-4333-86f8-9801abbf3bc8
- The @author field of a Javadoc tells us who we are. We are authors. And one thing about authors is that they have readers. Indeed, authors are responsible for communicating well with their readers. The next time you write a line of code, remember you are an author, writing for readers who will judge your effort.
  ls-type:: annotation
  hl-page:: 44
  id:: 636947d5-0a34-42ec-a499-5c31a8d58c5d
- We are constantly reading old code as part of the effort to write new code. Because this ratio is so high, we want the reading of code to be easy, even if it makes the writing harder. Of course there’s no way to write code without reading it, so making it easy to read actually makes it easier to write.
  ls-type:: annotation
  hl-page:: 45
  id:: 636949f4-364d-4bfb-98b5-da1bf45ec0ca
- This was adapted from Robert Stephenson Smyth Baden-Powell’s farewell message to the Scouts: “Try and leave this world a little better than you found it . . .”
  ls-type:: annotation
  hl-page:: 45
  id:: 63694a8b-a2f6-4f4d-b0ce-e916053de9f7
- Leave the campground cleaner than you found it
  ls-type:: annotation
  hl-page:: 45
  id:: 63694aa2-c1cb-4dfe-aee0-8ab79f2f78ea