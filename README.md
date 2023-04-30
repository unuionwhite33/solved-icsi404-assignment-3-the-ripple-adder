Download Link: https://assignmentchef.com/product/solved-icsi404-assignment-3-the-ripple-adder
<br>
This assignment builds on the previous assignment. Now that we have created a longword simulator, we can add and subtract.

Create a class called rippleAdder. You must create these two methods on this class: public static longword add(longword a, longword b) public static longword subtract(longword a, longword b)

The rippleAdder class should have no members and all methods on it should be static.

You may use a loop to create your ripple adder; you must use only operations on the bit class and longword class to implement your rippleAdder. You <strong>may not</strong> use the getSigned() or getUnsigned() methods – you must implement a rippleAdder.

You must provide a test file (rippleAdder_test.java) that implements void runTests() and call it from your main, along with your bit_test.runTests() and longword.runTests(). As with the other tests, these tests must be independent of each other and there must be reasonable coverage. You cannot reasonably test all of the billions of possible combinations, but you can test a few representative samples. Ensure that you test with positive and negative numbers.