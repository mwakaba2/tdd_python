# tdd_python
Going through "Test Driven Development with Python" by Harry Percival

## Useful TDD Concepts 

### User Story ###
<p>
A description of how the application will work from the point of view of the users. 
Used to structure a functional test. 
</p> 

### Expected Failure ###
<p>
When a test fails in the way that we expected it to.
</p>

### Regression ###
<p>
When new code breaks some aspect of the application which used to work
</p>

### Unexpected Failure ###
<p>
When a test fails in a way we weren't expecting. Thise either means that we've made a mistake in  our tests, or that the test have helped us find a regression, and we need to fix something in our code.
</p>

### Red/Green/Refactor ###
<p>
Another way of describing the TDD process. Write a test and see it fail (RED), write some code to get it pass (GREEN), then Refactor to improve the implementation.
</p>

### Triangulation ###
<p>
Adding a test case with a new specific example for some existing code, to justify generalising the implementation (which may be a cheat until that point)
</p>

### Three strikes and refactor ###
<p>
A rule of thumb for when to remove duplication from code. When two pieces of code look very similar, it often pays to wait until you see a third use case, so that you're more sure about what part of the code really is the common, re-usable part to refactor out.
</p>

### The scratchpad to-do list ###
<p>
A place to write down things that occur to us as we're coding, so that we can finish up what we're doing and come back to them later.
</p>

### Test Isolation and Global State ###
<p>
Different tests shouldn't affect one another. This means we need to reset any permanent state at the end of each test. Django's test runner helps us do this by creating a test database, which it wipes clean in between each test.
</p>

### Working State to Working State (Testing Goat vs. Refactoring Cat) ###
<p>
Our natural urge is often to dive in and fix everything at once..but if we're not careful, we'll end up like Refactoring Cat, in a situation with loads of changes to our code and nothing working. The Testing Goat encourages us to take one step at a time, and go from working state to working state.
</p>

### YAGNI ###
<p>
You ain't gonna need it! Avoid the temptation to write code that you think might be useful, just because it suggests itself at the time. Chances are, you won't use it, or you won't have anticipated your future requirements correctly. 
</p>