# Contributing to Windows Driver Documentation

Thank you for your interest in the Windows driver documentation! We appreciate your feedback, edits, and additions to our docs.
This page covers the basic steps for contributing to our technical documentation.

## Sign a CLA

All contributors who are ***not*** a Microsoft employee must [sign a Microsoft Contribution Licensing Agreement (CLA)](https://cla.microsoft.com/) before contributing to any Microsoft repositories. 
If you've already contributed to Microsoft repositories in the past, congratulations! 
You've already completed this step.

## Public and private repos

The driver docs are hosted on two different repos which are then merged and updated to a single site: one repo is for contributions from the general public and one for contributions from Microsoft employees.

If you are ***not*** a Microsoft employee, work in the [public content repository](https://github.com/Microsoft/windows-driver-docs).

If you ***are*** a Microsoft employee, work in the [private content repository](https://cpubwin.visualstudio.com/drivers/_git/drivers).  

## Editing topics

We've tried to make editing an existing file as simple as possible. 
- If you're already in the repo, just navigate to the file you want to make the edits to and click the **Edit** button.  
- Alternatively, if you're viewing an MSDN page in your browser, click the **Contribute** button on the top right of the page. You will be redirected to the relevant Markdown source file in the repo, where you can click the **Edit** button. 

> **Note** We're actively moving docs into the repo, so the one you want might not be there yet.  If you don't see a **Contribute** button for a page you'd like to change, please open an issue in the repo and be sure to provide the URL of the page in question.
 
If you're using the GitHub-based public repo, GitHub automatically forks the official repo into your personal GitHub account, where you can make your changes. 

If you're using the VSO-based private repo, use the drop-down arrow next to the Commit button and select **Commit to new branch**.

Either way, when you're done, submit a pull request back to the master branch of the official repository. 
After you create the pull request, a member of the Windows Driver Documentation team will review your changes. 
If your request is accepted, updates are published to https://msdn.microsoft.com/windows/hardware/drivers.

## Making more substantial changes

To make substantial changes to an existing article, add or change images, or contribute a new article, you will need to create a local clone of the content. 
For info about creating a fork or clone, see the GitHub help topic, [Fork a Repo](https://help.github.com/articles/fork-a-repo/).

If you are using the public repo, fork the official repo into your personal GitHub account, and then clone the fork down to your local computer.  Work locally, then push your changes back into your fork.  Then open a pull request back to the master branch of the official public repo.

If you are using the private repo, clone the private repo to your local computer.  Create a new branch from master, make your changes, and then push your new branch back into the VSO private repo.  Then open a pull request back to the master branch.

## Using issues to provide feedback on Windows driver documentation

If you just want to provide feedback rather than directly modifying actual documentation pages, you can create an issue in the appropriate (public or private) repository.
At the top of a topic page you'll see an **Issues** tab. Click the tab and then click the **New issue** button. 
Be sure to include the topic title and the URL for the page you're submitting the issue for, if that page is different from the page you launched the New issue dialog from.  

Members of the Windows driver documentation team review issues regularly, and we triage, assign, and address them accordingly.

## Resources

You can use your favorite text editor to edit Markdown.  We recommend [Visual Studio Code](https://code.visualstudio.com/), a free lightweight open source editor from Microsoft.

You can learn the basics of Markdown in just a few minutes.  To get started, check out [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

