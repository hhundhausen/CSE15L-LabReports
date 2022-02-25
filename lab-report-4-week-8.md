# Lab Report 4 Week 8 
---

# 1) Repository Links 
- For the link to Markdown-Parse Repository : [click here!](https://github.com/hhundhausen/markdown-parse) 
- For the link to Markdown-Parse Reviewed Repository : [click here!](https://github.com/ajwboi/markdown-parse)

# 2) Snippet's Expected Outputs 
- **Snippet 1** : 
[google.com, 'google.com, ucsd.edu]

- **Snippet 2** : 
[a.com, a.com(()), example.com]

- **Snippet 3** : 
[https://www.twitter.com, https://ucsd-cse15l-w22.github.io/, https://cse.ucsd.edu/]


# 3) Code From ``MarkdownParseTest.java`` Which Turned Snippet's Into Tests 

**Snippet 1 :**

![image](Snippet_1.png)

![image](Snippet1_Redo.png)

**Snippet 2 :**

![image](Snippet_2.png)

![image](Snippet2_Redo.png)

**Snippet 3 :** 

![image](Snippet_3.png)

![image](Snippet3_Redo.png)


# 4) Implementations 

# Reviewed ``MarkdownParse.java`` Implementation: 
- **Image of the corresponding output when running tests from the reviewed ``MarkdownParse.java``:** 
![image](ReviewedSnippet_Redo.png)

**Specific *Snippet 1* Output Revi:** 
- Snippet 1's test doesn't pass. Attached below is an image from the specific part of the JUnit output that shows the test failure.

![image](ReviewedSnippet1_Redo.png)

**Specific *Snippet 2* Output :** 
- Snippet 2's test doesn't pass. Attached below is an image from the specific part of the JUnit output that shows the test failure.

![image](ReviewedSnippet2_Redo.png)

**Specific *Snippet 3* Output :** 
- Snippet 3's test doesn't pass. Attached below is an image from the specific part of the JUnit output that shows the test failure.

![image](ReviewedSnippet3_Redo.png)


# My ``MarkdownParse.java`` Implementation :

- **Image of the corresponding output when running tests from my ``MarkdownParse.java``:** 
![image](MyCodeTest_Redo.png)


**Specific *Snippet 1* Output :** 
- Snippet 1's test doesn't pass. Attached below is an image from the specific part of the JUnit output that shows the test failure.

![image](OwnCode_Snippet1_Output.png)

***Snippet* 1 Output Free-Response Question :** 

For my program to work for **Snippet 1**, I think a small change to my code is needed. Additionally, the test for **Snippet 1** outputs a ``StringIndexOutOfBoundsException`` failing on line 28 due to pairs of nested brackets in the ``Snippet1.md`` file. Therefore, it is possible to resolve the issue by making the program determine the most internal pair of brackets and reassigning it to the open and closing bracket variables. 

**Specific *Snippet 2* Output :** 
- Snippet 2's test doesn't pass. Attached below is an image from the specific part of the JUnit output that shows the test failure.

![image](OwnCode_Snippet2_Output.png)

***Snippet 2* Output Free-Response Question :** 

For my program to work for **Snippet 2**, I think a small change to my code is needed. Furthermore, the test for **Snippet 1** generates a ``StringIndexOutOfBoundsException`` on line 28 for a similar reason as for **Snippet 1**, the pairs of nested brackets found in **Snippet 2.md**. Therefore, it is possible to resolve the exception similarly to  **Snippet 1**, having the program determine the most internal pair of brackets and reassign them to the open and closing bracket variables. 


**Specific *Snippet 3* Output :** 

- Snippet 3's test doesn't pass. Attached below is an image from the specific part of the JUnit output that shows the test failure.

![image](OwnCode_Snippet3_Output.png)

**Snippet 3 Output Free-Response Question :** 

In order for my program to work for **snippet 3**, I think a bigger code fix is needed. The problem is that the program is able to print the lines For my program to work for **Snippet 3**, I think a bigger code fix is needed. Additionally, the test for **Snippet 1** outputs a ``StringIndexOutOfBoundsException``on line 28 due to a significant issue. In a **.md** file, the program can print any number of lines with any amount of spacing between brackets and parenthesis, as long as there is a link with the correct syntax following. The following example demonstrates this: 

``This line is a line. ``

``[this title text is really long and takes up more than`` 
``one line``

``and has some line breaks](``
    ``https://www.twitter.com``
``)``

``[another link!](some-page.html)``

Therefore, I think that a change to more than ten lines of code would be necessary. 

    




    


   