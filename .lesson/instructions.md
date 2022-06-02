# Lab Instructions

Here we will be deleting an object from our Custom Linked List, specifically the first instance of the provided object. 

To do this we will need to implement the `remove()` method. You do not need to remove duplicates of the object. 

After the object is removed, the list should still be linked from start to finish.

The `remove()` method will return a boolean value corresponding with whether or not the object was removed or not:

- If the object is found and removed, return **true**
- If the object is not found, return **false**

## Running the Tests

The lab comes with tests that will verify the correct functionality. You can look at the test code to get a better sense of what the lab expects located in `src/test/java/CustomLinkedListTest.java`. 

To run the tests, use Maven via your shell with `mvn test` or in your IDE. The **Run** button on Replit should also run your tests. 

If you have any issues, try running `mvn dependency:resolve` and then running the tests again. 

If that doesn't work, let avi@revature.com know and do your best without the tests.

## GitHub

You can also fork and clone this lab on [GitHub](https://github.com/revature-curriculum/linked-list-deletion-lab) and submit a pull request when you're done.
