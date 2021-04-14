# README

Hi! Welcome to my team's MSCI 342 repo!



"A healthier team starts here".

For centuries, the health of teams has suffered due to rise of undetected conflict, discomfort and other negative experiences and emotions. PAEN is a team health monitoring web application developed a goal to provide users with a resource to communicate all team health related issues and provide team managers with a tool to quantify the emotions and feelings of their team members for a better understanding of their teams’ health. 

PAEN comprises of two separate user experiences: a unique PAEN page for team managers and separate, unique PAEN page for team members.

For managers, PAEN has designed the site such that team managers are able to view and keep track of all the teams they manage. As a manager, you are given an overview of your team member’s activity on the site. You will be able to view all the Tickets (refer to section Tickets) and Surveys (refer to section Surveys) submitted by your team members and even see some handy team health indicators to help you visualize the health situation for each team each week.

For team members, PAEN is primarily a communication tool to help members convey any conflict or reasons for negative emotions to their team members and to the team manager. As a team member you will have the ability to submit Tickets (refer to section Tickets) and Surveys (refer to section Surveys) each week to communicate how you feel about your manager, you team members, and the overall health of the current week. You will also be able to see team health indicators which give you a general understanding of the health of your team for the current week.



To use this repo please:
1. open your terminal and run: 'git clone https://github.com/Ashwuni/TeamHealthApp.git <directory_name>'
2. next navigate into the directory with: 'cd <directory_name>'
3. run "bundle install"
4. run "rails db:create"
5. run "rails db:migrate"
6. run "rails db:seed"
7. login to heroku from the terminal using "heroku login -i"
8. run `heroku create <application_name>`
9. run `git push heroku main`
10. run `heroku run rails db:migrate`
11. Access the website at `https://<app_name>.herokuapp.com/`

To access our web app, please go to this link:
https://msci342-w21-team-2.herokuapp.com/login

Feel free to create an account as a user or a manager, or use our pre-made logins:
As a user:
Watiam - "student4"
Password - "password"

As a manager:
Watiam - "manager1"
Password - "password"


