## Part 1 – Debugging Scenario
> 1. The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some sense of what the failure-inducing input is. (Don’t actually make the post! Just write the content that would go in such a post)

**Student:** Hello TA, I am having a hard time debugging my code. The `capital` method of my code takes two lists of string charaters and returns all the ones that has capital 
letters in them. It was able to correctly return the list containing `"X"`  when I gave my `capital` method the lists `"X"` and `"a"`

**TA:** Hmm that is strange. What does the error output in the terminal say?

**Student:** it says "array lengths differed, expected.length=2 actual.length=1; arrays first differed at element [1]; expected:<C> but was:<end of array>" I think this 
means that the length of the array I expected from it is different from the length of the array my `capital` methods gives me. 

> 2. A response from a TA asking a leading question or suggesting a command to try (To be clear, you are mimicking a TA here.)

**TA:** What do you think that means? Is your code `capital` not returning enough items? Or is your code `capital` returning the wrong things?

**Student:** I think my code is not returning enough items. It was able to discern `"X"` is a capital letter and  `"a"` is not a capital letter. 
