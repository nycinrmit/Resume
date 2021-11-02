# **Creating and Hosting Your Attractive Resume on GitHub**

## **List of Contents**
+ [Introduction](#introduction)
+ [Getting Started](#getting-started)  
  + [Prerequisites](#prerequisites)
  + [Installation](#installation)
+ [Instructions](#instructions)  
  + [Create a new repository](#1-create-a-new-repository)
  + [Write resume in Markdown](#2-Write-resume-in-markdown)
  + [Use a Markdown editor](#3-use-a-markdown-editor)
  + [Make an index file](#4-make-an-index-file)
  + [Create static site by Jekyll](#5-create-static-site-by-Jekyll)
  + [Resume Demo](#resume-demo)
+ [Resources](#resources)
+ [Authors and Acknowledgments](#authors-and-acknowledgments)
+ [FAQs](#faqs)

## **Introduction**
Here are many helpful guidelines about making beautiful documents like resumes that you want to show on your website. The main tools that are recommended to you are GitHub and Markdown which are commonly used by senior programmers around the world. Throughout the GitHub Pages inside, You can begin with your stuff and achieve an online resume. Also, the book, **Andrew Etter’s “Modern Technical Writing”**, is good for you to read before you get started. The author discusses the steps of writing on the websites. He also compares different tools and methods via displaying examples which are the most useful part of the book. You can find this book in the resorces section.

## **Getting Started**

### *1. Prerequisites*

+ The first and most important tool that you need to know if you want writing on popular and modern technical documentation tools is **GitHub Pages**. Etter says, "GitHub uses a *Distributed Version Control System* which allows people to work offline and work on the same file. Also, it can keep all versions of one file in history." So DVCS is suitable to solve problems requiring collaboration.
+ You required a basic level writing knowledge about **Markdown**. The benefits of writing on **Markdown** would be discussed later.  
+ Writing and editing codes by using a **Markdown editor** are strongly recommended.  
+ If you want your resume to be more vivid to provide a nice first impression on employers, **Jekyll** is another choice which is better than Markdown.

### *2. Installation*

+ Markdown editors are commonly used in modern technical writing  environments; they can run on mainly operating systems like Windows, Mac, and Linux. You can directly go to thier official websites to download. The best rate Markdown editors are displayed in *Resources* section.
+ Jekyll is code facing which is a little bit more difficult than Markdown, you just follow the [tutorials](https://jekyllrb.com/), copy codes and paste them step-by-step in the terminal.
+ Installing a GitHub application on your desktop is unnecessary.


## **Instructions**

### *1. Create a new repository*
Before you start, make sure that you create your own github account. After you log in, you can see a “+” sign on the top right of the screen, which is beside your profile. You can click it to open the menu and  there is a "*New repository*" to allow you to create your own GitHub Page. When you click this button then it requires you to type in your repository name. This repository name is followed by your username to automatically generate a GitHub Pages site.  

### *2. The reason you should write resume in Markdown*
You should prepare a resume file in Markdown type before you start this step. But, why? According to Etter, "Markdown is the most widely used lightweight markup language by many people who may work in the IT industry all over the world. If you write your resume in Markdown, you will enjoy the benefits it brings to you, such as the cleanest syntax, limited set of features, and no defined standard." To be specific, Markdown makes everything become simpler and easier to get started. Markdown has its flavors, especially GitHub Flavored Markdown. Some helpful Markdown tutorials is provide in *Resources* section, including some common syntax in use.
 
### *3. Use a Markdown editor*
Writing with a Markdown editor can make your writing easy and convenient because the editor can provide a live view. You are able to glance at the preview generated from what you write. These two free Markdown editors, **Typora** and **Atom**, are recommended here. Typora supports instant rendering technology which means you can edit contents and see what happens next second. Another is Atom, it has abundant plug-ins.
 
### *4. Make an index file*
If you finished creating new repository and editing your resume, you should click “*Add file*” button to add a new file named **index.md** in your GitHub repository. This index.md file should be your resume formatted with Markdown. If this is the first time you process files in a repository, I strongly advise you to copy the source code from your Markdown file and paste them in this index.md file.


### *5. Create static site by Jekyll*
Etter mentions, "static websites have some excellent performances, such as speed and simplicity, and are easy to migrate. If people want to create a static website, they will use a generator, like Jekyll, just provide content and theme and then it processes everything to build a website." However,  generating your resume on the web does not need all the functions of Jekyll. Clicking *Settings* in your GitHub repository, then going down and finding *GitHub Pages*. Selecting *main* branch and Clicking "*Change theme*". This could allow you control what would be shown to your future boss. Also, come back to repository and enter "*_config.yml*" file (See gif below), add code
```
title: yourname's Resume
```
![Adding Code Title](https://github.com/nycinrmit/Resume/blob/f6d3299c5db458d36142a29de4826b7ccb110c4a/Adding%20Code.gif)  
After a few seconds, you will see fantastic appearance of your resume on <u> https://**username**.github.io</u>.  
Here is my [Resume Demo](https://nycinrmit.github.io/Resume/).

### Resume Demo
![Sample Resume Demo](https://github.com/nycinrmit/Resume/blob/1ff8fa4b147fc33af319331b197b6b76771542aa/Resume%20Demo.gif)

## **Resources**
+ [10 of the best Markdown editors](https://www.shopify.com/partners/blog/10-of-the-best-markdown-editors)
+ [Markdown tutorials](https://www.markdowntutorial.com/)
+ [Get start with a GitHub Pages](https://pages.github.com/)
+ [Video tutorials of using Jekyll](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
+ [Modern Technical Writing](https://www.amazon.ca/gp/product/B01A2QL9SS/) *by Andrew Etter*

## **Authors and Acknowledgments**
README author:  
Yucong Nie  

Group Members:  
Gurtej Boparai, Yucong Nie,  Tim Appleyard,  Jordan Unger, Dean Pistorius


## **FAQs**
### *1.Why is Markdown better than Microsoft Word?* 

Markdown is good for simple situations with no special requirements on format. The line spacing, headers, footers, and indentation are less meaningful compared to Word. This results in markdown is simple text, which is easier to convert in other types for Git management. The word does not have such benefits.


### *2. Why is my resume not showing up?*  

Please try the following methods:  
    + Correct your repository named as <u>**username**.github.io</u>  
    + Check the contents of index.md file, is it in Markdown formattion?  
    + Retry to refresh this website after a while
