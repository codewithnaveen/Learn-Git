### What is Git ?

**Git** is a free and open source distributed **version control system** designed to handle everything from small to very large projects with speed and efficiency. 

#### Version control System 

Version control system is a system that records changes to a files or set of files over time so that you can recall specific version later.

#### How Git is different from other Version control systems

Conceptually, most other systems store information as a list of file-based changes. These other systems  think of the information they store as a set of files and the changes made to each file over time.

**Git** doesn’t think of or store its data this way. Instead, Git thinks of its data more like a series of snapshots of a miniature filesystem. With Git, every time you commit, or save the state of your project, Git basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot. 
To be efficient, if files have not changed, Git doesn’t store the file again, just a link to the previous identical file it has already stored. Git thinks about its data more like a **stream of snapshots**.

---

### Installing Git

Before you start using Git, you have to make it available on your computer. 

**Installing on Linux** Just go to : <https://git-scm.com/download/linux> 

**Installing on macOS** Just go to : <https://git-scm.com/download/linux> 
             
**Installing on Windows** Just go to : <https://git-scm.com/download/win>

---

### First-Time Git Setup

Now that you have Git on your system, you’ll want to do a few things to customize your Git environment.

##### Your Identity

`$ git config --global user.name "Naveen Singh"`

`$ git config --global user.email naveen@example.com`

`$ git config user.name`

`Naveen Singh`