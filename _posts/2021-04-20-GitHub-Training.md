---
layout: post
title: Training Data Scientists to Use GitHub
category: training
excerpt: Convincing your Data Scientists to use code management
usemathjax: true
---
## Introduction

Storing source code on GitHub is a modern practice in Software Development. I’ve worked with teams in GitHub and have enjoyed the features and convenience it provides for code collaboration and management.

However, my current team does not use GitHub for code collaboration and I wanted to adapt GitHub as the team grows. Managing individual files on a shared drive may be sufficient for a team of three people, but once we expand the team to more than three, it becomes hard to avoid duplicate work and enforce best practices.

Furthermore, as my team starts to create more sophisticated Machine Learning models with required auto deployments, I wanted to set up the team for future success in how a version control management system can be used to help automate tasks and create production ready code.

## Git and GitHub Training

However my current team members have never worked with git or GitHub, let alone any version control management system. In order to help move the team forward, I needed to train my team in version control management as well as online code collaboration. Here is how I did it.

### Introduce the general concepts of code management. Highlight the benefits:

Here are the benefits that resonated with them:

- Auto-deployment can be set up using a code management system.
- Coding standards can be reinforced if people are forced to check in their code now.
- Avoid copying and pasting code snippets on team chat.
- Future team members will ramp up faster and reduce training time from current team members; this benefit really helped my team see the need for an organized code management system.
- Resume builder. I believe a data scientist who is familiar with software development best practices can become a more effective professional because data science is a team sport and managing better code drives more effective communication within the team and with other technical teams such as Business Intelligence, Engineering, IT, etc.

## Provide the Team Basic git Training

Fortunately my organization had a subscription for online technical classes and I assigned my team to take a basic git course. Make sure to keep everyone accountable and get them to finish their course work. I scheduled monthly check-ins with people to review with them what they learned and reinforce any learning concepts they might have trouble digesting. 

If you do not have access to online courses, I suggest you create a small course yourself and take everyone through the training. It is a high effort, but it shows your team how dedicated you are to the team’s success. Lead your team through your actions, not through your words.

## Run Through a GitHub Project with the Team

I could not find a satisfactory course or project involving real-world examples with git and GitHub, so I created my own project that resonated with them and worked through the project with them. I wanted to simulate as much of the flow of communication and work they would typically experience in a an actual project.

My team followed the steps through a workbook and I acted as the project lead. They committed code to the GitHub repo and created pull requests.

I ran code reviews, left comments, and asked them to make further commits before I merged the PR request into the main branch. 

The specific project I created involved creating a machine learning endpoint that can be automatically tested and deployed on Google Cloud Run via a Docker image using Python Flask as the web application framework. The Data Scientists on my team have not had experience seeing how a Continuous Integration/Continuous Development (CI/CD) pipeline works with a Machine Learning model deployment. 

They wanted to learn how the magic happens involving auto deployments. Make sure you create a project that resonates with your team members; it makes the whole process more fun and engaging for them.

## Summary

Overall, if you want to take your team to the next growth stage, take action and commit to your team’s learning. Make sure to highlight the benefits for your current team and future team; always think about how the new process and system saves them time in the future.

I’ve released my [GitHub workbook](/files/Github-Training/github_training_workbook.pdf) under the Creative Commons license. Feel free to use it and modify the workbook how you see fit.

Here is the link to the GitHub repo the workbook uses: [https://github.com/Mrk-Nguyen/boston-predict-model](https://github.com/Mrk-Nguyen/boston-predict-model).
