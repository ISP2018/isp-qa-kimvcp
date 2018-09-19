# 1) According to the Practice of Agile Developer(PAD), which are tips for making you and your team work efficiently and also give reason why? (give the number and title of the tips)

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

# 2) What are the efficient ways for handling errors?

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
 	
 	
 
 	(Ref. clean code book)

