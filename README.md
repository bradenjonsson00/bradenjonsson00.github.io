# bradenjonsson00.github.io

This README will describe how to host a resume on GitHub. An integral part of hosting on GitHub is having a good README. The README associated with my resume (that you are currently reading), will both explain and demonstrate what a good is.

You can see my resume [here](https://bradenjonsson00.github.io/).

## Prerequisites

 - Have a GitHub account
 - Install Jekyll (optional)
 - Have a Markdown Editor

## Introduction

### Modern Technical Writing

The book "Modern Technical Writing: An Introduction to Software Documentation" by Andrew Etter, has heavily influenced the creation of this README, and the resume associated with it. I will be highlighting principles from that book. From here on out I will be referring to it as "MTW" for short.

### Create a static site with Github pages and Jekyll

It is a common practice for people who want to distribute their resume, to do so with PDFs and WORD documents. A better practice is to create a static website. In MTW, Andrew says "You should build and host a website, not distribute PDFs … PDFs get downloaded onto hard drives and then sit there like day-old bagels, growing more and more stale until they're actively harmful. You can never update them.". This is very true, if something related to your professional experience changes, then you will be much better off being able to edit the document, no matter when it is.

If you look around, you should be able to find a website that will host your resume for free. In MTW, Andrew says "\[Static websites] have no server-side application dependencies, no databases, and nothing to install", thus they are cheap to host, so that barrier is not a concern.

Using GitHub pages is an excellent choice for hosting. GitHub is a form of a Distributed Version Control System (DVCS). As Andrew puts it in MTW: "DVCS have better performance, allow for offline work, and are superior for concurrent work on the same file. For technical writers, the most important reason to use DVCS is that developers prefer them."
Most of these features will be beneficial to someone wanting to host a resume online.

## Instructions

1. Create a GitHub repository named "[yourusername].github.io".
2. Create a markdown formatted resume file in that repository named "index.md". Once that is created you can see your resume at the URL:"[yourusername].github.io"

    Using markdown is an excellent choice for this case. In MTW, Andrew says "[Markdown is] the most widely used lightweight markup language in the world and has the cleanest syntax, but it also has a limited set of features and no defined standard.". I find this to be very true, though the limited set of features isn't an issue, as we are creating a simple document. And the "no defined standard isn't an issue, as we are using the GitHub Flavored Markdown, which is more well defined.
3. Create \_config.yml, Jekyll uses the information found in this file to change the style of your resume.
4. Edit the config file to your liking.
Here is a demonstration on how to edit your yml file:

![](EditYML.gif)

5. Create a README to explain your repository, resume, etc.
6. Fill your README with information explaining your repository, in the case of your resume, it should be fairly straightforward.

## More Resources

In MTW, Andrew says to "leverage all the wonderful writing that developers and testers produce". By this he is referring to the various guides, and books that are easily available online. Thus, in this section I have highlighted some useful resources.

Here are some links to some useful resources:
- [Markdown tutorial](https://www.markdowntutorial.com/)
- [Guide to install Jekyll](https://jekyllrb.com/docs/installation/)
- [Amazon link to "Modern Technical Writing: An Introduction to Software Documentation" by Andrew Etter](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)
- [Specifications of GitHub flavored markdown](https://github.github.com/gfm/)
- [Typoria, my Markdown editor of choice](https://typora.io/)

## Acknowledgments
- Thanks to PurpleBooth's great [README template](https://github.com/PurpleBooth/a-good-readme-template/edit/main/README.md).

- Big thanks to my group members:
  - Arjun Kaushal
  - Anas Ashfaq Mehar
  - Joshua Dueck

## FAQs

### Question: Why should I use Github?

Answer: GitHub makes it easy for you to share your work with other people, including for collaboration.

### Question: Why have the Jekyll customizations I have made not shown up yet?

Answer: It can take up to 30 minutes for the changes to take effect.
