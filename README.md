### Course No 
CSE 2100
### Course Title 
Software Development Project I

### Submitted to
Dr. Md Ali Hossain</br>
Professor</br>
Department of Computer Science & Engineering</br>
Rajshahi University of Engineering & Technology</br>

### Submitted by
Md Zobair hussain</br>
Roll: 143014</br>
Department of Computer Science & Engineering</br>
Rajshahi University of Engineering & Technology</br>
# Offline Judgment
### Purpose of the project
nowadays competitive programing is the biggest part of CSE subject. But all the judge system are online based. There are a few offline
judge available in the market like PC^2. But it can’t run in a single PC. It is vastly used to take onsite contest. So, there is no offline judge for single users. Here is the concept of my project. It is very simple for a single user to judge there code whether it is correct or not.
### Required Apparatus
Net beans or eclipse or any kind of java runnable software.
### Theory
this is a java based project. There is a editor. When we submit a code in the project, it edit the code in a while so that the code can create a txt file of output. Then we submit the original output ion the program. After that it checks the judge output & user’s output line by line whether they are same or not. If they are same it gives accepted verdict & if not, then wrong answer. Besides, it counts the total time to run the code. So that anyone can easily know
that how much time his code took to run.
### Project Description: (how it works)
1.There is a java code that takes the judge input & judge output form the user.</br>
![Project image](image/01.JPG)</br></br>
2. After that it convert the C or C++ or java code into a txt file.</br>
3. There is another C++ code called output generator that edited that txt file in a way that, it can generate the output txt file.</br>
![Project image](image/02.JPG)</br></br>
4. Another code called evaluator check the judge output & user’s output line by line. If they are same, the verdict is **Accepted**, if not, the verdict is **Wrong Answer**.</br>
![Project image](image/02.JPG)</br></br>
5. Besides it count the time taken by the code.</br>
6. At the end, it shows the verdict and the time.</br>
### Usefulness
By this app a user can easily check that his code is correct or not and the time complexity of his code. And is don’t have to get wrong answer in the main judgment.</br>
### Limitations
Here is no server, so by this app no one can take an onsite contest.</br>
### Discussion
In the next version of this app some feature will be added like it can measure the runtime error, compiler error, etc. now, this app only can compile C, C++ and JAVA code. But in the next version it will compile Pascal, Python etc.</br>
