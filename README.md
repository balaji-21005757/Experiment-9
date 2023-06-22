# Experiment-6

# To add , remove, retrieve an element in an Array

## Aim:
  To write a Java program to add , remove, retrieve an element in an Array.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create an array with a name of your choice.

Step 3 : Using Scanner, Input a number or a element from the user.

Step 4 : Using for loop insert,remove,retrieve the input element at the end of the array.

Step 5 : Display the appended array in the terminal.

## Program
```

import java.util.*;
class ArrayListDemo
{
public static void main(String[] args)
{
ArrayList<String> al = new ArrayList<String>();
System.out.println("Size of ArrayList: "+al.size());
//Adding the elements
al.add("Java");
al.add("JDBC");
System.out.println("Elements of first ArrayList: "+al);
ArrayList<String> al2 = new ArrayList<String>();
al2.add("EJB");
al2.add("Struts");
//Adding the both array
al2.addAll(al);
System.out.println("Elements of second ArrayList: "+al2);
//remove the element
al2.remove("EJB");
System.out.println("Elements of ArrayList after deletion: "+al2);
System.out.println("Size of ArrayList: "+al2.size());
//Retriving 2nd index element
System.out.println("The element at 2nd index is: "+al2.get(2));
}
}


```
## Output

![image](https://github.com/SaiDarshan2003/Experriment-10/assets/94692595/27a66c6f-f6b7-405e-b2d6-ccd91e8621dc)


## Result 
  We have successfully created a Java program to  add , remove, retrieve an element in an Array.
