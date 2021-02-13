## Automating the software release

Ory uses numerous automation approaches to eliminate manual, repetitive tasks and integrate web applications to improve productivity including:
- Software testing and release management such as Coveralls (https://coveralls.io)  and CircleCI (https://circleci.com)
- End to End Tests for web browsers such as Cypress (https://www.cypress.io)
- GitHub Actions or scripts that automate workflows in GitHub (https://github.com/features/actions)
- Third party automation tools such as Zapier (https://zapier.com) or n8n (https://n8n.io) that add new workflow processing outside GitHub
- Real-time metrics and notifications that use GitHub repositories such as Upptime (https://github.com/upptime/upptime)

Software Quality Assurance: Open Source Software undergoes scrutiny from many different constituants for example contributors, users, security specialists so having automated processes that provide data about the heath of a software build is an essential form of communication. Automation tools such as Coveralls informs about code coverage tests while CircleCI  provides a fully automated release pipeline.

Interchange: @OryCorp uses this @GH Action to publish tweets from a GitHub repository, rather than sharing log-in credentials across the team. Instead of tweeting directly, our team can submit a pull request for review, thereby encouraging more data interchange and enabling everyone to create a @Twitter post.

Delegation: Ory uses @Zapier to integrate Google Gmail and GitHub. Inbound emails to our general office@ory.sh  mail address are labeled according to their content, which automatically triggers a New Issue in GH in a corresponding repository matching the label, eg. Human Resources, including adding the content of the email  for instance subject/body, and assigning the issue to the responsible team member. 

Administration: Ory uses @Zapier and basic scripts to rename and store inbound invoices. Inbound invoices are received, reviewed and  forwarded electronically to our web based accounting software @Datev for automatic posting. Using @Zapier, we have set this forwarding action as a trigger to download and save the invoice to our @GoogleDrive ‘Inbound Invoices’ folder and rename it with a simple script (by date, vendor, amount etc.) in accordance with our internal file naming convention.

Engagement: @Slack release automation gives transparency over our release process. Notifications give our community realtime oversight over every release. Ory also uses GreetBot to greet new members in our Slack channel and give them a warm welcome, point them to all relevant documentation and other places that might be interesting to them.

Getting to real-time: Ory reports real-time status data using @Upptime , a slick automation tool that uses Github Actions and other Github tooling to provide accurate uptime stats in real-time for our websites and APIs. 

Lastly a word of wisdom from one of our ushers through the universe of software, art, work, life and creating almost anything, Hofstadter's Law: 
"It always takes longer than you expect, even when you take into account Hofstadter's Law." (Gödel, Escher, Bach: An Eternal Golden Braid, Basic Books; Anniversary edition 1999-02-05) (https://www.amazon.de/gp/product/0465026567/ref=dbs_a_def_rwt_bibl_vppi_i2)
