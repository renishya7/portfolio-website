---
title: "Host your website"
description: "Learn how to host your website for free."
date: "2023-03-15"
banner:
  src: "../../images/cloud.jpg"
  alt: ""
  caption: ''
categories:
  - "Tutorial"
keywords:
  
  - "GitHub Pages"
  - "Gatsby Cloud"
  - "Website"
---
Building your first website is a huge step; the next step is finding a hosting platform for your website. There are many things you would want to consider before choosing a hosting platform — how big of a project it is, the project's longevity, expected traffic to your website, and more. Depending on your project needs, you might want to go for a free or paid plan. Since my portfolio website began as a hobby and a way to document my technical journey, I went for free hosting. Even if your project is big, if you're new to the whole game, test your concept with a free plan.

I have tested hosting my website on GitHub Pages and Gatsby Cloud. Both are free. They were my obvious choices since I have my repository on GitHub, and I used a Gatsby template to build my website.  


## Before you start

You need the following to get started:

- a Git repository
- a static website

For this purpose, I have used the following:

- [GitHub](https://github.com/)
- [Gatsby template](https://renishya.com/create-a-portfolio-website/)


## Hosting on GitHub Pages
1. In your GitHub repository, navigate to **Settings**.
2. Under **General**, provide your repository a name.
3. Optionally, provide a social preview for your website.<br/> 
   The social preview appears when you share your website link in a chat or a social platform.

4. Navigate to **Pages**.
5. Under **Build and deployment**, select a source:
- **GitHub Actions**
- **Deploy from a branch** <br/>
  If you select Deploy from a branch, you need to provide the branch. In most cases, it is the main branch.
6. Under **GitHub Pages**, click **Visit site** to visit your live site.<br/>
   **Tip**: There might be a delay in site deployment for the first time.

## Hosting on Gatsby Cloud

1. In your Gatsby Cloud, click **Add a site**.
2. Under Import from a Git repository, select your Git provider.<br/>
   A new browser window opens to grant Gatsby Cloud permission to access your repository.
3. Provide access to all repositories or only select ones.
4. In your Gatsby Cloud, select the repository you want to import and click **Import**.
5. Under **Basic Configuration**, provide your site name.
6. Click **Next** and then **Build Site**.<br/>
   You are redirected to your site page, where you can see the status of your build.
7. Click your site link to to visit your live site. 