- ## Stack and Queues   .  [<sub>    Reference </sub>](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

 1. ### Stack: 
    - imagine that you were playing logo, and you built a wall using logo blockes by putting one above the other, So when you need to degredate(unbuild) this wall you have to remove the top one then the below until you reach the lowest one and you can only access the top one, and of course the next of the top one will be the secound to delete.
    - that is exactly the same as the stack data structure so you will add nodes one by one and the last one you add will be the first one to delete or read.and you will have only one enterance to this stack witch is top, so of course the next of the top must not be null -unless you just have one node- so the next will be from top to down
    - some terms to use:
       - top: the first item to pop 
       - pop: to delete one item from top.
       - push: to add item
       - peek: the top value

 1. ### Queues: 
    - imagine that you were going to the bank to do some stuff,when you enter the bank you will take a number, and you have to wait people who came before you,and when the employee call the next they will be meaning the person who came before the one who end of course, but the one how came after the one who ends
    - that is exactly the same as the Queues data structure, so you will add node to the end and it will be the last to delete or read, and all of them will be attached by next from the Front to Rear, and because you have 2 entrance to the Queues -Frontand Rear- so you can add while you delete.
    - some terms to use:
       - Enqueue: to add an item to the Rear
       - Dequeue: to delete an item from Front.
       - Front: the first item added and the first one to delete
       - Rear : the last item added
       - Peek: the Front value