# How to Host a Resume While Learning Technical Writing Principles Along the Way 

In this README, steps will be described in order to show you how to host your resume on Github while referring to Andrew Etter’s book: Modern Technical Writing. The general principles listed in the book allows you to not only host your resume, but to get a better understanding of the importance of certain steps and to provide you with tools you can use along the way. By the end of this, you should be ready to host your own resume on Github!


## Contents

  - [Getting Started](#getting-started)
  - [Instructions](#instructions)
  - [Authors and Acknowledgments](#authors-and-acknowledgments)
  - [FAQs](#faq)

## Getting Started

These instructions are intended for computer science students looking to learn how to host their resumes online, and at the same time, seeing the benefits in doing so. 

### Prerequisites

So the first thing you should have to get started is a resume formatted in Markdown. Markdown is a markup language that is great for documents like this. It’s recommended because of how tedious other files can be. In our case, take your resume. If not in markup language, it’s commonly a text document converted into a pdf. But what happens when you want to edit your resume? Now you have to discard the previous pdf and replace it with a new one. It’s single use and hardly efficient. That’s where Markdown and Github come in. Etter has mentioned that documentation should live online and he’s right. This way, updates are made instantly and you don’t have to convert files or throw them away.  

Benefits of Markdown:  
-	Easy to learn
-	Can be used in almost any documentation tool
-	Works well in formatting your documents

For more on Markdown, go to [resources](#more-resources).  

Next, you will need a Github account. This account will be where you host your resume. Github is an example of a distributive version control system(DVCS). This is another tool that allows us to make those updates I mentioned so easily. Github gives you free hosting pages which acts like a website to your resume. It's what you would call a static website, something Etter's reccomendded once again. This is also where we'll touch on a bit of Jekyll; it will help us make a theme for our site.

## Instructions
Alright, now that we've got those out of the way, we can proceed with the main process.  

1. Make a Repository  
   - On the top right hand side of the screen, under the addition icon, you can find the option to make a new repository. This will direct you to a new form to fill out to set up a repository.
   -  Name the repository: ` yourUsername.github.io ` using your username in place of 'yourUsername'. This is how you can have access to Github's free hosting page.
   - Make sure you set the repository to public so people can view your resume.
2. Upload your Resume  
   - In the main branch, upload your resume by clicking ` Add file ` and choosing the correct file.
   - Name it ` index.md `.
   - Then all you have to do is click ` commit new file ` at the end of the screen and ensure that it commits to the main branch. 
3. Set a Theme  
   - Make a new file called ` _config.yml `. This is a file that will allow you to customize your theme using Jekyll. You don't need to have anything in it, just leave it blank and it will be updated later.
   - Now from your repository page, go to `settings` on the right. Scroll down untill you see `change theme` under Github Pages and select one. The .yml file you've just create will be updated automatically with the theme you selected.
   - This is another step that corresponds to Etter's book in which he suggests having a theme helps in navigation and approachability of our site. 
4. Done!
    - Now your resume should be ready and hosted. Check it out by going to your site ` yourUsername.github.io `. You should be redirected there once you put this in your address bar. Check out a preview of my own resume down below using the steps I described!
    <img src="https://github.com/jellyglitch/jellyglitch.github.io/blob/main/Resume.gif">

### More Resources
* [Tutorial on MarkDown](https://www.markdowntutorial.com)  
* [MarkDown Overview](https://www.markdownguide.org/getting-started) 
* [Andrew Etter's Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)


## Authors and Acknowledgments

  - **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)
  - **Ahmed Kidwai** *-Provided Peer Editing-*
  - **Azat Nurlan Uulu** *-Provided Peer Editing-*
  - **Theo Gerwing** *-Provided Peer Editing-*

## FAQ

- Why is Markdown better than a word processor?  
Markdown is better because of it's simplicity. Word has many formatting options, meanwhile Markdown has just what you need in documentation. It's also very easy to learn which is a bonus!

- Why is my resume not showing up?  
There could be a couple of reasons:
  1. Your resume may not appear immediately after getting hosted. You may have to wait for a few minutes or longer for it to show up on the Github pages. 
  2. You didn't make your repository public. Go to `settings` again and at the bottom of the page you can check your repository's visibility. Make sure it's on `public`.
  3. Your resume doesn't have the right file name. Make sure it's named `index.md`.  
