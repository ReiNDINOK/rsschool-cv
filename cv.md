# CV
# Sergey Nenashev
**_Contact information:_** 
                                   
**Phone number:** +7 771 477 27 98   
**E-mail:** sergei_nenashev2000@mail.ru

**_About myself:_** 
Having received an education in Mathematics-Computer Science, I wanted to study programming languages and 
the work of website layout designers in more detail. Learning website writing and layout skills is a good foundation for future progress.

**_Skills:_** 
- Python Basics
- MS Word

**_Code example:_** 
Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.
```
def create_phone_number(n):
    if len(n) != 10:
        return 'invalid input'
    create_phone_number = '('
    for i in range(3):
        create_phone_number += str(n[i])
    create_phone_number += ') '
    for i in range(3, 6):
        create_phone_number += str(n[i])
    create_phone_number += '-'
    for i in range(6, 10):
        create_phone_number += str(n[i])
    return create_phone_number
```
**_Education & Courses:_**
- North Kazakhstan State University
  
  Faculty of Natural and Mathematical Sciences, 2018-2022
  
  Specialization: Mathematics-Computer Science, Bachelor's degree
- RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)
  
**_Languages:_**
- English - Intermediate
- Russian - Native
