# A quick intro to GitHub

### What's GitHub?

Github is an open-source, cloud-based, version control service for project management and it's based on Git.

### Okay, that was nonsense. What's Git, what's version control, and what's version control software?

Yeah, that was kind of word salad. Sorry!

Basically, Git is a software that automatically tracks changes in a set of files on your computer. You can use it to track and review the entire history of how a file or directory has changed, but it can only be used from the command line.

"Version control" is just programmer-jargon for the task of managing files and projects that change over time.

By extension, version control *software* is any software that helps with version control. So Git is a version control software.

### Thanks. That's a little better, but it didn't really explain what Github is?

Gah! Sorry again.

Git is a version control software. It creates the infrastructure that stores your files and tracks changes in a sort of ledger.

Here's a handy table from [geeksforgeeks](https://www.geeksforgeeks.org/difference-between-git-and-github/), which we've lightly edited, explaining explains the differences between Git and GitHub.

|     | Git                                                                     | GitHub                                                         |
|-----|-------------------------------------------------------------------------|----------------------------------------------------------------|
| 1.  | Git is a software.                                                      | GitHub is a service.                                           |
| 2.  | Git is a command-line tool                                              | GitHub is a graphical user interface                           |
| 3.  | Git is installed locally on the system                                  | GitHub is hosted on the web                                    |
| 4.  | Git is maintained by linux.                                             | GitHub is maintained by Microsoft.                             |
| 5.  | Git is focused on version control and code sharing.                     | GitHub is focused on centralized source code hosting.          |
| 6.  | Git is a version control system to manage source code history.          | GitHub is a hosting service for Git repositories.              |
| 7.  | Git was first released in 2005.                                         | GitHub was launched in 2008.                                   |
| 8.  | Git has no user management feature.                                     | GitHub has a built-in user management feature.                 |
| 9.  | Git is open-source licensed.                                            | GitHub includes a free-tier and pay-for-use tier.              |
| 10. | Git has minimal external tool configuration.                            | GitHub has an active marketplace for tool integration.         |
| 11. | Git provides a Desktop interface named Git Gui.                         | GitHub provides a Desktop interface named GitHub Desktop.      |
| 12. | Git competes with CVS, Azure DevOps Server, Subversion, Mercurial, etc. | GitHub competes with GitLab, Git Bucket, AWS Code Commit, etc. |

### But why do I want to use any of this stuff?

Great question! Here are answers, with help from [this post introducting GitHub](https://ourcodingclub.github.io/tutorials/git/).

Whether you realize it or not, you already do some kind of version control in your existing projects. It's probably manual. Maybe you follow a standard format for naming stuff. Maybe you include dates so you can easily see when it was created or last changed.

For example, when you're writing a grant application, you might start the file as:

    grant-application_20220718.docx

As you work on it, you might want to save it as a new document to avoid overwriting old versions. So you name, and rename, and rewrite, and `Save As...` until you've got:

    grant-application15_finalest2_20220718.docx

This isn't easy to read, it's tough to organize, and it's nearly impossible to triangulate where or when a change was made and what the change replaced.

Git and GitHub are solution options. Git tracks changes in a project can forget about the hard work of tracking changes in a project over time, so you don't have to. GitHub is a free online service that makes it very easy to create projects Git-friendly projects; e.g., projects in which Git can automatically track changes.

Using this workflow will allow you to easily examine old versions of a project or file, which means it also functions as a handy—and free—cloud backup.

# [Click this link to return to the assignment](./day-02)
