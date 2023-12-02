## Part 1 – Debugging Scenario
> 1. The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some sense of what the failure-inducing input is. (Don’t actually make the post! Just write the content that would go in such a post)

**Student:** Hello TA, I am having a hard time debugging my code. The `capital` method of my code takes two lists of string charaters and returns all the ones that has capital 
letters in them. It was able to correctly return the list containing `"X"`  when I gave my `capital` method the lists `"X"` and `"a"`

**TA:** Hmm that is strange. What does the error output in the terminal say?

**Student:** it says "array lengths differed, expected.length=2 actual.length=1; arrays first differed at element [1]; expected:<C> but was:<end of array>" I think this 
means that the length of the array I expected from it is different from the length of the array my `capital` methods gives me. 

<img width="1080" alt="image" src="https://github.com/kan024/CSE15L-lab-reports-FA23/assets/146775606/b1fc749c-c7a2-40b7-9466-00fb7989aa75">


> 2. A response from a TA asking a leading question or suggesting a command to try (To be clear, you are mimicking a TA here.)

**TA:** What do you think that means? Is your code `capital` not returning enough items? Or is your code `capital` returning the wrong things?

**Student:** I think my code is not returning enough items. It was able to discern `"X"` is a capital letter and  `"a"` is not a capital letter. 

**TA:** How are you checking for capital letters in your method `capital`? What methods are you using? 

**Student:** I am iterating through every string in list one using  `(letter.equals(letter.toUpperCase()))`. If a letter in list 1 equals the upper cased version of that letter, it is added to an empty array list. 

<img width="1080" alt="image" src="https://github.com/kan024/CSE15L-lab-reports-FA23/assets/146775606/894de4a2-1f0f-49a6-bbba-86282cf6d191">

**TA:** Is the `capital` method supposed to iterate over one list or 2 lists?

**Student:** Two lists, i see now. 


> 4. At the end, all the information needed about the setup including:  
> *The file & directory structure needed
<img width="564" alt="image" src="https://github.com/kan024/CSE15L-lab-reports-FA23/assets/146775606/e409866d-1630-4f55-b343-7670378a0116">


> *The contents of each file before fixing the bug  

The file `ListExamples.java` before the bug fix. This file is able to take in two string lists of characters, and return a single list of all capital letter lists in both the lists.
<img width="1080" alt="image" src="https://github.com/kan024/CSE15L-lab-reports-FA23/assets/146775606/923574cf-0332-4144-9476-71d899c0ebef">

This is the test file that tests if `ListExamples.java`  is able to correctly return the capital letters.
<img width="1080" alt="image" src="https://github.com/kan024/CSE15L-lab-reports-FA23/assets/146775606/d45c887d-e2c4-4714-b05c-ab929a11f63e">

> *The full command line (or lines) you ran to trigger the bug
>
> 
> *A description of what to edit to fix the bug




