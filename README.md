# Description of this project (under development) 
--- 

First things first: nothing is set in stone in our repo. Here is just how I think that this project should be  <br/> organized so that we can learn, collaborate and most importantly have fun!  In case of other opinions <br/>
and suggestions we will work together to reshape it if necessary. 

Since we have decided to get our hands into a **realistic project** in the early days of the upcomming <br/>
year, we will currently focus really on **skills** and **implementation patterns**. This is important: <br/>
each one of us has different experties and specific workflow, which can turn into a trap in software <br> development since we learn specific things to accomplish very narrow tasks. Thus, we should focus on <br/>
the transferability ond exchange of our skill set, which can archieved through two distinct procedures: <br/> 
 1. **Turorials** and 2. **Puzzles**

## The scope of Tutorials

In this category, we are asked to present something that can be useful and, at the same time, it is rather <br/> unprobable that the others already have some sort of experience on it. This can be (propose additions):  

- A new library/tool that you came across and you consider important. In this case, try just to show <br/>
the most important features with some examples, aiming to trigger the interest of the others as if <br/>
this library would be yours. Afterall, it is their (ours) job to look into details if needed. This is quite <br/>
general but an example would be a framework of visualization or parsing of files.
- A Python-concept, for instance classes, list comprehensions, generators e.t.c. 
- An implementation/design pattern that you have used. This is not trivial but can reveal a lot of things <br/> 
on your personal taste of workflow and might help us when we will deal with complex projects. 

**Note:** Everything that belongs in this category should be placed in the `tutorials` directory. 

## The scope of Puzzles

I think that this category is quite self-explanatory: Here you propose a puzzle that you find <br/>
intriguing and you have or have not solved. Having gathered all our solutions we then compare <br/>
them and reach a **consencus** for our final answer. 

**Note:** Everything that belongs in this category should be placed in the `puzzles` directory. 


## Organization pattern

There is one master branch that should be considered as the **final product** of our work. <br/>
Everyone will work on their branch that I would suggest to be upstream at all times. When <br/>
someone has created a tutorial, he performs the merge of his branch with the **master**<br/>
(there is no need for code-reviewing here). For puzzles, a different pattern makes more <br/>
sense: We post the puzzle in the branch, then each one obtains a solution and reports to <br/>
our common chat that he has finished. After everyone is done or the problem is open for <br/>
more than a week, then we will **code review** all the solutions in order to choose which one <br/>
(or which combination) will be merged in the **master** as our final solution. 

In all cases, do not forget to post the **required packages** of your implementation <br/>
(I assume that everyone works with virtual-environments and if not then you should really start to)

## Git commits notations

Use the identifiers before your commit as `git commit -m "[IDENTIFIER] ... your message"`. The identifiers that  
I propose are the following:
- `[NEW] ...` : When you commit a file for the first time.
- `[ADD] ...` : When you add something new in your implementation that doesn't affect the previous version
- `[UPDATE] ...`: When you add something new in your implementation that does affect the previous version 
- `[FIX] ...` : When you fix a bug in your implementation. 

Once again, nothing is set in stone here. Propose your own commit-system so that we all are on the same page.  Note that 
I did not follow till now this pattern so everything before that point does not use strictly this pattern. 
