Skip to content
This repository  
Explore
Gist
Blog
Help
@zhuhaix zhuhaix
 
You don't have any verified emails. We recommend verifying at least one email.
Email verification helps our support team verify ownership if you lose account access and allows you to receive all the notifications you ask for.
 Watch 86
  Star 189
  Fork 58,391
rdpeng/ProgrammingAssignment2
Browse files
More typos
 master
commit 7f657dd22ac20d22698c53b23f0057e1a12c09b7 1 parent 873d883
@rdpeng rdpeng authored on Apr 22, 2014
Unified Split
Showing  1 changed file  with 7 additions and 7 deletions.
 View 14  README.md
@@ -1,16 +1,16 @@
 ### Introduction
 
 This second programming assignment will require you to write an R
-function that is able to cache potentially time-consuming computations. For
-example, taking the mean of a numeric vector is typically a fast
+function that is able to cache potentially time-consuming computations.
+For example, taking the mean of a numeric vector is typically a fast
 operation. However, for a very long vector, it may take too long to
 compute the mean, especially if it has to be computed repeatedly (e.g.
 in a loop). If the contents of a vector are not changing, it may make
 sense to cache the value of the mean so that when we need it again, it
 can be looked up in the cache rather than recomputed. In this
-Programming Assignment you will take advantage of the scoping rules of the R
-language and how they can be manipulated to preserve state inside of an
-R object.
+Programming Assignment you will take advantage of the scoping rules of
+the R language and how they can be manipulated to preserve state inside
+of an R object.
 
 ### Example: Caching the Mean of a Vector
 
 @@ -76,8 +76,8 @@ Write the following functions:
     that can cache its inverse.
 2.  `cacheSolve`: This function computes the inverse of the special
     "matrix" returned by `makeCacheMatrix` above. If the inverse has
-    already been calculated (and the matrix has not changed), then the
-    `cachesolve` should retrieve the inverse from the cache.
+    already been calculated (and the matrix has not changed), then
+    `cacheSolve` should retrieve the inverse from the cache.
 
 Computing the inverse of a square matrix can be done with the `solve`
 function in R. For example, if `X` is a square invertible matrix, then
24 comments on commit 7f657dd
@sandyceracapa
sandyceracapa commented on 7f657dd on Apr 27, 2014
:)
@liliaromdhane2014
liliaromdhane2014 commented on 7f657dd on Jun 19, 2014
;)
@ashwarya33
ashwarya33 commented on 7f657dd on Jun 22, 2014
hey how do i add my code to github..i seriously m confusedd o.O
@tneubert
tneubert commented on 7f657dd on Jun 23, 2014
git add .
git commit -am "Your coimmit message"
git push origin master
@KlepikovMD
KlepikovMD commented on 7f657dd on Jun 25, 2014
I use GitHub for Windows(do not confuse with Git for Windows)
Very simple program, works without command line
@tneubert
tneubert commented on 7f657dd on Jun 26, 2014
Ok, than that is the problem. You should not work directly on the GitHub webpage except for minor changes on your code. You definitely want an IDE like RStudio where you develop your code and afterwards push it to the remote git repository which is managed by github.

Working with RStudio to write your code and push it directly to github without using git, the only way to go is copy&paste.
@PGirdhar
PGirdhar commented on 7f657dd on Jul 24, 2014
I edited the code online on GitHub webpage. Now I do not understand how to do the next step.
Commit your completed R file into YOUR git repository and push your git branch to the GitHub repository under your account.
@2051289v
2051289v commented on 7f657dd on Sep 19, 2014
Hi,

I am stuck with the same problem. I have an R file but no idea what I need to do with it to make it go to where it is supposed to go... is "MY" git repository the one I cloned? Different one? How do I push and where? Thanks...
@ebehrouz
ebehrouz commented on 7f657dd on Oct 26, 2014
Whole story is very confusing!
@Ashleshadk
Ashleshadk commented on 7f657dd on Oct 26, 2014
I am very confused . I dont know how add code into this. From where to start. and I am stuck. though I am following instructions but still confused
@angadgrover91
angadgrover91 commented on 7f657dd on Dec 21, 2014
this thing is pretty darm confusing
@soumikchaudhuri
soumikchaudhuri commented on 7f657dd on Dec 21, 2014
Simply cannot submit the assignment, the whole process is so confusing. So much time is already wasted, is not there a simpler way to achieve "submission"?
@web4zn
web4zn commented on 7f657dd on Dec 21, 2014
R programing(chinese version) for this month can't Evaluate because the Evaluation time is wrong.
i hope you will read this and fix the problem before the course close.

_skuzov ik 8 wy_psgrfm
@savithriDevaraj
savithriDevaraj commented on 7f657dd on Jan 23
I believe I commited my R program to github, but I am not sure.
After clicking a few things I see 
"commit ca5f5bcba2631beb764c7a084gg91f8be9bc173a"
Is that it?

I didn't use any git tools - just went on the browser...
Any help appreciated
@bjimmykim
bjimmykim commented on 7f657dd on Jan 28
https://github.com/bjimmykim/peer-assignment/commits/86f472e8238985f844590ae71c3ea763e24eea10/makeVector.R

86f472e8238985f844590ae71c3ea763e24eea10
@bjimmykim
bjimmykim commented on 7f657dd on Jan 28
Please, let me know how you make the submitted homework. And check the unconfirmed error.
@web4zn
 web4zn commented on 7f657dd on Jan 28
你说中文吗？

发自我的 Windows Phone
________________________________
发件人: bjimmykim<mailto:notifications@github.com>
发送时间: ‎2015/‎1/‎28 21:37
收件人: rdpeng/ProgrammingAssignment2<mailto:ProgrammingAssignment2@noreply.github.com>
抄送: web4zn<mailto:web4zn@hotmail.com>
主题: Re: [ProgrammingAssignment2] More typos (7f657dd)

Please, let me know how you make the submitted homework. And check the unconfirmed error.
…
@fcerda
fcerda commented on 7f657dd on Feb 12
This is very confusing. I need help
@freemansugar
freemansugar commented on 7f657dd on Feb 20
I did this, hope it is correct and can help those confused classmates:
1: create an account in GitHub
2: create the exactly two same files as the two given under account "rdpeng". They are README.md, and cachematrix.R.
3: in the instruction, we are asked to clone GitHub repository to my computer. But unfortunately my MacOS is too old to clone it. So I skipped this step. What I will do is I will just create the functions in my RStudio
4: Submit my assignment to my repository under my account. I will just copy the functions from RStudio into the file "cachematrix.R" under my account
5: Copy the URL link of my R functions to Coursera.
@amitnene
amitnene commented on 7f657dd on Feb 21
Thanks Prof. Just submitted the assignment.
@reactor2006
reactor2006 commented on 7f657dd on Mar 1
https://github.com/rdpeng/ProgrammingAssignment2/commit/

7f657dd
@ellynguyen
ellynguyen commented on 7f657dd on Mar 16
Thanks freemansugar , your information has cleared my confuse
@andrelmfsantos
andrelmfsantos commented on 7f657dd 22 days ago
I tried put my project but i didn't get. My url project is https://github.com/andrelmfsantos/ProgrammingAssignment2/blob/master/cachematrix.R
@AnaIngstrom
AnaIngstrom commented on 7f657dd 18 days ago
Maybe it is because you need to follow the instructions from the course Data Scientist's Toolbox?
@zhuhaix
 Markdown supported   Edit in fullscreen
Write Preview

Attach images by dragging & dropping,  selecting them, or pasting from the clipboard.
Comment on this commit
   Subscribe  You're not receiving notifications from this thread.
Status API Training Shop Blog About
© 2015 GitHub, Inc. Terms Privacy Security Contact
