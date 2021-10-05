# why-github
This repository aims to help decision makers understand the reasons to use the GitHub platform as an orgaisational support system.
## 1. Background

## 2. Code Organisation

## 3. Process Landscape

In business operations, especially in high tech startups, lean processes and frugal budgets often dictate decisions. Perfection has a price, and if it comes at the cost of execution speed, perfection often falls to the wayside. While "robotic process automation" became popular with the business pundits and consultants over the past few years, the software industry has been deeply invovled in workflow automation for over a decade now. This repository explains the benefits that "GitOps" process automation delivers to the broad [Ory community](https://slack.ory.sh/) of open source contributors and adopters involved with the main [Ory Projects](https://www.ory.sh/products), as well as the Ory [core team](https://github.com/orgs/ory/people). 

It's important to note one of Ory's internal principles: 
> "If a development process can be automated it will be, and if not, it will be changed to a process that can be automated." The beauty of recursion! 

Ory uses numerous automation approaches to eliminate manual, repetitive tasks and integrate web applications to improve productivity including:
- Software testing and release management such as [Coveralls](https://coveralls.io)  and [CircleCI](https://circleci.com)
- [GitHub Actions](https://github.com/features/actions) or scripts that automate workflows in GitHub
- Third party automation tools such as [Zapier](https://zapier.com) or [n8n](https://n8n.io) that add new workflow processing outside GitHub
- Real-time metrics and notifications that use GitHub repositories such as [Upptime](https://github.com/upptime/upptime)
- Open source web analytics platform Matomo that tracks and generates reports on engagement rates with online media

##### Software Quality Assurance
Open Source Software undergoes scrutiny from many different constituants e.g., contributors, users, and security specialists. Thus having automated processes that provide data about the health of a software build is an essential form of communication. Automation tools such as Coveralls inform about code coverage tests while CircleCI  provides a fully automated release pipeline.

##### Interchange
[@OryCorp](https://github.com/ory-corp) uses this Action to publish tweets from a GitHub repository, rather than sharing log-in credentials across the team. Instead of tweeting directly, a team member can submit a pull request for review, thereby encouraging more data interchange and enabling everyone to create a Twitter post.

##### Delegation
Ory uses [Zapier](https://zapier.com) to integrate Google Gmail and GitHub. Inbound emails to our general [office@ory.sh](mailto:office@ory.sh?subject=Cool%20Automation&body=Hey%20Ory,%20I%20loved%20the%20article,%20thanks!) mail address are labeled according to their content, which automatically triggers a new issue in GitHub in a corresponding repository matching the label, e.g. Human Resources, including adding the content of the email,  for instance subject/body, and assigning the issue to the appropriate team member. 

##### Administration
Ory uses [Zapier](https://zapier.com) and basic scripts to rename and store inbound invoices. Inbound invoices are received, reviewed and forwarded electronically to our web-based accounting software Datev for automatic posting. Using Zapier, we have set this forwarding action as a trigger to download and save the invoice to our Google Drive ‘Inbound Invoices’ folder and rename it with a simple script (by date, vendor, amount etc.) in accordance with our internal file naming convention.

> "Our focus on automating and standardizing processes lets us double down on the really critical stuff needed to build the Ory business"

-[Jared Preston](https://github.com/jaredpreston), former Managing Director @ Ory

##### Engagement
Slack release automation gives transparency over our release process, both internally and with the community. Notifications give our community realtime oversight over every single release. Ory also uses [GreetBot](https://github.com/codebuddies/greetbot) to greet new members in our Slack channel and give them a warm welcome, point them to all relevant documentation and other places that might be interesting to them. It also sends them a couple of emojis to let them know whats up. 👋 Yo

##### Getting to real-time
Ory reports real-time status data using [Upptime](https://github.com/upptime/upptime), a slick automation tool that uses Github Actions and other Github tooling to provide accurate uptime stats in real-time for our websites and APIs. 

> "Try not to let humans do what machines could do instead. As a rule of thumb, automating a common task is worth at least ten times the effort a developer would spend doing that task manually one time. For very frequent or very complex tasks, that ratio could easily go up to twenty or even higher."

-[Vincent Kraus](https://github.com/vinckr), Community Manager @ Ory

Lastly a word of wisdom from one of our ushers through the universe of software, art, work, life and creating almost anything 

##### Hofstadter's Law: 
> "It always takes longer than you expect, even when you take into account Hofstadter's Law." [Gödel, Escher, Bach: An Eternal Golden Braid](https://en.wikipedia.org/wiki/G%C3%B6del,_Escher,_Bach)

#### How do you use GitHub drive automation and create new efficiencies in your operations?  
[Ory](https://www.ory.sh) is an open source project aimed at advancing the state of cloud security by making it easier and safer for developers to implement a number of boilerplate services such as [credentials](https://www.github.com/ory/kratos), [service authorisation](https://www.github.com/ory/keto), [authentication](https://www.github.com/ory/hydra), [rule based reverse proxy and access control](https://www.github.com/ory/oathkeeper) as APIs. We appreciate your interest in Ory as we continue to help our audience understand Open Source Software and the New Identity Stack. And we continue to explain the dynamics of building a world class company based on the principles of transparency, diversity and good old hard work.


## 4. Automation

## 5. Deployment

## 6. Statistics and Metrics

## 7. API

## 8. Publication GitHub.io

## 9. Personalisation

## 10. License Management and Legal Conventions
