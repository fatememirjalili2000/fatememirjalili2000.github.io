---
layout: posts
title: Final Exam.2
---


Python:


-**Question 1**: length of string 

-**Correct Solution**:
{
    
 
def string_len(str): 

    count = 0    

    for i in str: 

        count += 1


    return count

}

-**Question tip**: 

-**Question 2**:copying a string in a buf

-**Correct Solution**:

-**Question tip**:


-**Question 3**:counting a character in a string 

-**Correct Solution**:

{
    

def char_count(pch,a):

    d=string_len(pch)

    c=0

    for i in range (d):

        if (pch[i] == a ):

            c=c+1 
 

    return c


}



-**Question 4**: counting longest sequence of a character

-**Correct Solution**:

-**Question tip**:


-**Question 5**: counting a pattern of characorts in a stirng

-**Correct Solution**:



def count_pattern (arr , cd ):

    n=len(arr)

    m= len(cd)

    s=0

    for i in range(n-m+1):

        p=""

        for j in range(i,i+m):

            p+= arr[j]

            if(p== cd ):

                s+= 1

    print (s)


    return s


-**Question tip**: مهم ترین قسمت سوال پیدا کردن درست از بازه های مناسب برای حلقه هاست



-**Question 6**:applying a function

-**Correct Solution**:

-**Question tip**:


-**Question 7**:changing a class

-**Correct Solution**:




def __init__(self, id, name):

       self.id = id

       self.name = name



class student:

   def __init__(self, id, name):

       self.id = id

       self.name = name


def ghange_student_name (s , name ):

    s.name = name 



def changge_stident_id (s,id ):

    s.id = id 



-**Question tip**: چگونگی تعریف  یک کلاس درون تابع


-**Question 8**: converting a class to string

-**Correct Solution**:


def student_tostring(s):

    p=""

    p+= s.id 

    p+=':'

    p+=s.name 

    print(p)

    return p 



-**Question tip**:


-**Question 9**:creating a class

-**Correct Solution**:




def create_student(id, name):

    p= student(id , name )



    print(p.id , p.name)

    return(p.id , p.name)



-**Question tip**:


-**Question 11**:memory

-**Correct Solution**:

-**Question tip**:



-**Question 12**:memory

-**Correct Solution**:

-**Question tip**:


---

