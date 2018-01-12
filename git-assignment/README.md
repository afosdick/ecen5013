### This file is for use of the university of Colorado at Boulder Embedded Systems Engineering Professional Masters Program.

### This is a free library to be used for teaching ECEN5813.

### Class:  ECEN5813 - Principles of Embedded Software

**Adding yourself to the student files**

**Steps**

1) Modify the students.json file in the ./git-assignment/students-spr2017 directory of this repo. You will need to add a unique username key and a couple of characteristics. When you add a new line, put a comma on the previous line before adding to the bottom. See example below.

  *format:*
  ```
  "identikey_username": {
      "file": "identikey_username.json",
      "name": "Your First and Last Name"
  }
  ```
  *example:*
  ```
  "afosdick": {
      "file": "afosdick.json",
      "name": "Alex Fosdick"
  }
  ```

2) Change directories into the students_<semester><year> folder and add a file with the same name as the file you put in the above code.
        ```
        $ cd ./students
        $ touch indentikey_username.json
        ```

3) In this file you are to add a block of formated test that gives details on your dream Super Power if you were a super hero. You need to add your hero name, your super power, if you have a cape (true/false), and if you have a cape, what the color of the cape would be. Example below.

  *format:*
  ```
   {
     "SuperHeroName": "your-choice-superhero-name",
     "SuperPower": "a super hero power",
     "Cape": true or false,
     "CapeColor": "color of your cape"
   }
   ```

  *example:*
  ```
   {
     "SuperHeroName": "Professor Prance",
     "SuperPower": "Amazing dance moves",
     "Cape": true,
     "CapeColor": "Blue"
   }
   ```

4) No git merge commands can be used. You must only use rebase for fixing any merge conflicts.
