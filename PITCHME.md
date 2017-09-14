### Git*

Short intro to Git*

- Git
- GitHub
- GitHub Pages

---

### Git

- A solution to a common problem…

---?image=phd101212s.png&size=contain

---

### Git

- A brilliant version control system (VCS)
- Can track changes to any kind of file, but best support for plain text formats
  (which also happen to be more archive friendly)
- Powerful history: all versions are kept forever, every change linked to person.
- Have been around since 2005, widely used, won't go away anytime soon.
- Free & open source

---

### Git

- It's distributed:
	- Runs locally on your computer (no internet access required)…
	- … but can sync with any number of other computers, or a website such as GitHub
		- allows you to coordinate simultaneous work on a project among a distributed group of people
		  without ever being afraid of accidentally overwriting each others changes.

---

### Git

- Learning curve a little bit steep and quite long
  (lots of *terminology* and commands to be learned) 😟
	- But you can make practical use of it with only a little knowledge 😊
	- Also, it's quite hard to break something (you can always go back in history) 😊

---

### GitHub

- A popular website for *sharing* Git repositories and making it easier to work together
- Adds some optional project management tools such as issue tracking
- Also allows you do many of the things you can do with Git on the command line, but not everything
- Free for open projects, paid if you want private repositories.

---

### GitHub

- Majority of the content on GitHub is open source software
  (including [library software](https://github.com/hbunke/BibsOnGitHub)),
  but increasingly used for other projects such as
  [open](http://www.nature.com/news/democratic-databases-science-on-github-1.20719),
  [science](https://opensource.com/life/14/4/interview-arfon-smith-github),
  [constantly updated](https://github.com/openmusictheory/openmusictheory.github.io),
  [text books](https://github.com/progit/progit2), and you'll even find things
  like [my library's subject heading vocabulary](https://github.com/realfagstermer/realfagstermer)
  and of course all the [library carpentry course material](https://github.com/data-lessons/library-git)
  (If you notice a typo, we can fix it together!)

---

### GitHub Pages

- An easy way to publish a web site from a git repository.
- An example of a service that integrates very well with the Git workflow.
  There are more (such as [Authorea](https://www.authorea.com/)
  for collaborative academic paper writing).

---

### The two most important concepts

---

### The two most important concepts

- **Repository**: a collection of version-controlled files, a "project"
  - Can think of it as a a special kind of folder where all *versions* of the files are stored forever
- **Commit**
   - A commit is a version or snapshot of the repository.
   - Unlike some other systems like Google Docs, new versions are never created automatically. You must actively commit to make a new version.

---

### Enough talking...

```shell
$ git config --global user.name "First Last"
$ git config --global user.email "first.last@isp.com"
```

#### A few links for later

- [Push, pull, fork - GitHub for academics](http://www.digitalpedagogylab.com/hybridped/push-pull-fork-github-for-academics/)
- [A great Git book](http://git-scm.com/book)
- [Software Carpentry Git Novice Tutorial](http://swcarpentry.github.io/git-novice/)
