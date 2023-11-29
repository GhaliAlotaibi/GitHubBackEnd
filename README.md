# Conflicts
## 1- Background
### 1.1- Conflict:
A merge conflict is a situation that arises when two or more developers make changes to the same line of code in a shared file. Git, the distributed version control system, is unable to automatically resolve these conflicts, which leaves developers to manually decide how to merge the changes.
### 1.1.1- How Conflicts Happen:
![image](https://github.com/leeu4/conflict/assets/123780953/216a3cde-e566-4d5d-b112-8a20f33eff6e)
### 1.2- Git & GitHub:
Git is a version control system that allows developers to track changes in their code. GitHub is a web-based hosting service for git repositories. In simple terms, you can use git without Github, but you cannot use GitHub without Git.
### 2- Scenario:
Suppose two developers, Alice and Bob, are working on the same codebase. Alice modifies line 10 of a file to add a new feature, while Bob removes that line to fix a bug. When Git tries to merge their changes, it encounters a conflict because both developers have modified the same line.
### 2.1- Resolving merge conflicts:
#### To resolve a merge conflict, developers need to manually review the changes and decide how to incorporate them. There are two main approaches:


  1. Manual merge: Developers manually edit the file to combine the changes from both branches. This can be tedious and error-prone, especially for complex changes.

  2. Automatic merge: Developers use merge tools or graphical user interfaces (GUIs) to guide them through the conflict resolution process. These tools highlight the conflicting changes and allow developers to choose how to merge them.
     
### 2.2- Preventing merge conflicts:
#### To minimize the occurrence of merge conflicts, developers should:


  * Work on different branches: If multiple developers are working on the same codebase, they should use separate branches to avoid conflicts.

  * Communicate effectively: Developers should communicate with each other about their changes to avoid overlapping modifications.

  * Use version control tools: Version control tools like Git can help track changes and identify potential conflicts early on.

Merge conflicts are an inevitable part of collaborative software development, but by following best practices and using appropriate tools, developers can minimize their occurrence and resolve them efficiently.
