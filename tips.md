## Coding Problem Solving Tips
Most coding exercises revolve around writing an algorithm to solve a particular problem.
In the below guide, this is what we are going to assume.

<br>

### Step 1 - Start with the things you know | The Signature
**Rationale**<br>
Usually the problem statement contains clear hints on input(s) and output(s) to the logic you need to implement.
Use that information to write up a function signature, with an empty body for now.

**Important points**<br>
- Usually you only need to name a single function and a few input arguments.
  Give them meaningful, descriptive names.
- This is a good opportunity to show that you are familiar with the general naming conventions of the language of your choice.

**Possible pitfalls**<br>
- Depending on the level on the interview, lazy or misleading names might be a red-flag.
- Incorrect usage of basic data types/structures in input and output might cause confusion down the line.

**How to improve**<br>
- Practice translating problem statements into abstract concepts such as functions and classes.
- Don't worry or care about the implementation details (yet).
- Familiarize yourself with the general naming conventions, and those that are specific to your language

<br>

### Step 2 - Solidify your understanding of the problem | The Tests
**Rationale**<br>
You need to understand the problem in order to solve it.
Having a pre-defined test suite will not only help you test your code, but will reveal any misunderstandings right at the beginning.

**Important points**<br>
- If you give the possible scenarios some thought, you might as well articulate them.
- If you articulate them, you might as well write them down.
- If you are writing them down, you might as well write them as automated tests.
- You can use this opportunity to get more information out of the interviewer with questions such as:<br>
  *"Based on these tests, do I understand the problem correctly?"*<br>
  *"Do you see a scenario, that I treat incorrectly, or I didn't think of?"*
- This is a good opportunity to show that you are familiar with and understand the value of automated tests.

**Possible pitfalls**<br>
- If you lack practice in writing these tests, and take too much time, you might end up with no useful code.<br>
  Depending on the interviewer, it might be a red-flag.
- If your tests are not meaningful, redundant, it might be a red-flag.

**How to improve**<br>
- Practice quick creation of a simple test function. (Copy, add expectation, get actual, print)
- Practice coming up with test scenarios. (Happy path, Sad path, Error path)
- Practice organizing the test scenarios in the order of logical progress.
- Be familiar with multiline editing.
- Be familiar with string formatting.

<br>

### Step 3 - Use your intuition | The Strategy
**Rationale**<br>
Almost all problems given in interviews are simple enough, that even someone without programming knowledge (e.g.: a child) could solve them.
That is called the intuitive/naive/brute-force solution.
They are usually not the most elegant, nor most performant solution out there, but *working*.

**Important points**<br>
- If you know the problem, or a similar one, you don't need to start from scratch, but be careful, don't get trapped in the programmer mindset.
- If you don't know the problem, or have no better idea, think of how you would do it on paper? How would a child do it?
- Make sure you clearly articulate your thoughts towards the interviewer, so they can understand your thought process.
- Try to use phrases that sound natural, but easy to translate to code.
- As long as you cannot explain what your code will do, there is no point in starting to write it down

**Possible pitfalls**<br>
- If your thoughts aren't organized, it will be obvious, and might be a red-flag.
- If you are talking pointlessly, in long, compound sentences, to drag the time, it will be obvious, and might be a red-flag.
  (even if you are not trying to drag the time, it's still a problem)
- If you are using too vague language, it might take too much time to explain your ideas, and might be too difficult to translate to code.

**How to improve**<br>
- Practice describing one-liners with sentences.
- Practice describing short functions in natural language.
- Practice describing the same thing as briefly as possible, while maintaining the same content.
- Use phrases such as:<br>
  *"I'll go through each..."*<br>
  *"I'll iterate through each..."*<br>
  *"I'll filter..."*<br>
  *"I'll stop if..."*<br>
  *"I'll do nothing if..."*<br>
  *"I'll keep track of..."*<br>

<br>

### Step 4 - Just write it down | The Implementation
**Rationale**<br>
If you have a working strategy in head or on paper, all you need to do is to *just* write it down as program code.
Assuming you have sufficient tests, you will get constant feedback about the correctness of your strategy.
Assuming your strategy was correct, by the end of this step, you have a working solution.

**Important points**<br>
- Your strategy might be incorrect, but even if it's mostly correct, you are in a good position.
- You should be able to naturally translate ideas to code. This comes with practice.
- Make sure you are using variable names that are meaningful and descriptive.
- Practice the previous step to the level that at this step all you really need to do is write, not to brainstorm.
- If you are not sure how to do something in the given language, but you know it's possible (e.g. how to tell if a character is a letter),
  either use pseudo-code, and ask for a hint from the interviewer, or implement it yourself.

**Possible pitfalls**<br>
- Even if your strategy is correct, if you cannot translate it, it's a problem.
- This step might reveal potential gaps in your knowledge in the programming language, it's data types and structures.

**How to improve**<br>
- Practice translating short sentences to one-liners.
- Practice translating short descriptions to short functions.
- Get intimately familiar with the main data types of your language.
- Get intimately familiar with the main data structures of your language.

<br>

### Step 5 - Don't stop, analyse | The Refactor
**Rationale**<br>
Having a working solution is not the end. It's the beginning. As a developer, writing code that does the job is the minimum requirement.
You need to critically review your solution and analyse it from different angles. Is possible, improve it.
Assuming you have a solid test suite, you are free to make changes to your code, as the tests suite will act as a safety net.
If the test suddenly start to break, you know your last change had a problem.
Improve the code and rerun the tests over and over again, until you are satisfied with your creation.

Key areas to consider:
- Readability
- Maintainability
- Performance

**Important points**<br>
- Readability issues are *usually* due to improper naming, spacing, lack of abstraction, and code organization.
- Maintainability issues are *usually* due to code duplication, lack of abstraction.
- Performance issues are *usually* due to incorrect usage of data structures, or inefficient strategy.

**Possible pitfalls**<br>
- Even if your solution is correct, it might still be considered low quality, and might not even work for certain (large) inputs
- Not caring about these points at all during the strategy design and implementation phase might lead to too much fixing to do at this stage
- Being oblivious to coding style standards, clean coding practices, and performance metrics is a red-flag.

**How to improve**<br>
- Overcome your desire to *just name things and move on*. Spend an extra 5 seconds to come up with a good name.
- Practice extraction of fields and methods.
- Practice O analysis of pseudo-codes.
- Be familiar with the time complexity of the most common operations (e.g.: adding, deleting, finding, updating elements, iteration, etc...)
