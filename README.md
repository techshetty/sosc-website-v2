<p align="center">
<img src="https://raw.githubusercontent.com/haxzie/sosc-website/master/src/images/logo_main.png"/>
</p>
<h1 align="center">Sahyadri OpenSource Community</h1>

Official website for Sahyadri OpenSource Community.  
All contribution to this website including contents are made through Pull Requests. If you are new to Git and GitHub and don't know how to submit a Pull Request(PR), please refer our friendly guide on submitting your first pull request at [gitme.js.org](https://gitme.js.org).

All the contents to the website is in Markdown format, Please follow the below guidelines for any contributions.  
If you don't know how to write a markdown file, take quick look at [GitHub's markdown](https://guides.github.com/features/mastering-markdown/) guide.

## Creating Content with CLI Tool :zap:

The easiest way to create new blog posts or events is using our CLI tool:

```bash
npm run add
```

Select either "blog" or "event" from the menu and follow the prompts. The CLI will automatically create the proper folder structure and markdown template for you.

---

## Manual Creation

### Creating a new Blog Post :memo:

To manually submit a new Blog post, create a new folder in the `src/content/blogs` directory. Name the folder with date of posting and slug eg: `first-blog-post`. Add the images you want to include in your blog inside the `/public/content/blogs/<folder-name>/` directory and create a markdown file with the name `index.md`. Add the following frontmatter details into the markdown file followed by your blog post in markdown format. And finally submit a Pull Request.

PS:

- Slug is where your blog post will be available on the website and the prefix `/blog/` is required to identify it as a blog.
- Description should be written in a single line, with considerably almost 2-3 lines as viewable. Make it short and descriptive.
- Date should be in the format YYYY-mm-dd
- Your author name should be your github profile url.
- Images should be referenced as `/content/blogs/<folder-name>/image.jpg`

```
---
date: 2018-08-02
author: haxzie
name: Musthaq Ahamad
title: Second blog post
tags: blog post
cover: '/content/blogs/first-blog-post/cover.jpg'
description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure'
---

# Your blog post in Markdown
```

### Creating a new Event :triangular_flag_on_post:

To manually submit a new event details, create a folder in the `src/content/events/` directory with the name of the event. Create a new Markdown file with the name `index.md` and add any images in the `/public/content/events/<folder-name>/` directory. Follow the below format with all the details inside the markdown file and submit a Pull Request to this repository.

PS:

- Slug is where your blog post will be available on the website and the prefix `/events/` is a must to identify it as an event.
- Date should be in the format YYYY-mm-dd
- Images should be referenced as `/content/events/<folder-name>/image.png`

```
---
name: devhost:18
date: 2018-12-02
location: Seminar Hall
cover: '/content/events/devhost-18/cover.png'
---

# Other event details
And descriptions in Markdown
```

## Contributing to the Project :octocat:

We welcome Pull Requests for Bug Fixes, Missing or Fixing Documentation or even a brand new feature.  
Open an issue with your concern and we'll help you out in the way.  
While submitting the Pull Request make sure you have added proper comments in the code. Having a proper PR message will help us review your PR fast. Please follow consistent commit message throughout development, we follow Highlight with prefix guideline for commit messages where you need add a prefix text indicating what you have made changes in the commit.  
A few of the prefixes are listed below.

- FIX: Bug fix or correction
- SFIX: Security fix
- TYPO: any typo in docs or strings
- RFT: refactored code
- ADD: Added files or contents
- FEAT: implemented a new feature
- WIP: work in progress
- INIT: Initialized files to start working on.

PS: Only use the prefix before your commit followed by an understandable commit message.

# Meet our Contributors :tada:

- [haxzie](https://github.com/haxzie)
- [rumaan](https://github.com/rumaan)
- [Chaman](https://github.com/chaman-k)
- [Shravan](https://github.com/shravan1998)
- [Afroz Hussain](https://github.com/coderhawk999)
- [Nathaniel Ryan Mathew](https://github.com/nathanielmathew)
- [DominikTrojcak](https://github.com/DominikTrojcak)
- [David Brunnthaler](https://github.com/davidbru)
- [Davidgorel](https://github.com/davidgorel)
- [Pedro Féo](https://github.com/phe0)
- [Dhanush Bangera](https://github.com/dhanushp)
- [JustModo](https://github.com/JustModo)
