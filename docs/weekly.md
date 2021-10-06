---
path: '/what-makes-a-great-open-source-project-github-pt1/'
banner: '/images/blog-banner-ory.png'
title: >
  What makes a “Great Open Source Project” in GitHub (Part One)

teaser: >
  Not all projects within GitHub are equal - what indicates that any given open source project has wings?

seo:
  keywords: |
    github, open-source, automation, developers 
publishedAt: '2020-10-06'
author: tacurran

overline: >
  GitHub
---
## What makes a “Great Open Source Project” in GitHub (Part One)
 
In German there is a saying “Two beers is a cutlet.” It's supposed to mean, I guess, that drinking two beers has the same amount of calories as eating a deep fried breadcrumbed cutlet. I imagine that Germans coined this during the time of Lent. Fasting over beer while dreaming of mouth watering veal may lead to delusions. At least, like many things around us, the number of calories in a cutlet is hard to measure. And this article is all about measurements.

When Aeneas Rekkas aka “Hackerman” and I first started the open source Hydra product on GitHub in 2015 with the very first “commit,” we didn't  think too much about what makes a great project in the eyes of others. We just wanted to solve a problem that we had for others in the Go programming community. We did not have many metrics. Today we believe that we achieved our goal.  Yet, what makes open source software great?

At some point , probably around the time of the sale of GitHub to Microsoft, the venture capital community caught the big data virus, started trolling GitHub, and began to contact us. The normal cold call or email opener would be something similar to: “We recently came across your Great Open Source Project on GitHub” and want to learn more about it. Engineers love greatness if it applies to something that is measurable and can be improved over time thereby making it even greater, for example an automobile. Many programmers, though, are more artists than engineers. They feel more Bauhaus than Mercedes Benz. They value gestalt in visual communication, and strive towards zen-like simplicity in API design, for example Twitter. Yet engineers, developers, programmers, artists, and investors all love great things. The challenge is finding the right mix of qualitative and subjective indicators for greatness.

With datafication happening all around us, there is a struggle to find and communicate the right metrics. What data  leads to the conclusion that a project is bad, medium, good, or great? While there is no perfect answer, there are some data points that can apply to both open source and inner source software projects that reside on GitHub. Some examples include:

### Pull Requests
When something is changed in a software product, for instance a team member adds a new feature, a Pull Request or PR signifies that the feature is ready to become part of the core project and should be added. The number of PRs is a sign of life for sure, and a larger number of them indicates that a product is active. Along with GitHub Issues and Commits, PRs need to be considered as indicators of momentum. There are great PRs, ones that make significant contributions to a product, and in sum the total number of PRs may be a good indicator of importance. Great PRs on GitHub do not equal great projects.

### Stars
Giving a repository a star is similar to a “like” on other social media platforms. The verb “stargazing” refers to the process of watching for stars to be added or subtracted from a repo. The reason for this is that developers associate stars with popularity, utility, quality, or just plain brilliance. Yet a star is a star is a star as Getrude Stein might say while sipping her favorite natural plum schnapps. It's easy to read too much into any given star.

### Commits
In GitHub it helps to think about commits as points on a line. When they are all connected one can see how the code developed over time. The distance between the commits can also reveal something about the developer or the maintainer or the codebase. Many developers strive to have small commits in high frequency. For instance Kevin Goslar, maintainer of the Git Town project,  a high level command line interface for Git, recommends or even mandates this approach as a best practice for contributors.  The smaller the commit, the less work for the maintainer. While smaller commits that cover only one addition or change are often simpler and easier to merge, longer commit times do not always indicate that the contribution is larger, complex or more sophisticated. Documentation, for example, often has longer and larger commits since the authors need time to write up all those cryptic explanations and create woeful untested code examples. So commits can be a measure of goodness or efficiency, but not always. 
 
### Forks
When someone wants to make a contribution or change to a software program, the first step is to “fork” the repository to create a copy or local repository. The change’s scope is not evident without looking at other statistics such as commits, making all forks count the same.

### Issues
Creating an Issue is similar to making a comment or suggestion that can turn into a longer story. The length of time an Issue stays open or active is often a measure of a topic’s importance.  The total number of Issues in any repository can indicate numerous situations.  For instance, a high number of Issues might mean that a product is very popular and has many feature requests due to its large user base.

### Discussions
In May 2020 at the GitHub Universe Conference, GitHub announced a new platform feature called “Discussions” [GitHub Discussions] (https://github.blog/2020-05-06-new-from-satellite-2020-github-codespaces-github-discussions-securing-code-in-private-repositories-and-more).  Since open source products depend on a community of active developers, GitHub Discussions supports communication and interaction. A large and vibrant community of developers using Discussions requires a significant amount of commitment from (hopefully great) maintainers, community managers, and the community itself.

### Summary
“Good morning. You look great.” But why? Part one of this article addresses some of the metrics used in GitHub to track software projects. According to GitHub’s The State of Octoverse Report (https://octoverse.github.com/), there were 60 million new repositories created in 2020 indicating loads of activity on GitHub. Many of these new repositories contain open source projects that do not seem important if evaluated using the available GitHub metrics discussed above. However many of these have the ingredients to become great products. At Ory we welcome contributions and discussions with the community about new features. We also eagerly support other developers and teams using GitHub Discussions.
