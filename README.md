# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
        get the name using command arguments

### Step 2: 
         now read the content in the file
 
### Step 3: 
         use.split()

### Step 4:  
         now read the no.of words in file

### Step 5: 
          print number of words present in the given file

### Step 6: 
          end the program

## PROGRAM:
     #developed by S.Subashini`
     ```
     import sys
     count = {]
     with open(sys.argv[1],'r') as f:
         for word in line.split():
             if word not in count:
                count[word] = 1
             else:
                 count[word] +=1
      ```
### OUTPUT:
       


![argument](https://user-images.githubusercontent.com/119404951/215097790-45c76195-2df8-4608-98b9-0cafac387a49.jpg)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
