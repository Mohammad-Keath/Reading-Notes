- ## Linked Lists   .  [<sub>    Reference </sub>](https://canvas.instructure.com/courses/6888396/assignments/37655923/submissions/91763049)
   - For this part I will take about Linked Lists, So before starting talking about it lets get back to way we should learn it
   - What is the Big O?
       - first if you dont know about the Big O so dont wory I will explain what is the most important part of it in preef just to make it clearer to your brain
       - Big O: it is a calculation type that programmer use to calculate two important things Time and Memory, So since you are working at a small project you dont have to worry about that.
       Ok Time and Memory, Now it is very important to learn how to decrease time and memery as much as possible 
       Lets get started
       I will talk about three types of Big 0 
           - First O(1) : which takes the same time or memory away from how many n do we have 
       for example :
       let n = 5
       for (let i=0;i<6;i++){
        console.log(n)
       }
       so if the n changes the times of consoling won't change so it is static
          - Secound O(n): which increase linery when n increase
       for example:
       let n = 5 
       for (let i=0;i<\n;i++){
        console.log(i)
       }
       So in this example the times of consoling will increase when n increase
         - Third O(n^2): In this situation when the n increase the time or memory will increase more than n increasing (double)
         for example:
         let n =5
         for (let i=0;i<\n;i++){
            for (let v=0;v<\n;v++){
              console.log(i,v)
            }
         }
         So in this example it will take double time as the incresing of n
    - Why we should learn Linked Lists?
        - When we need to do a project we have to use less memory and time, So, we are learning the Linked list to know one way to decrease memory and time
     - When we should use Linked Lists?
        - We usually use it when we just expect to add or remove and we don't know how much elements we will use
    - How to use Linked list?
        - we simply just create a node which contain 2 parts (value and next) and simply linked them together by next
      
