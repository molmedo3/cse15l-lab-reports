# Lab Report 4
For this report, two markdown-parser repositories, one being my groups and the other being one that we reviewed in lab, will be used to run a series of JUnit tests and answer questions.

Here is a link to my  [markdown-parser](https://github.com/molmedo3/markdown-parser) repository.

Here is a link to the [markdown-parser](https://github.com/richmass1/markdown-parser) that my group reviewed.

## Snippet 1 Results

The code in Snippit 1 produced the following:

![image](labReport4Images\snippet1Prev.png)

To test my implementation, I used this code to test Snippet 1:

![image](labReport4Images\snippet1Test.png)

### Test Result on my repository:

When I ran the test on my markdown-parser repository, it did not pass and I got this error:

![image](labReport4Images\snippet1TestResult.png)

The error displayed above shows that my expected output did not match my actual output.

### Test Result on reviewed repository:

When I ran the test on the reviewed markdown-parser repository, it did not pass and got this error:

![image](labReport4Images\snippet1ReviewedTestResult.png)

The error displayed above shows that the expected output did not match the actual output.

## Snippet 2 Results

The code in Snippit 2 produced the following:

![image](labReport4Images\snippet2Prev.png)

To test my implementation, I used this code to test Snippet 2:

![image](labReport4Images\snippet2Test.png)

### Test Result on my repository:

When I ran the test on my markdown-parser repository, it did not pass and I got this error:

![image](labReport4Images\snippet2TestResults.png)

The error displayed above shows that my expected output did not match my actual output.

### Test Result on reviewed repository:

When I ran the test on the reviewed markdown-parser repository, it did not pass and got this error:

![image](labReport4Images\snippet2ReviewTestResults.png)

The error displayed above shows that the expected output did not match the actual output.

## Snippet 3 Results

The code in Snippit 3 produced the following:

![image](labReport4Images\snippet3Prev.png)

To test my implementation, I used this code to test Snippet 3:

![image](labReport4Images\snippet3Test.png)

### Test Result on my repository:

When I ran the test on my markdown-parser repository, it did not pass and I got this error:

![image](labReport4Images\snippet3TestResults.png)

The error displayed above shows that my expected output did not match my actual output.

### Test Result on reviewed repository:

When I ran the test on the reviewed markdown-parser repository, it did not pass and got this error:

![image](labReport4Images\snippet3ReviewTestResults.png)

The error displayed above shows that the expected output did not match the actual output.

## Answering Questions

1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

* A small code change would be sufficient for my program to work for snippet 1 and all other related cases. I could add an if-statetment that looks and accounts for the backticks when indexing and if it does, then don't add the link to the list. If it does not, then the program will continue to run as it did before.

2. Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

* To make my program work for snippet 2 and all other related cases, I would need to make a more involved code change. I would need to keep track of the amount of nested parentheses, brackets, and escaped brackets using variables, and then make sure my program only adds the link to the list if the link contains the starting bracket and parenthesis and the ending bracket and parenthesis. This would require more in depth coding as I would need to make variables to keep track, and at least one more if statement with at least 4 conditions.

3. Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

* To make my program work for snippet 3 and all other related cases, a small code change would suffice. I could make an if-statement that checks for new-line in brackets and parenthesis, and only adds the link, not the link and the entire new line, which would take less than 10 lines.









