**Code for StringServer:**
![img1](4lab2.png)

**1st Screenshot of /add-message**
![img1](3lab2.png)

**Which methods in your code are called?**
- getPath()
- contains()
- getQuery()
- split()
- Integer.toString(num)
  
**What are the relevant arguments to those methods, and the values of any relevant fields of the class?**
- getPath gets the url link. The contains("/add") method checks to see if the string inside is present in the url. If it is present, then the getQuery() finds the information given, then the .split("=") method splits the information into a list of two elements. We return the second element and the number using the Integer.toString(num) method.
- when /add-message?s=Hello is being sent to the URL, the method split("=") splits the message into two parts, so that we can access the message "Hello" using parameters[1]. The Integer.toString(num) method helps print out the message "1. Hello"
  
**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.**
- the variable int num is changed with every request, and is being increased by one after every request. The variable String statements is also being changed and added onto with every request.
- When /add-message?s=Hello is being used, the variable num changes from 0 to 1. The statement string is being changed from "" to "1. Hello"

**2nd Screenshot of /add-message**
![img1](2lab2.png)

**Which methods in your code are called?**
- getPath()
- contains()
- getQuery()
- split()
- Integer.toString(num)
  
**What are the relevant arguments to those methods, and the values of any relevant fields of the class?**
- getPath gets the url link. The contains("/add") method checks to see if the string inside is present in the url. If it is present, then the getQuery() finds the information given, then the .split("=") method splits the information into a list of two elements. We return the second element and the number using the Integer.toString(num) method.
- when /add-message?s=How are you is being sent to the URL, the method split("=") splits the message into two parts, so that we can access the message "How are you" using parameters[1]. The Integer.toString(num) method helps print out the num integer. The message is now
"1. Hello
2. How are you"
  
**How do the values of any relevant fields of the class change from this specific request? If no values got changed, explain why.**
- the variable int num is changed with every request, and is being increased by one after every request. The variable String statements is also being changed and added onto with every request.
- When /add-message?s=How are you is being used, the variable num changes from 1 to 2. The statement string is being added on to. It goes from "1. Hello" to "1. Hello \n 2. How are you"
