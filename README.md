---
layout: post
---

# Hosting a Resume Online
## Purpose
This document serves as a guide on how to host a resume on online using tools such as Markdown editor, Jekyll and GitHub Pages. It also connects the principles on current Technical Writing that are presented by Andrew Etter on his book Modern Technical Writing



## Prerequisites
1. A Resume
   - formatted it in Markdown
   - make sure its tailored to your job requirements.
2. Modern Technical Writing by Andrew Etter
3. A GitHub account



## Instructions
### Hosting your resume on a static site
We will be using GitHub pages as it allows anyone to host a public website through GitHub. It is very easy to create and is also free of cost.

1. Save your resume that is formatted in markdown in a .md file and name the file index.
2. Open your GitHub account and create a new public repository.
3. Make sure that the name of the repository is in the format username.github.io and that the default branch in settings is set to main
4. Upload your resume i.e. index.md file
   

### Using Jekyll to add themes
Jekyll is a site genarator that is built-in in GitHub Pages. We can use Jekyll to generate themes for yoour website.

1. To add themes to your resume, create a "_config.yml" file
2. Inside the "config.yml" file add the line "theme: jekyll-theme-slate"
  - "slate" is the theme name. To use other themes, we can replace it with other theme names such as "minimal", "cayman", "hacker", etc.


### Animated gif
![cv-gif](https://i.makeagif.com/media/3-07-2024/QaYIpx.gif)



## More Resourses
1. Markdown Tutorial
2. [Mardown Editor: Dillinger](https://dillinger.io)
3. [Guide to GitHub Pages](https://docs.github.com/en/pages/quickstart)
4. [Guide to using Jekyll in  GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)



## Authors and Acknowledgements
Andrew Etter - *Author of Modern Technical Writing*

Billie Thompson - *Provided README Template* - [PurpleBooth](https://github.com/PurpleBooth)

Souvik Ray and Jahidul Islam - *Team Members* - helped me by peer reviewing my files and pointing out errors and mistakes. 



## FAQs
Q. Why is Markdown better than a word processor?

A.  

Q. Why is my resume not showing up?

A. There can be several reason for the resume not showing up. 
  - Error in repository name: the reporsitory name has to in the format username.github.io. If it is not in this format the page will not generate.
  - If the correct branch from which the site is generated is not selected.
  - If the CV is in the wrong file: the CV has to be in the file labelled index.md 

