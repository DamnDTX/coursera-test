# PART 1 - Why not keep things simple


## Summary: Easier to deal with code:
 ° Good code organization;
 ° Updating part of it shouldn't affect other parts;
 ° Update functionality without a re-write of large portions of your code;
 ° Code Reuse; 
 ° Code should be fairly easy to test. (When we say this, we´re talking about making peaces of code that can be tested independently, even if in the end everything will be conected);


## PART 2 - Why Does Code Get Complex? 
° Hard to read code
 - Bad or inconsistent coding style
 - Hard to read variable  & function names
 - No comments or API documentation
° **Lack of High Cohesion & Low Coupling** 

### High Cohesion: 
° Is when smaller pieces of functionality are strongly related to each other within some code boundary
 - How well does that one thing stick to doing just one thing 
 

 ### Loose coupling
 ° Least possible dependency of one component on another component
  - If you change one, you do not have to change the other

  ## Part 2 Summary: 
  ° We must take care about our code, in a way that we must always think to create it for: 
    - Be editable without changing the functionality of others things;
    - Be reseanable about what it does (if something is made to act like X, it have to act like X, no X and Y)