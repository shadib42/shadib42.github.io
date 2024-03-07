---
layout: post
---

# Hosting a Resume Online
## Purpose
This document serves as a guide on how to host a resume on online using tools such as Markdown editor, Jekyll and GitHub Pages. It also connects the principles on current Technical Writing that are presented by Andrew Etter on his book Modern Technical Writing



## Prerequisites
1. A Resume that is formatted in Markdown and tailored to the specific job requirements
2. A GitHub account



## Instructions
### Hosting your resume on a static site
We will be using GitHub pages as it allows anyone to host a public website through GitHub. It is very easy to create and is also free of cost.

1. Save your resume that is formatted in markdown in a .md file and name the file index.
2. Open your GitHub account and create a new public repository.
3. Make sure that the name of the repository is in the format username.github.io and that the default branch in settings is set to main
4. Upload your resume i.e. index.md file

Andrew Etter in his book exlplains in his book to write based on your audience. Here it is assumed that the user knows what GitHub is and will have the ability to navigate through it.  
   

### Using Jekyll to add themes
Jekyll is a site genarator that is built-in in GitHub Pages. We can use Jekyll to generate themes for yoour website.

1. To add themes to your resume, create a "_config.yml" file
2. Inside the "config.yml" file add the line "theme: jekyll-theme-slate"
  - "slate" is the theme name. To use other themes, we can replace it with other theme names such as "minimal", "cayman", "hacker", etc.


### Animated gif
![cv-gif](https://i.makeagif.com/media/3-07-2024/QaYIpx.gif)



## More Resourses
1. [Markdown Tutorial](https://www.markdowntutorial.com/)
2. [Mardown Editor: Dillinger](https://dillinger.io)
3. [Guide to Markdown](https://www.markdownguide.org/getting-started/)
4. [Guide to GitHub Pages](https://docs.github.com/en/pages/quickstart)
5. [Guide to using Jekyll in  GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)



## Authors and Acknowledgements
Andrew Etter - *Author of Modern Technical Writing*

Billie Thompson - *Provided README Template* - [PurpleBooth](https://github.com/PurpleBooth)

Souvik Ray and Jahidul Islam - *Team Members* - helped me by peer reviewing my files and pointing out errors and mistakes. 



## FAQs
Q. Why is Markdown better than a word processor?

A.  There are several reasons why markdown is better,
   - Markdown is more versatile. You can use it to create websites, notes, techinicla documentations etc.
   - Markdown is very lightweight and takes up very less memory to be created which is why it is also very easily portable.
   - It can be opened by any application no matter the operating system and created on any device.
       

Q. Why is my resume not showing up?

A. There can be multiple situation where the resume might not showing up. 
  - Error in repository name: the reporsitory name has to in the format username.github.io. If it is not in this format the page will not generate.
  - If the correct branch from which the site is generated is not selected.
  - If the CV is in the wrong file: the CV has to be in the file labelled index.md 

