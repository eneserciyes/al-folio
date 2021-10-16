---
layout: page
title: Scrumier
description: A tool for easier worklog entry and sprint data visualization
img: /assets/img/scrumier_welcome.png
importance: 4
category: professional
---

In Summer 2020, I did an internship at Amadeus IT Services and completed an open source web-development project from the ground up. The project I worked on is called Scrumier – A Standalone Time Tracking Tool for JIRA. It is an open source web application that is based on a microservices architecture and containerized for easier deployment and running on cloud. The problem faced was essentially
threefold:

* Lack of a feature in vanilla JIRA Software to view, modify and insert worklogs easily.
* Inability to generate detailed reports of past sprints to better plan the next ones.
* People neglecting or forgetting to log their works.

<div class="img_row">
    <img class="col half left" src="{{ site.baseurl }}/assets/img/scrumier_calendar.png" alt="" title="scrumier base calendar view"/>
    <img class="col half left" src="{{ site.baseurl }}/assets/img/scrumier_teamreport.png" alt="" title="team report view for sprint data visualization"/>
</div>

The project we built provides three solutions for these three problems. Firstly, the Calendar Dashboard, which is the home screen for our application, allows viewing all worklogs in a calendar format for easier editing and reporting. Secondly, our Individual Reports and Notifications screen empowers especially scrum masters in agile teams to keep track of their team’s worklogs and set email notifications for reminding them to enter their worklogs. Last but not the least is our Team and Sprint Reports view. It enables especially team directors to analyze the cost of items and better size issues in sprint planning.

For the backend of the project, I used Java and Spring Boot framework. For the frontend, I used Vue.js. I developed the application with the microservices approach and then, containerized every service and deployed it to the Google Cloud. You can see the screenshots from my application in Figure 1 and 2.