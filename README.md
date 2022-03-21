# linux-practice
Looking at what packages I should get in my Ubuntu environment and a review of things I'm familiar with.


### Packages List
- tree
     - manages your git trees and other various things: structuring information
     - `tree .git`
- git is already installed on most linux environments (inquire: alpine containers and alpine-slim)
     - aside from basics also look at: `cat ./.git/HEAD`
     - my gitlog whopper: `git log --graph --abbrev-commit --date-order --format=format:'%Cblue%h%Creset%C(bold red)%d%Creset %s <%an> %Cgreen(%ar)%Creset' --all`
