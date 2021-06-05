---
layout: post
title:  "Software Engineering projects"
date:   2021-01-20 14:05:36 +0800
categories: course projects
---

Last semester (Fall 2020), I took a Software Engineering course which revolves around a group software project. The software that we have to build is based on a Amercian name database, where we have to complete several name-related tasks. We were randomly allocated in groups of 3, so I worked with two complete strangers here. One of them worked as a project manager that contacts the "clients" (our teaching assistants) and obtains the project details from them, while I worked as a Scrum master that helped allocating the work, calling Scrum mettings, and managing GitHub branching issues. The project mainly consists of 6 tasks, so I simply allocated 2 tasks to each member.

During the project process, which lasted three months throughout the semester, we held short Scrum meetings periodically to report our progress on our allocated tasks, and estimate the progress we can make before the next meeting. The group wasn't big, so the meetings and the minutes recorded are very simple, but it's a new experience of formal software engineering process to me.

If you are interested, you can find our GitHub project repository <a href="https://github.com/JustinYFLau/20202021F-COMP3111-T-53" target="_blank">here</a>. The project is kind of huge, but the main codes are in <a href="https://github.com/JustinYFLau/20202021F-COMP3111-T-53/tree/master/src/main/java/comp3111/popnames" target="_blank">this folder</a>. Other folders are just data or GUI components. 

The most tedious part of this project is the fact that I didn't have any Java experience beforehand. We were provided with little support on Java and GUI tutorial (basically step-by-step tutorials on how to start a new GUI project with Scene Builder), and I have to learn to understand the codes myself. Turns out the tasks that I was working on requires scanning the whole name database multiple times, and my code takes around 2-3 minutes to finish a single execution, which made the TA initially think that my code crashed, and gave my task a 0 mark. A friend recently suggested that I should have looked up multi-threading techniques for Java, but oh well, I demenstrated my code in front of the TA and she gave me some marks at the end.