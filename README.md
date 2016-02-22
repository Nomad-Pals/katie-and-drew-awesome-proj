# katie-and-drew-awesome-proj
A awesome project for Katie and Drew to learn git together

## Resources

- [git - the simple guide](http://rogerdudler.github.io/git-guide/)
- [Git Community Book](http://book.git-scm.com/)
- [Pro Git](http://progit.org/book/)
- [Think like a git](http://think-like-a-git.net/)
- [GitHub Help](http://help.github.com/)
- [A Visual Git Guide](http://marklodato.github.com/visual-git-guide/index-en.html)

## Lesson Plan

0. Set up github.com user account, [set up ssh user key](https://help.github.com/articles/generating-an-ssh-key/), and be added to nomad-pals organization
1. clone this repository using the command line.

```
$ git clone git@github.com:Nomad-Pals/katie-and-drew-awesome-proj.git
$ cd katie-and-drew-awesome-proj
```

2. create a new branch using the command line

```
$ git branch katie-branch
$ git checkout katie-branch
```

3. create a new file and add stuff to it!
4. save changes and stage new file to git

```
$ git add file-name
$ git status
$ git commit -m "a clear message about what you did"
```

5. push to remote

```
$ git push origin katie-branch
```
