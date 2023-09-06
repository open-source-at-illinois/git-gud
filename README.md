## What is Git?
[**Git**](https://git-scm.com) is a distributed version control system that allows a developer to track changes made to files in their projects. Teams of developers can use Git to collaborate on a single project at scale. This is made possible by branching, which allows developers to make specific changes to eventually be merged into the `main` branch of the codebase (or Git repository).

In simpler terms,
> Git is like a time machine for your development work, letting you save different versions of your projects and work on them with friends without messing things up. It's a tool that helps you keep track of changes and work together smoothly.

## Basic Terminology

- **repository (repo)**
	- When working on a project with collaborators, a Git repository acts as a special folder on your computer that records all the changes you make to your files. 
	- This makes it simple to see what everyone has done and combine your work. It resembles a computerized version of journal that records everything you and your collaborators write in it.

- **branch**
	- A branch in Git is comparable to a different project route. Similar to how you may write two different stories in various notebooks, it enables you to work on different aspects of your project without interfering with the primary one. 
	- Conventional name for the primary branch of a project is `main`.

![Illustration to explain branches](https://rogerdudler.github.io/git-guide/img/branches.png)
- **HEAD**
	- Think of the "HEAD" in Git as a special marker that, like a bookmark in a book, indicates which version of your project you are currently viewing. It aids in keeping track of your progress throughout the course of your assignment.
	- HEAD is a reference variable used to denote the most current commit of the repository in which you are working. When you add a new commit, HEAD will then become that new commit.

- **Remote**
	- Git remote is similar to a link to a shared copy of your code (repository) on the internet or another machine. It allows you and your collaborators to work on the same code from multiple locations, ensuring that everyone has the most recent modifications.
	- A remote in Git is **a common repository that all team members use to exchange their changes**.
