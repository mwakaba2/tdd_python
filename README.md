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
