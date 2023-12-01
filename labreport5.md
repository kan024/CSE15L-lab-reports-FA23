**Part 1 – Debugging Scenario**
Design a debugging scenario, and write your report as a conversation on EdStem. It should have:

1. The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some
sense of what the failure-inducing input is. (Don’t actually make the post! Just write the content that would go in such a post)

**Student:** Hello TA, I am having a hard time debugging my code. The `capital` method of my code takes two lists of string charaters and returns all the ones that has capital 
letters in them. It was able to correctly return the list containing `"X"`  when I have them `"X"` for list one and `"a"` for list two in one test, but not the other. 

**TA:** Hmm that is strange. What does the error say?

**Student:** it says "array lengths differed, expected.length=2 actual.length=1; arrays first differed at element [1]; expected:<C> but was:<end of array>" I think this 
means that the length of the array I expected from it is different from the length of the array my `capital` methods gives me. 
