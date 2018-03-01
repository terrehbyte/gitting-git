### Gitting Git with Terry Nguyen
@terrehbyte // terry@terrehbyte.com

How do I do program better?

How do I get good at "arting"?

What makes a great VFX artist?
Note: I don't really know.


## Who's Terry?

I'm a programming instructor at AIE Seattle.

I've been alive for 22 years, but...
- programming since 2013
- teaching since 2015
- experimenting since forever

Programming has been a strong interest of mine since I got a computer in first grade.

Git was the first tool I fell in love with as a developer.


## Why Git?

Git is just really cool.

### What does it even mean?

Linus Torvalds, its creator, described Git as a...
- random pronounceable three-letter combination   <!-- .element: class="fragment" -->
- "stupid. contemptible and despicable. simple."  <!-- .element: class="fragment" -->
- "global information tracker"                    <!-- .element: class="fragment" -->
- "goddamn idiotic truckload of shit"             <!-- .element: class="fragment" -->

So, Git is basically **really cool**.


## Version Control?

It's the process by which you track and manage changes to your work.
- Tracking lets you see how it developed over time.
- Managing lets you control how the project grows.

So, let's take a quick poll.
 
How many people use version control?

What's the most common type of version control out there?
 
Making copies of your project for each change!<!-- .element: class="fragment" -->

So, let's try again.
 
How many people use version control?


## VCS
That's short for Version Control System.

It's a tool that lets you version your project automagically.
Note: Note the difference! It's a tool. It's automatic!

You've probably heard of a few of them!
 
P4 / Plastic / SVN / Git / Hg

What do they all do for you?

Version control systems automatically do versioning.
- Everyone checks in their work as it progresses!
- Leads can review work before passing it on.
- Developers can track down when bugs started.

These systems record changes to your project instead of completely new copies.
 
We get to save on space and keep a full history!*
Note: Some VCS let you keep the last four-five copies of file.

This is what you'll find in most large game studios.
 
These have been in use for ages, and it'd be hard to switch if they wanted to.

It's just easier to manage and control, which is totally fine!


## DVCS
That's short for Distributed Version Control System.

What does it mean to be a distributed VCS?
 
When you download the repo, you download everything!<!-- .element: class="fragment" -->

Traditional **VCS** keep everything on the server.
 
You, as the client, only need to download the latest version of the project.

Since you only have the latest version, you have to ask the server for everything else that you'd need.
 
This usually works out, but can be slow if you're asking for a lot of things.

With a **DVCS**, you already have everything from the first to the last change ever made!
 
You can see all of it at any time.

That's easy to understand in concept, but harder to do in practice at first.


## Using Git

Using Git revolves around two major building blocks:
 
_commits_  
_repositories_

Each **commit** represents a set of changes to your project.
 
These changes can range from new lines of code or deleting models.

Each **repository** is one big container that holds all of your commits.
 
As you add more commits, you build upon previous changes.

This means that version of your project is the culmination of your changes
over the course of the entire project.


### Collaborating
#### Branching and Merging with Git

A **branch** represents a single timeline of changes.
Note: The formal verbiage is history, but that's not important right now.

Branches allow people to work on their own sets of changes that they'll merge
together later on.

<!-- .slide: data-background="img/branch1.png" -->

The timeline of changes is important.
 
Git can combine your work by looking at what changes have occurred since the
last common commit.
Note: That's the *common ancestor*.

<!-- .slide: data-background="img/branch1.png" -->

<!-- .slide: data-background="img/branch2.png" -->

<!-- .slide: data-background="img/branch2-1.png" -->

<!-- .slide: data-background="img/branch2-2.png" -->

<!-- .slide: data-background="img/branch3.png" -->

When you merge branches together, you **merge** their changes into one timeline.
 
The result is a single unified timeline with everyone's work.


## Git Troubles
### Always Troubles Inbound

In a perfect world, Git always knows how to merge everyone's work.

Git is capable of determining what files changes and whether it can honor
everyone's work together.

When Git doesn't know, it relies on _you_ to make the call.
 
This is where stuff goes wrong. <!-- .element: class="fragment" -->

People need to look at the changes and intuit the final result.
 
Most people barely understand their own work, let alone deciphering someone else's.

Binary files (like models and textures) need to be manually compared and then
manually resolved.

Both of these problems can happen even when you're working by yourself.

Binary files quickly bloat your repository.


## Git Love
### Why even use Git?

Git is *fast* (as long as you don't have art).

Git gives you *full control*.

Git is *free to use* for commercial projects.


### Extras

<h2 style="color:black">GVFS</h2>
<!-- .slide: data-background="img/gvfs.png" -->

<h2>GitKraken</h2>
<!-- .slide: data-background="img/gitkraken.png" -->

<h2 style="color:black">@gitlost</h2>
<!-- .slide: data-background="img/gitlost.png" -->


### Gitting Git with Terry Nguyen
_Feel free to reach out for questions or even Git tips!_
 
@terrehbyte // terry@terrehbyte.com