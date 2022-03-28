# linux-practice
TODO: bootstrap my tools into a container.

Now? Looking at what packages I should get in my Ubuntu environment and a review of things I'm familiar with.


### Bash Scripting and High Level Overview

### Packages List
- tree
     - manages your git trees and other various things: structuring information
     - `tree .git`
- git is already installed on most linux environments (inquire: alpine containers and alpine-slim)
     - aside from basics also look at: `cat ./.git/HEAD`
     - my gitlog whopper aliased as gl: `git log --graph --abbrev-commit --date-order --format=format:'%Cblue%h%Creset%C(bold red)%d%Creset %s <%an> %Cgreen(%ar)%Creset' --all`
     -


## Bash Scripting
- Don't just put everything in /dev/null.
- comments and/or echo.
- what if your input parameter is improperly formatted? 
-    file begins with `-` or has spaces in it.
-    add `cat -- "$USERFILE"`
- Bus test: could one of your teammates look at your script and use them relatively easy.
