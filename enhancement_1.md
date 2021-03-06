**Enhancement One: Software Design & Engineering**

This artifact represents a project that I completed in early 2019 for IT-145. The program is coded in Java and allows the user to login with a username and password. Once the credentials are authenticated the user is assigned a role. This program uses MD5 encryption to store the password information in encrypted text for security purposes, it reads the user information from a text file. The program is split into three classes, the main class (authenticationSystem.java), a class to verify credentials (credentialsFileStream.java) and the user selector class (userTypeSelector.java). All these together provide the framework for an authentication system that can assign specific permissions based on the user credentials entered.

I have included this artifact in my ePortfolio as it demonstrates my understanding of several key software design and engineering concepts. The first being modular programing, by splitting the functions of the software into multiple classes the code becomes more modular, allowing for ease of updating or modification. Modular programming also makes it possible to reuse parts of the code in different applications. Another concept I wanted to showcase was my ability to program in Java. Java is one of the most popular programming languages used today. Java also allows the software to be used across many different operating system and devices. The last concept this example highlights is that of encrypting sensitive data. My ability to understand and use encryption techniques like MD5 hashing makes my coding inherently more secure a big focus in today&#39;s world, especially for things like E-commerce.

This project originally was used via a command prompt. IT-145&#39;s assignment was to allow a user to log in via that command prompt. I have updated the program to include a GUI (graphical user interface) to make it easier to use . I did this my by using Java swing (JFRAME,JPANEL,ect.). The same classes were used for credential checking and user role assignment. (Modular Programing!) The GUI, like the command line takes input from the keyboard, encrypts the entered password and once the login button is clicked determines if that data is correct. After four invalid attempts the program terminates. I configured Joption dialog boxes to appear on incorrect and correct credentials, as well as a warning that the program is going to close due to exceeding the attempt limit.

I feel this modification meets the course objectives that I planned to meet per my ePortfolio plan. I would like to add a user creation GUI to the program but after working on this enhancement I don&#39;t feel I will have time to complete it prior to the due date. In the future I will work on that enhancement as that would round out the authorization system and could be applied to other software should it require an authentication system.

I found this project very rewarding. I started the process with simple pseudocode as the concept is not complicated. Moving forward I remembered why Java is such a challenge for me. The method declarations can be a bit confusing without much experience. That made the most difficult part of the project figuring out where to put my GUI code, and how to interface that with the existing software. Local vs global java variables can also be a bit cumbersome for me. These needed to be correct to allow for the invalid credential counter to function. With the GUI window the while loops that were used in the cli version were no longer needed, requiring global counter variables as each time the click action was captured variables declared in that method were reset.

Java is not my favorite language and the syntax presented most of my challenges. Reading through my old notes as well as Java swing and Jpane documentation helped to answer most of my questions. All in all, the enhancement took about 5 hours of work, and with what I learned during the processes the next time it will take far less time.

A big take away for me on this project is that computer programming is an iterative process that requires a solid game plan or foundation. Once you have the over all picture in sight using all available resources to complete your project helps to overcome syntax and API specific requirements.
<br>
[Software Design and Engineering Enhancement One Code](https://github.com/rspector1974/Software_design_engieering)
## ePortfolio Navigation
- [Home](index.md)
- [Enhancement Two Algorithms and Data Structures Example](enhancement_2.md)
- [Enhancement Three Databases Example](enhancement_3.md)
- [Web Development Examples](web_dev.md)
- [Code Review](code_review.md)


