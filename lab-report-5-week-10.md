# Lab Report 5

How I found the differences:

1.  Set up two different repositories in ieng6 with the separate implementations of MarkdownParse.java.

2. Changed the .sh file to print out the test name before and output of each commonmark spec tests. 

3. Redirected the output of the bash to separate files. In my case, I named my implementation's text file myoutput.txt and the provided implementation's output file I named theiroutput.txt.

4. To see the differences, I ran the ```diff``` comand.

```
$ diff [filepath1] [filepath2]
```

5. Choose the different outputs you want to address

Example of what the output to diff should look like:

![Image](diff-output.png)

### Test 577

My Output:

![Image](mytestfile577.png)

Provided Output:

![Image](theirtestfile577.png)

Actual Output:

![Image](actualoutput577.png)

the output should be -> []

Because this is an image, markdown parse should not add it to the list and it should not be printed.