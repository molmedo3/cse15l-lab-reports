# Lab Report 5

For this lab report, I will be referring to the two test in that my impementation and the implementation, provided in [lab 9](https://docs.google.com/document/d/1T0y1R0i3dNtvhbEBImuSM3YagMJmprbsDaM42PzWUjI/edit), of the  markdown-parser which had different answers.

Click [here](https://github.com/nidhidhamnani/markdown-parser.git) to get access to the implementation provided for lab 9.
 

## Test 1
For this test I will be referring to test file 482.

Click [here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/482.md) to access the test file.

## How did I find this test file with a different result? 

- In order to find this test with a different result, I used vimdiff, and scrolled through until I found a file with a different output than mine. 

## Expected ouptut
- Here is a picture of the preview:

    ![image](labReport5Images\LabReport5Preview482.png)
    
    using this picture, the expected output should be 
    ```
    [/url]
    ```
## Actual output

- The following image shows the output of my implementation and the one provided in which I used vimdiff: 

   ![image](labReport5Images\vimdiff.png)

  As you can see, excluding the "hi" that was printed in mine (I was using print statements to debug and forgot to delete this particular print statement), my outputed list was empty, while the other version output did add the link to the list. 


- For this specific test-file, my implementation was incorrect because it should the result should have been 
 ```
[/url]
``` 
but mine was:
```
[]
```
On the other hand, the implementation provided was correct since the output matched the expected result.

## Fix
- This is a screenshot of where I think the bug is:
![image](labReport5Images\labReport5Fix482.png)

   In order to fix my implementation, in the screenshot above, it shows how I am checking for the open parenthesis. In that "else-if" statement, I think I am going an index too far, so instead of 
   ```
   else if (!markdown.substring(closeBracket+1,closeBarcket+2).equals("("))
   ```

it should be: 

```
else if (!markdown.substring(closeBracket,closeBarcket+1).equals("("))
```


# Test 2
For this test I will be referring to test file 483.

Click [here](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/483.md) to access the test file.

## How did I find this test file with a different result? 

- To find this test with a different result, I used vimdiff, and scrolled through until I found this file with a different output than mine. 

## Expected ouptut
- Here is a picture of the preview:

    ![image](labReport5Images\LabReport5Preview483.png)
    
    using this picture, the expected output should be 
    ```
    []
    ```
## Actual output
- The following image shows the output of my implementation and the one provided in which I used vimdiff: 

   ![image](labReport5Images\vimdiff.png)

  As you can see, excluding the "hi" that was printed in mine (I was using print statements to debug and forgot to delete this particular print statement), my output was 
  ```
  []
  ``` 
  while the other version's output was:
  ```
  [./target.md]
  ```
- For this specific test file, my implementation was correct, while the other version's implementation was incorrect since it did add the link when it should not have been added.

## Fix

- This is a screenshot of where I think the bug is in the provided implementation:

![image](labReport5Images\labReport5fix483.png)

In order to fix the provided implementation, in the screenshot above, it is checking for the open and closed brackets. In the highlighted part, we can add an if statement checking for any characters in between the brackets. If it does not have any, then do not add it the link, if it does, add the link. 




 