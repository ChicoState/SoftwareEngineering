#Exercise 07: Test-Driven Development

This exercise continues from [x06 Google Test](https://github.com/ChicoState/SoftwareEngineering/tree/master/x06-GTest).

* Open the local directory where you cloned cpp-gtest.

* Edit **RandoTest.cpp** and review the syntax of the tests we used for the `shouldWorry` function, which should look like:

```TEST(/*ClassName*/, /*DescriptiveNameOfTest*/)
{
	//declare an object of the class' type

	//call the function and assert your expected outcome
}```

* Write **one** (and only one) test for the function `isDivisibleBy`:

> /**     
> * Determines if first or second are evenly divisible by the other.     
> **/

* Next, `make` the project. After it builds, run `./RandoTest`. Your test should fail (and highlight in red).

* Since you now have a failing test, you should write code *specifically to resolve that failed test*. Edit **rando.cpp** to update the solution. When you think you have resolved the failed test, repeat building the project and running the tests. If your test still fails, return and continue to fix the function until it passes.

* Once your first test passes, then you can repeat this process: write a test, run the test (with failure), write the solution, run the test (until passing).

* Repeat this process until you have decided that your tests would fail *any* wrong implementation and would pass *any* right implementation. Then, read over your implemented code and *refactor* it to make sure it uses good style, is consistent with its documentation, and fits within its class.

* This method is specifically called "Red Light, Green Light" Test-Driven Development, where the green light represents a passing test that indicates you can *go* on to the next test-develop cycle. Test-Driven Development was popularized as a part of [eXtreme Programming](https://en.wikipedia.org/wiki/Extreme_programming) by Kent Beck who summarized it as "Test-a-little, Code-a-little."

* Now that you have practiced Test-Driven Development (TDD), write one paragraph to summarize your thoughts. How did testing first impact how you thought about the problem? What do you think is the biggest benefit of TDD? What do you find most challenging? Submit your paragraph on Blackboard by the end of the day.