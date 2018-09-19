# Questions

**Q1:** According to the Practice of Agile Developer ([PAD](https://media.pragprog.com/titles/pad/PAD-pulloutcard.pdf)), which are tips for making you and your team work efficiently and also give reason why? (include the number and title of the tips)

**Q2:** What are the efficient ways for handling errors?

**Q3:** Which is not the laws of *Test Driven Development(TDD)*?

- [ ] You may not write more production code than is sufficient to pass the currently failing test.
- [ ] You may not write more of a unit test than is sufficient to fail, and not compiling is failing.
- [ ] You may not write unit test until you finish all of your code.
- [ ] You may not write production code until you have written a failing unit test.
	
**Q4:** According to 7 Habits of Highly Effective Programmers, what is the meaning of "For developers, ego is the worst enemy."?  

**Q5:** If you are new to software development, whether starting as a professional or even just learning as a student, you probably find the culture intimidating. What is the key to become a great software developer?

*** 

# Answers

**A1:**

 There are many tips that helps.

38. Use stand-up meetings.
	- You get a good sense of what everyone else is working on and can bring problems out into the open easily.
 	
41. Be a mentor.
	- You motivate others to achieve better results. You improve the overall competence of your team.

42. Give others a chance to solve problems.
	- Pointing them in the right direction instead of handing them solutions will help your team to be able to learn and understand the code better.
	
43. Share code only when ready.
	- As soon as you check-in your code, it is publicly available. Your team can get confused if your code is not ready. 
 
45. Keep others informed.
	- Don’t wait for others to ask you the status of your work because it is wasting time.

**A2:**

There are many ways for handling errors.

 * Use Exceptions Rather Than Return Codes
 	- The code looks cleaner. Its logic will not be obscured by error handling so you can understand them independently.
 
 * Write Your Try-Catch-Finally Statement First
 	- This helps you define what the user of that code should expect, no matter what goes wrong with the code that is executed in the try.
 
 * Use Unchecked Exceptions and also provide context with the exception
 	- Each exception that you throw should provide enough context to determine the source and location of an error.
 
 * Define Exception Classes in Terms of a Caller’s Needs
 	- The caller must check for errors immediately after the call. When we define exception classes in an application, our most important concern should be "how they are caught".
 	
 * Define the Normal Flow
 	- Normal flow is the way that elements are displayed in a web page. The bulk of code will start to look like a clean
unadorned algorithm
 
 * Don't return or pass null
 	- Returning null from methods is bad, but passing null into methods is worse. Code with the knowledge that a null in an argument list is an indication of a problem, and end up with far fewer careless mistakes.
 	
(Ref: Clean Code book)

**A3:**

- [ ] You may not write more production code than is sufficient to pass the currently failing test.
- [ ] You may not write more of a unit test than is sufficient to fail, and not compiling is failing.
- [x] You may not write unit test until you finish all of your code.
- [ ] You may not write production code until you have written a failing unit test.

(Ref: Clean Code book)

**A4:**

&nbsp;&nbsp;&nbsp;&nbsp; You will never let your ego cause you to think only of yourself. This will not only give you a superficial type of contentment, it’ll also probably damage your team productivity as a whole.


**A5:**

&nbsp;&nbsp;&nbsp;&nbsp; The key is "practice", once you’ve solved a problem, you can, at best, iterate on that solution to improve it. That’s an important step, but to really expand your knowledge, you need to regularly find new challenges.

(Ref: [Great Software Development](https://blog.qualified.io/the-key-to-becoming-a-great-developer-8ce863d10543))

