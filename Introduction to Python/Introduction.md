## Introduction 

### **Q) Why Python**

### *Python is a **DYNAMIC TYPED LANGUAGE***

Let take an example 
|C Language | Comments | Python | Comments
|--|--|--|--|
| int i = 10; | Will Work | i = 10 | Will Work
| i = "Hello"; | Error | i = "Hello" | Will Work 
| i = 15.5;  | Error |  i =15.5 | Will Work

C and  C++ will verify datatypes at compile time so once the datatype is defined we cant change the assigned values.
But Python is a Dynamic Typed Language Type checking will done at run time.

### *Python is a **USER FRIENDLY SYNTAX***

Let take an example 

| C Language | Python |
|-- |--|
|#include<stdio.h>|  print("Hellow World"); |
int main()
{
	printf("Hello World");
	Return 0;
} 
in C language we need to write lot of code to print a simple message but when we use python it is very easy 

### *Python **READABILITY***

**C language** 

    #include<stdio.h>    
    int main()
    {
    int i  = 10;
    while(i>=0}
    {printf("i=%d\n",i);
    i -= 1;
    }
    return 0;
    }
The above code will work evey we dont give any **indentation** because the compailer will know where statment start and ends due to this the above code works 
now we will see in python.

**Python** 

If we do same as above code the code will break. let see the below example.

    i=10
    while i>=10:
    print("i=",i)
    i-=1
but this code will not work because python is **indentation** sensitive   language.

    i=10
    while i>=10:
        print("i=",i)
        i-=1
this code will work By default python will fource the developer to maintain readabulity 


### *Python **DEVELOPER PRODUCTIVITY***

in C language if we need to find  a key in array we need to write lenghty of code by when we use pyton with few lines of code we can find the key. let see the below example 
**C Language** 

    int main()
    {
	    int arr[5] = {10,20,30,40,50};
	    int  i, key = 50, flag = 0;
	    for(i= 0; i < 5; i++)
	    {
		    if(arr[i] == key)
		    {
			    flag =1;
			}
			if(flag == 1)
			{
				prinf("Key Found");
			}
			else
			{
				printf("Key Not Found");
			}
		}
		Retrun 0;
    }
    
**Python Language**

    arr = [10,20,30,40,50]
    key = 50
    if key in arr:
	    print("Key Found")
	else: 
		print("Key Not Found")

How it is possible with python, There are too may lib. which will help to make code easy
this will improve the **developer productivity**.

### **Q) What we can do with Python**

 - GUI
 - Web Development
 - Scripting
 - Image Processing
 - AI
 - Machine Learning 

### **Q) Who uses Python**

 - Google for their serch engine algo.
 - Youtube for video sharing alog.
 - Dropbox use Python 
etc...

### Python Drawback
**Speed** 
 - C, C++ execution speed is **high** , because both are low level language it will directly hardware 
 - Python execution sepeed is **low** because python will convert code to **IL** and it will convert to low level language.


## **Summary :**
Why To Use **Python** ? 
 - DYNAMIC TYPED LANGUAGE
 - USER FRIENDLY SYNTAX
 - READABILITY
 - DEVELOPER PRODUCTIVITY

