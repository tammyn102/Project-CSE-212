# Stacks

Stack is a linear data structure that stores items in a Last-In/First-Out(LIFO).

![](stack2.png)


Talking about performance, a proper stack implementation is expected to take O(1) time for insert and delete operations.

## Stacks in the daily

When you started collecting your Pokemons. 
And you decided to stack then all together.
Every time we put a pokemon onto the stack, we call this a **push** operation.  
We can keep stacking pokemons on top of the one before. However, circumstances can change in implementing stacks on Python, we will say that the pokemon is actually added to the **back**. When we take the pokeom off the stack, we will call this a **pop** operation. We can push and pop from the back of the stack. Pulling out from the middle of the stack is not generally allowed. Usually, the pokemon at the **front** is the first pokemon that was stacked. 

![](pokstack.jpeg)
## Implementation 
**push** - adds an element to the top of the stack:

`def push(self, item):`
        
   `self.items.append(item)`

![](push.jpeg)


**pop** - removes the element at the top of the stack

`stack = []         	 # create an empty stack`

`stack.append(‘a’)  	  	  # push 'a' to the stack`

`stack.append(‘b’)  		 # push 'b' to the stack`

`stack.append(‘c’)   # push 'c' to the stack`

`
print(stack)
`

`
['a', 'b', 'c']
`

`
stack.pop()         #pop the last element`
`

`'c'`


`stack.pop()        #pop the last element`

`'b'`

`stack.pop()        #pop the last element`


`'a'`

`stack              #check the remaining stack`

`[]`

![](pop.jpeg)

[More info](https://realpython.com/how-to-implement-python-stack/)


## Practice
[Pop practice](https://replit.com/@TammyNolasco/Poppractice)

[Solution](https://replit.com/@TammyNolasco/stackpop)

[Push practice](https://replit.com/@TammyNolasco/Push)

[Solution](https://replit.com/@TammyNolasco/Pushsolution)
