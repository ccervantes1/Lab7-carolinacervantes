---


---

<h2 id="lab-5-answers">Lab 5 Answers</h2>
<p>Question 1: There is an explicit Node constructor in the Node class, but there are two different ones. These two different constructors take different parameters. It doesn’t have an explicit constructor in the LinkedStack class, but Java supplies a default constructor. However, the constructors in the Node class do require parameters that will need to be specified.<br>
<br>
Question 2: The time complexity of each of the methods in LinkedStack as well as ReverseLines is O(1) since we are adding stuff to the head of the stack. However, the AsList method is O(n) since we are adding things elsewhere.<br>
<br>
Question 3: We could have implemented LinkedStack using an ArrayList so that the method asList uses constant time and space.<br>
<br>
Question 4: I think it is better for push and pop to return the item because it allows the user to extract the last item from the top of the stack. Returning the stack itself, however, would return the whole thing. If you return the stack itself, it will deconstruct it though.</p>
<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.</p>
</blockquote>

