## Answers

12. List
  a. student.name
  b. student["Grad Year"]
  - c. student.greeting()
  - d. student["Favorite Teacher"]["name"]
  - student.courseLoad[0]

13. 
      - a. '32' ( 2 gets typecasted to same string representation for string concatenation)
      - b. 1 (there's no string subtraction in js so '3' gets typecasted and treated as a number)
      - c. 3 ( null being a "falsy value" is typecasted as 0)
      - d. '3null' (string datatype has higher priority and null is typecasted into "null")
      - e. 4 (true is typecasted to 1)
      - f. 0 (false and null both get typecasted into 0s as numbers)
      - g. '3undefined' (undefined doesn't have 0 or 1 representation like booleans but it does have a
    toString method which is concatenated to 3)
      - h. NaN ( no way to typecast into number and string subtraction doesn't exist)

14. 
    - a. true ('2' get typecasted into 2 and compared against 1 as numbers)
    - b. true (both strings, compared lexiographically)
    - c. true ( == operator typecasts '2' into 2 and compared them)
    - d. false (strict operator, no typecasting)
    - e. false (true gets typecasted to 1)
    - f. true (Boolean(2) is the same as true)

15. The == operator ignores the datatype of the two values being compared and performs implicit
    typecasting if necessary to equate the values. The === operator is more strict, does no
    typecasting and compares the actual stored values keeping different datatypes in mind.
16. Code
17. [2,4,6] (modifyArray is called with doSomething as callback. It iterates through the given array
    and calls and performs the doSomething function on each element and modifies the array in
    place.)
18. Code   
19. 
    1
    4
    3
    2

 



