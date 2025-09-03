Assignment Prompt:

Step 1
The steps below are not very detailed on purpose. There’s very little you can do (if anything at all) to break the Linux server, so use the resources above and experiment and explore.

Log in to Linux and launch Vim by typing vi. You are now in a text editor, but start typing and see what happens.
If you get frustrated, hit esc and type :. Notice where the : appears. Then type q! after the : (i.e., :q!) and see what happens.
Enter vi again, and press control-z (on Mac, you might have to press fn-control-z.) It should look similar what happened above; i.e., you should be at the bash command prompt.
Type fg and hit enter.
Answer question 1 below.

Step 2
Quit Vim and run this command from shell: vi hello.sh. Using vimsheet.comLinks to an external site. if necessary, figure out how to edit the file so that it contains the following lines:

#!/bin/bash

# Report the time and date in a friendly manner.

echo "Today is $(date)"
echo "and it's going to be a great day!"
Save the file and exit Vim. Try to execute the file by running ./hello.sh – it shouldn’t work. Assuming it doesn’t, use your work in prior labs to troubleshoot why you cannot execute this script. Fix the problem so that you can execute the script by typing ./hello.sh.
