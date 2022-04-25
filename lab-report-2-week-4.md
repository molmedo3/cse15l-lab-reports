# Lab Report 2

This lab will show code changes made to the file [MarkdownParse.java](https://github.com/nidhidhamnani/markdown-parser/blob/main/MarkdownParse.java) to fix bugs that were found.

## Code Change 1
This code change was made as a result of the output when testing the file, [test-file.md](). This was the sympton caused by the test file:

![image](lab2Sympton1.png)

To fix this, the following changes were made to the code:

![image](lab2Bug1Fix.png)

The sympton, which was that the heap ran out of memory due to an infinite loop, was caused by the failure-inducing input, the file test-file.md, becuase it had an extra line in it causing the storing of indexes to be incorrect, because there were no brackets or parentheses found in the empty line. The error, or the bug in the code was that it did not account for any possible characters after the closing parenthesis, causing the indexes to be stored incorrectly.

## Code Change 2

The next change made was made as a result of the output when the file, [test2.md]() was tested. This was the symtpon:

![image](lab2Sympton2.png)

To resolve this, the following changes were made to the code:

![image](Lab2Bug2Fix.png)

The symptom was an index out of bounds error, resulting from the missing parentheses in the links in the test2 file (the failure-inducing input).The bug was that the code did not account for any cases in which their were no parentheses, which provoked the sympton.

## Code Change 3

This code change was provoked by the output when the test3 file was tested. This was the sympton:
