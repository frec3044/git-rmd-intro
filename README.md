# Introduction to Github, Git, and Rmarkdown

We will be using GitHub classroom to distribute and submit assignments.  You accepting assignments, which creates GitHub repositories ("repos") in the frec-3044 organization https://github.com/frec-3044.  Your repos are private so that only you and and the instructor can see it.  You will be expected to make numerous commits to your repo for each assignment, including the final commit that will be graded.  This assignment walks you through the steps required to start and complete the other assistments in the course.

1. Create a GitHub user account at https://github.com, if you don't already have one.
2. Go to Canvas and get the link to accept the assignment.  Copy and paste the link in a webbrowser.  Accept the assignment.
2. Go to assignment at https://github.com/frec-3044.  Click on repository
3. Under the green "Code" button, select the local tab, and copy the https link.
4. Open Rstudio on your computer and create a new project. First, File -> New Project -> Version Control -> Git.  Paste the URL from you repo in the first box, hit tab to fill in the repo name in the second, and then use Browse to select where you want the project on your computer (I recommend having a directory on your computer where you keep all the assignments for the class).
5. Your prject will load.  Then go to New -> New File -> Rmarkdown... 
6. In the prompt use Title =  "Assignment 1" and Author = [Your name]
7. Save file as "assignment1.Rmd"
8. Commit to your Rmd file using the Git tab at the top right pane using a useful commit message. If this is the first time using Git on your computer, then you will need to provide your email (the you used to create a GitHub account) and username (your GitHub user name) to the terminal.  Paste the following in your terminal (the terminal tab is on the bottom left pane).
```
add code
```
and
```
add code
```
9. Change output to `github_document`
10. Knit (found on the top left pane) the document a to github_document
11. Commit the Rmd and md documents to git.
12. Push to your repository on GitHub.  You will be prompted for your user name (or email) and your password.  You GitHub password is [add info for setting up creds]
