---
title: "Tools for Contributing to the Blog"
author: Francesca Giannetti
date: January 25, 2022
summary: Set up for blogging in Jekyll
---

## VS Code

We will be using Visual Studio Code (VS Code) as our text editor for both the markdown and markup exercises. VS Code is a Microsoft project, but it's free to download and use. It has many built-in features, as well as a whole range of [community-developed extensions](https://marketplace.visualstudio.com/vscode), that make it a good choice for working in a range of computer languages and syntaxes. 

If you already have another text editor that you prefer, you are welcome to use that instead. You may also use TextEdit (Mac) or Notepad (PC), which tend to be already installed on those respective operating systems. The one significant drawback of a TextEdit or Notepad is that there is no syntax highlighing, which really does make things easier on the eyes. 

## Download and Install

Navigate to [https://code.visualstudio.com/download](https://code.visualstudio.com/download) and download the version of Visual Studio Code that is appropriate for your operating system. 

If you need additional support, you can read through the [Getting Started](https://code.visualstudio.com/docs) guide. 

Once you download VS Code, open the program and go to **File > New File**. When VS Code invites you to "select a language," type/select Markdown. 

## Markdown tutorial

I am asking you to learn the markdown syntax to contribute blog posts to the course website. The website is built using a piece of software called [Jekyll](https://jekyllrb.com/) that generates a combination of HTML, CSS, and JavaScript files that constitute the website. We don't have to learn any of that, though. Learning markdown is sufficient because it can be easily transformed into HTML(CSS and JavaScript are another story for another course ;-)). 

Once we get to the GitHub portion of our tutorial, you will be able to see more of how Jekyll sites are put together. For now, it is sufficient to know a few things that are required. 

**File names**. The file names of posts have to follow a strict format that includes the date and a title. 

Save your file as `yyyy-mm-dd-title-of-my-file.md` where the date is today's date and the title could be anything descriptive: 

- 2022-01-25-francescas-first-post.md
- 2022-01-25-how-to-write-a-blog-by-francesca.md

Notice that spaces are not allowed, and in the context of this course it would be really helpful if you could slot your name or your netID (for privacy) into the filename so I am able to tell whose post is whose from a list of file names. 

**Front matter**. In addition to the filename format, the other required bit is the front matter. The front matter contains information *about* your file.

```
---
title: Class #2 Exercise
author: Francesca Giannetti
summary: This is my first foray into markdown for web development
---
```

More on [creating posts](https://jekyllrb.com/docs/posts/) for Jekyll websites may be found in their [documentation](https://jekyllrb.com/docs/).

For the next 20 minutes or so, let's work through portions of the ["Markdown Guide."](https://www.markdownguide.org/basic-syntax/) Just spend enough time with each so that you get the gist.

- Headings
- Paragraphs
- Line Breaks
- Emphasis
- Lists
- Links
- Images

**Save your work** in VS Code often. In order to read your work in a more human readable format, and to check for errors, use the following keyboard shortcut to render your markdown as an HTML preview: 

- Windows machines > Ctrl + Shift + V
- Macs > Cmd + Shift + V


## GitHub

We will use GitHub to collaborate on the course website at <https://rutgersdh.github.io/humdata22/>. GitHub is a host for collaborative software development projects, as well as an interface for using the version control software, Git. 

[![Introduction to GitHub](https://img.youtube.com/vi/0lEtVpdYbQ4/0.jpg)](https://youtu.be/0lEtVpdYbQ4 "Introduction to GitHub")

Clicking on the video above will take you to a walkthrough of creating an account on GitHub and later of contributing to a repository or "repo." 

## Create an account

To create a GitHub account, navigate to [https://github.com/join](https://github.com/join) and fill in a valid username, email address, and password. For a username, you may want to think about whether you want a name that represents your name, or a more anonymous one. You may want to click off the email marketing box. You should also verify your account. 

GitHub provides additional documentation on [signing up for an account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account). You'll be using a [free personal account](https://github.com/pricing) to work with GitHub. Most of our work will be in public respositories, but if you are doing research that you would like to be kept private, you will also be able to set up private repositories under this account.

If you are not logged in at this point, you can navigate to the [login page](https://github.com/login). You may also consider securing your account with [two-factor authentication (2FA)](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa).

## Download GitHub Desktop

Next, you should download and install GitHub Desktop. You can navigate to [https://desktop.github.com](https://desktop.github.com) and a button for your current operating system should display automatically on the page. Once it is downloaded, you should be able to connect your GitHub account to the program. 

We will be walking through how to set up and use GitHub Desktop effectively. Using this application abstracts away many of the challenges with command-line Git.

If you need help with installing GitHub Desktop, you can review the official [Installing and configuring guide](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop). 

Once GitHub Desktop is installed, please open the program and verify it's set up correctly by cloning this repository.

## Clone this repository

You can either clone the repository directly from your GitHub Desktop application by following the [Cloning and forking repositories from GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop) documentation, or you can navigate to the root directory of this repository ([https://github.com/rutgersdh/humdata22](https://github.com/rutgersdh/humdata22)) and click the green **Code** button and select **Open with GitHub Desktop** in the dropdown menu.

GitHub Desktop should install a local copy of this repository to your machine, and you should now have access to it in GitHub Desktop. This means you can contribute to this repo or modify it for alternate use.

If you've made it this far, try adding the blog post you created in VS Code to the folder called `_posts` in our website's files. Write a commit message and push your changes. 