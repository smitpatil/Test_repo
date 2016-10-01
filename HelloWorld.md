*Have Added Some COntent

##Maybe you just need to commit. I ran into this when I did:

* mkdir repo && cd repo
* git remote add origin /path/to/origin.git
* git add .
* Oops! Never committed!

* git push -u origin master
#error: src refspec master does not match any.
#All I had to do was:

* git commit -m 'initial commit'
* git push origin master

#Added One Line Here. Just Testing