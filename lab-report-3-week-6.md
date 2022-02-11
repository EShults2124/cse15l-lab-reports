# Copy whole directories with scp -r:

* Show copying your whole markdown-parse directory to your ieng6 account

```
$ scp -r [to-be copied folder path] [account]:~[new directory name]
```

After inputing the command, your terminal will look similar to this:
![Image](CSE-Lab3-screenshot1-part1.png)

It will go on for a bit depending on how much is being copied over and it end with all the files that are in the directory being listed:
![Image](CSE-Lab3-screenshot1-part2.png)

* Show logging into your ieng6 account after doing this and compiling and running the tests for your repository

![Image](CSE-Lab3-screenshot2.png)

The process to compiling and running a test is very similar to running a normal file, there are just a few extra specifications.

To compile:
```
$ javac -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar [java file name 1].java [java file name 2].java ...
```

To Run:
```
$ javac -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar [compiled file name to run]
```

The commands and result should look similar to this:
![Image](CSE-Lab3-screenshot3.png)

* Show (like in the last step of the first lab) combining scp, ;, and ssh to copy the whole directory and run the tests in one line.

## Things To Do

Choose one of the Group Choice Options (1-3) from week 5. Complete it for yourself (if you haven’t already), and take the relevant screenshots listed below for your choice. Create a post with a few sentences of description about each. Do this for only one of these options for your lab report.