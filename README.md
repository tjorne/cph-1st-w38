# cph-1st-w38
Exercises for week 38

Alle opgaverne kan løses ud fra den viden I har tilegnet jer fra bogen. 
I enkelte tilfælde er der behov for viden vi endnu ikke har været igennem - i disse tilfælde, vil der være et hint i opgaveformuleringen. 

Opgaverne er struktureret således at de følger kapitlerne i bogen. 

Såfremt I sidder fast ved en opgave, så tag en kort pause og prøv igen. Hvis I stadig sidder fast ved den, så hop videre til den næste.
Generelt er det bedre at I får tænkt over alle opgaverne, end at I får løst dem allesammen fuldkommen. 
Endvidere er I meget velkommen til at tale sammen om opgaverne, men det forventes at I alle koder hver jeres løsning. 


Opgaverne skal ligesom sidste uge, afleveres på moodle, via et link til jeres github repo. 



## Task 1 - functions: 
    1.a Write a function that prints an empty line and call it from setup();
    1.b Write a function that receives a string as a parameter and prints it. call this function from setup()
    1.c Write a function that receives a string called "name" and an integer called "age" and call it from setup with your own name and age. Have the function print the text "My name is \<name\>, I am <age> years old".

## Task 2 - functions return types
    2.a Look at the file TaskTwoA and fill out the missing line, using the happy boolean. 
    2.b Write a function that receives to integers as parameters and returns the sum of them.
    2.c Write a function that receives a string and returns it as uppercase. (Hint: ".toUpperCase()". Further hint: https://www.w3schools.com/jsref/jsref_toUpperCase.asp )
    2.d Write a function that receives a string and returns true if the first letter of the string is uppercase. (Hints: ".charAt(0)" and "Character.isUpperCase('a');" )

## Task 3 - Objects: 
    3.a Create a new sketch and save it by the name "Class"
    3.b Create a new tab called "Teacher" and another one called "Student"
    
    3.c in the Student tab, define the class "Student" and add 3 fields: "name", "age", "isFemale" using appropriate data types for each.
    3.d in the Student tab, add a Constructor that takes in 3 parameters with the names "tmpName", "tmpAge", "tmpIsFemale" with the same data types used in 3.c
    3.e populate the fields created in 3.c with the parameters of the constructor added in 3.d

    3.f in the Teacher tab, define the class "Teacher" and add 3 fields: "name", "age", ??? using appropriate data types for each.
    3.g in the Teacher tab, add a Constructor that takes in 3 parameters with the names "tmpName", "tmpAge", "tmp???" with the same datatypes used in 3.f
    3.h populate the fields created in 3.f with the parameters of the constructor added in 3.g

    3.i Returning to the Class tab add a setup() function and in this function, create a new object of the type Teacher and give it the name, age and ??? of your teacher. 
    3.j Also in the setup() function of Class, create two new objects of the type Student. The first one, with your own name, age and gender. The second one with the name, age and gender of the student sitting next to you. 

    3.k in the setup() function print the name of the teacher as well as the names of both students. 
        

## Task 4 (Arrays): 
    4.a Write a function that takes in an array of strings as parameter and prints each string.
    4.b Write a function that receives an integer array as a parameter and returns the sum of all elements in the array.
    4.c Write a function that receives an integer array as a parameter and returns the average value.	
    4.d Write a function that takes in an integer array as a parameter and returns the array sorted from lowest to highest value.
    

## Task 5 - Putting it all together
    For this task you should reuse the Student class from Task 3. 
        Methods of reusing the class could be: 
        - copy the Students.pde file and open it in this sketch
        - copy the content of the students tab from Task 3 and create it once more in this sketch
        - Open the task 3 and continue working in this.
        Either method is fine - it is up to you. 
        
    5.a Create an array of Students (the class created in ) with 10 elements in it. Each student must have a unique name.
    
    5.b Create a function that takes in the array from 5.a as a parameter as well as an integer. The function should return the field name and print it.

    5.c Create a similar function to that of 5.b, but instead of receiving the array and an integer, it receives the array and a string. Loop through all elements in the array until you find the element with the name received as a parameter. Then return the index of that student.
