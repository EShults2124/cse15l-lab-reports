# Testing and Debugging Code

My Markdown Parse Repo:
https://github.com/EShults2124/markdown-parse 

The Other Team's Repo:
https://github.com/austin-li/CSE15L-TheLunaMoths

* A link to your markdown-parse repository and a link to the one you reviewed

* For each test above: 
    * Decide on what it should produce by using either VScode preview or the CommonMark demo site
    * Showing the code in MarkdownParseTest.java for how you turned it into a test
    * For your implementation, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.
    * For the implementation you reviewed, the corresponding output when running the tests; if it passed, say so. If it didn’t pass, show the specific part of the JUnit output that shows the test failure.
* Answer the following questions with 2-3 sentences each:
    * Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.
    * Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.
    * Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

<br/>

## Snippet 1:

<br/>

Expected Output: 

```["`google.com", "google.com", "ucsd.edu"]```

Test Code:
![Image](Snippet1TestCode.png)

My Running Test: Failure
![Image](Snippet1Test.png)

My Actual Output:
![Image](Snippet1RealOutput.png)
 



## Snippet 2

```["a.com", "a.com(())", "example.com"]```

Test Code:
![Image](Snippet2TestCode.png)

My Running Test: Failure
![Image](Snippet2Test.png)

My Actual Output:
![Image](Snippet2RealOutput.png)


## Snippet 3

VSCode and CommonMark Demo Site Disagreed So I will Go With DemoSite
```["https://ucsd-cse15l-w22.github.io/"]```

Test Code:
![Image](Snippet3TestCode.png)

My Running Test: Failure
![Image](Snippet3Test.png)

My Actual Output:
![Image](Snippet3RealOutput.png)