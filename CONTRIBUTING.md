# Educative courses database
This comprises of data on courses assisting in learning technical subjects

## Procedure :
1. Fork this repository and edit as per the following rules.
2. Once the infomration is added and is in a proper structured format, create a pull request.
3. Wait for it to get merged !

### Rules:
1. ***id*** is the number assigned by your mentor
2. ***module_number*** should be an **integer**, *refer the table of contents for module numbers !*
3. ***free_courses*** - can have either **'yes'** or **'no'** against them
4. ***difficulty*** can be either one of three options- **'beginner'** , **'intermediate'** or **'advanced'**.
5. ***certification*** can be either one of three options- **'free'** (for *free courses with free certifications*), **'paid'** (either for *paid courses* or *free courses with paid certifications* ) and **'none'**.
6. Make sure that the courses you're entering into the database don't already exist there !
7. ***PRs which don't abide by the rules won't be merged***

### Reference :
You can take the reference from below example and structure your information similar to that.
   
  ```
  [
     {
       "id" :  1,
       "platform" : "scrimba",
       "free_course" : "yes",
       "course_name" : "Learn Firebase",
       "link" : "https://scrimba.com/learn/learnfirebase",
       "difficulty" : "intermediate",
       "module_number" : 2,
       "certification" : "free"
     }
]
 ```



#### Bonus :
Improve the layout and functionality of the deployed webpage - quality PRs will get merged !

