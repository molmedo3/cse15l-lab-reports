# Lab Report 2

This lab will show code changes made to the file [MarkdownParse.java](https://github.com/nidhidhamnani/markdown-parser/blob/main/MarkdownParse.java) to fix bugs that were found.

## Code Change 1
This code change was made as a result of the output when testing the file, [test-file.md](). This was the sympton caused by the test file:

![image](lab2Sympton1.png)

To fix this, the following changes were made to the code:

![image](lab2Bug1Fix.png)

The sympton, which was that the heap ran out of memory due to an infinite loop.The failure-inducing input, the file test-file.md, has an extra line in it causing the storing of indexes to be incorrect, because there no brackets or parentheses found in the empty line. The error, or the bug in the code was that it did not account for any possible characters after the closing parenthesis, causing the indexes to be stored incorrectly.