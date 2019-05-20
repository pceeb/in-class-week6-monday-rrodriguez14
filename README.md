## In class exercise

1. If you wanted to reuse this program for a file that had 17 headers lines. What line of code
would you change in our program?

        Write the line of code that you will replace here:_if LineNumber > 0_

        What will be the new code? The new code will skip the first line and start at the 17th line. 

        Write the new code here:_if LineNumber > 16__

2. would happen if we don’t included `import sys` in our program?

        Write you answer here:_If we were not to include 'import sys' in our program, then we will get an error message. The message is shown below:
        NameError: name 'sys' is not defined

3. Let’s suppose that the third file that the user provides as input
has only one column. What error message will be generated?

        Write you answer here: The error message that will be generated is shown below:
                                IndexError: list index out of range

4. Our program split lines of input files (except the first file) into elements
that are tab delimitated. However, data could be split by `,` or many other
characters. In this case is a good idea to define a new variable that takes the delimiter
provide by the user. Using what you learn about `sys.argv` in this class`.
Write a variable that reads a delimiter (e.g ',') provided as the first input file.

        Write your code here:
        
        ElementList = Line.split(chosenDelimiter)
      if len(ElementList) > 0:
          MasterList[RecordNum] += (chosenDelimiter + ElementList[1]) # += adding instead of replacing
          RecordNum += 1
