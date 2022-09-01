Practical task for "Version Control with Git" course:

1. Install git and generate a pair of ssh keys. Authorize the public key on github.com.
2. Specify your user.name and user.email in git.
3. Create a new repository on github.com and clone it locally to your computer.
4. Create a file called song.txt and put there half the text of your favorite song.
5. Make a commit called "add first half of my favorite song" and send it to the server.
6. Make sure github has a song.txt file with the lyrics.
7. Using the github's web interface, add the second half of the lyrics and make a commit with the name "finish my song".
8. Make a pull in the local repository and make sure that the commit you created on github is pulled up and you have all the lyrics.
9. Add a .gitignore file to the project and configure it to hide files with the extension .db, .log and directories with the names target or bin.
10. Create a feature branch and add two commits to it
11. Merge the feature branch in master
12. Return to feature and create the arrows.txt file with the following contents:
"The ship glides gently on the waves
As day turns into night"
Make a commit.
13. Go to master. Create the arrows.txt file there and add the following text:
"One thousand burning arrows
Fill the starlit sky"
Make a commit.
14. Merge feature in master resolving the conflict: save all 4 lines in arrows.txt file in the order they were added in steps 4 and 5.
15. Create a storm branch and add a commit to the storm.txt file:
"Twenty ships with Norsemen braves
Riding the northern wind"
16. Add 2 more lines to storm.txt and make another commit:
"They left their shores at early dawn
As a red sun was rising in the east"
17. Return to master and create the pursuit.txt file with the text below:
"The warming sun returns again
And melts away the snow
The sea is freed from icy chains
Winter is letting go"
Make a commit.
18. Mark the commit with session1 tag and go to the storm branch.
19. Rebase the storm branch so that it contains the last commit from the master.
20. Make a push of your repository and make sure all commits are on github.
21. Make a new repository on github.
22. Change the remote repository into the local one so that fetch and push come to to the new repository that was created in the previous step.
23. Make a push and make sure that the second repository on the github looks the same as the first.
24. Return the remote settings to their initial state: pull and push of the first local repository lead to one remote repository on the github.
