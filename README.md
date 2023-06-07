# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	To find the maximum of marks using the list method sort.
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: S AFSAR JUMAIL
RegisterNumber: 212222240004
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii) To find the maximum marks using the list method max().
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: S AFSAR JUMAIL
RegisterNumber: 212222240004
'''
def max_marks(marks):
   large = max(marks)
   return large

```

iii) To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by:S Afsar jumail
RegisterNumber:212222240004 
'''
def max_marks(list1):
    
   max=list1[0]
   for i in list1:
       if i >max:
           max=i
   return max
```
## Output:
(i)
![image](https://github.com/Afsarjumail/FindMaximum/assets/118343395/f7f36754-b50f-4f24-9046-aaf099b14c49)
(ii)
![image](https://github.com/Afsarjumail/FindMaximum/assets/118343395/f157ad17-19db-4532-a29b-13055b19fc46)
(iii)
![image](https://github.com/Afsarjumail/FindMaximum/assets/118343395/fe0de5f8-da9d-4572-9961-fbb8de4a335b)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
