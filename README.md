########

In class exercise

1. If you wanted to reuse this program for a file that had 17 headers lines. What line of code
would you change in our program?

        Write the line of code that you will replace here: 
        
        if LineNumber > 0 
        
        #This will enable to skip the first line.

        What will be the new code? 
         
        Write the new code here: 
        
        It would be if LineNumber > 16 
        #skipping the first 17 lines of the file

2. would happen if we don’t included `import sys` in our program?

        Write you answer here:
        
        If we did not include 'import sys' in our program, the sys module would not load making it inaccesible to me. We would           get an error message. 

3. Let’s suppose that the third file that the user provides as input
has only one column. What error message will be generated?

        Write you answer here: 
        
        The error message that would be created would be mentioning that we do not have a third file or that it would be empty           in this case, thus making it imposible to print. 

4. Our program split lines of input files (except the first file) into elements
that are tab delimitated. However, data could be split by `,` or many other
characters. In this case is a good idea to define a new variable that takes the delimiter
provide by the user. Using what you learn about `sys.argv` in this class`. Write a variable that reads a delimiter (e.g ',') provided as the first input file.

        Write your code here:
        
       ElementList = Line.split('\delim')
       


########
     
