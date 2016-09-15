CSCI 5828 – Fall 2016

# git-graph
Software engineering assignment 2

| Team Members | Email Id |
|--------------|----------|
| Keerthi Chikalbettu Pai | kech1404@colorado.edu |
| Pallavi Madasu | pama1314@colorado.edu |
| Sunil Baliganahalli Narayana Murthy | suba5417@colorado.edu |
| Suraj Sridhar |such2660@colorado.edu |

***

@sunil: git init

@keerthi: git add *; git commit -m "zeroth commit"; git push

@Suraj: git add *; git commit -m "First Commit"; git push

@Sunil: git add *; git commit -m "Second Commit"; git push

@pallavi: git checkout -b bug-fix;git add *;git commit -m "Third Commit";git push --set-upstream origin bug-fix

@keerthi: git checkout bug-fix; git add .; git commit -m "Forth Commit"; git push;

@Sunil: git checkout bug-fix; git merge master; git mergetool; git add *; git commit -m "Fifth commit"; git push

@Suraj: git checkout bug-fix; git add *; git commit -m "Sixth Commit"; git push

@keerthi: git checkout -b bug-fix-experimental; git add .; git commit -m "Seventh Commit"; git push --set-upstream origin bug-fix-experimental

@pallavi: git checkout bug-fix-experimental; git add *; git commit -m "Eighth Commit";git push

@Suraj: git checkout bug-fix-experimental; git add *; git commit -m "Nineth Commit"

@Pallavi: git checkout bug-fix; git merge bug-fix-experimental; git add *; git commit -m "Eleventh Commit"; git push
