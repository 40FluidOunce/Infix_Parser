# Infix_Parser
parse and solve infix equation strings

Requirements:
1. Your parser should parse an infix expression that supports the following
   arithmetic and logical operators with the specified precedencies: 
   
    !  //logical 
    
    ++ //prefix increment
    
    -- //prefix decrement 
    
    -  //negative 
    
    ^  //power 
    
    *, /, %  //arithmetic 
    
    +, -  //arithmetic
    
    >, >=, <, <=  //comparison 
    
    ==, !=  //equality comparison 
    
    &&  //logical and 
    
    ||  //logical OR
    
 2.Parse an expression given in a string format. Your program should be flexible with
  the given expressions. For instance, 1+2 is the same as 1 + 2. The user should not worry about
  writing the spaces between operands and operators. 
  
 3.Your program should check for invalid expressions, and produce meaningful error
  messages when necessary. Further, the error message should indicate whether the error
  happened (Only report the first error the program encounters and exits the program).
  
 4.Evaluate the given expressions efficiently.
 
Assumptions:

      All operands are numbers
   
      Boolean true=1 and false=0
   
      No input needed from user
  
 
