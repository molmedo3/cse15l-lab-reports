# Lab Report 5

For this lab report, I will be referring to the two test in that my impementation and the implementation, provided in [lab 9](https://docs.google.com/document/d/1T0y1R0i3dNtvhbEBImuSM3YagMJmprbsDaM42PzWUjI/edit), of the  markdown-parser which had different answers.

Here is the implementation provided for lab 9:

https://github.com/nidhidhamnani/markdown-parser.git 

## Test 1
For this test I will be referring to test file 482.

Here is a link to this test file:

https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/482.md

- In order to find this test with a different result, I used vimdiff, and scrolled through until I found a file with a different output than mine. 

- For this specific test-file, my implementation was incorrect because it should have had the [/url], but my list was empty. On the other hand, the implementation provide was corrected since the output, which was [/url].

- The following image shows the output of my implementation and the one provided in which I usef vimdiff: 

   ![image](labReport5Images\vimdiff.png)

  As you can see, excluding the "hi" that was printed in mine (I was using print statements to debug and forgot to delete this particular print statement), my outputed list was empty, while the other version output did add the link to the list. 

- Here is a picture of the expected and actual outputs:

    ![image](labReport5Images\LabReport5Preview482.png)

  The correct output should be: [/uri], and as seen in the picture that shows vimdiff, my output was incorrect, while the other versions output was correct.
 -