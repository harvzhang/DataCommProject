Shawn Button Project 2
How to run program:

makefile is provided
type make to remake the project
type imap to start the communication

Dificulties:
I had problems with figuring out how to get my ssl connection working correctly.
Once I began having these problems I spent hours experimenting with ssl and 
just trying to get the examples on the website to work and I was just having a 
real bad time. The biggest difficulty I continue to have on these projects is using
windows as my developing machine, especially this one since I felt like much of the
tutorials would have been easier for me to test out on linux, and along those lines
I should have spent more time in labs to work on it sooner rather saving it for last
minute. I started working on this project much too late for how complex
it was for me. I will need to get better at estimating my time and sticking
to schedules.


Tests:
First stage Command Line tests:
input	expected result				pass?
n	cout message and return to prompt	y
p	"				"	y
h	Display the list of commands and return	y
r	Error Message				y
r-1	Error Message				y
ras	Error Message				y
r1	cout message wait for another return	y
r10	"				    "	y
r11	Error Message				y


Second stage SSL Connection
connection established with server		n

Imap Connection					n

GIT LOG
commit 7a9c70da3c22e1edf17fefaf4977db69265a0db2
Author: Shawn Button <smb1717@rit.edu>
Date:   Fri Jan 11 22:21:47 2013 -0500

    Final commit with program working somewhat well for what I accomplished while working on windows and codeblocks.


commit dba2a0c4063a98be1b10128bb8d4129a3f60cb0d
Author: Shawn Button <smb1717@rit.edu>
Date:   Fri Jan 11 19:58:52 2013 -0500

    Example openssl


commit e898b90f51af608970ad58ef5de1a192f1559ba0
Author: Shawn Button <smb1717@rit.edu>
Date:   Fri Jan 11 18:06:44 2013 -0500

    Adding Open ssl library along with a begining user interface to allow me to test and the begining of trying to create the command pattern for the cli's commands.


commit 6903b1d54e7448e631d99640595bc629681edb6a
Author: Shawn Button <smb1717@rit.edu>
Date:   Thu Jan 10 01:51:17 2013 -0500

    Initial commit with my code block project


commit 8fe8ffa2d7ceb612647fa16c6d6c26c8a1cce411
Author: Shawn Button <smb1717@rit.edu>
Date:   Thu Jan 10 01:09:36 2013 -0500

    Getting rid of initial readme


commit 87e5109573fd387cf75134f2d403ab5177cb8743
Author: Shawn Button <smb1717@rit.edu>
Date:   Thu Jan 10 01:02:51 2013 -0500

    Data comm project 2 IMAP


commit 7585cc94511b775196cd86d003d191e95f5fa6d4
Author: smbutton <smb1717@rit.edu>
Date:   Wed Jan 9 21:59:14 2013 -0800

    Initial commit
