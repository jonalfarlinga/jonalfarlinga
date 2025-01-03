# 👋 Hi, I’m Denny

I'm a software developer who's excited by the prospect of building tools that others find useful. I'm very interested in testing and Agile methodologies. I've written and iterated on automated tests for my personal projects, making several improvements as I've learned more.

- [My Stack](#my-stack)
- [My Projects](#my-projects)
  - [Birddex](#birddex)
  - [Proficient](#proficient)
    - [Calends](#calends)
    - [PDiF](#pdif)
  - [Portfolio](#portfolio-project)
  - [Codename: true-quasar](#codename-true-quasar)
  - [Chat-12](#chat-12)
  - [Lawn Mower](#lawn-mower)
- [About Me](#about-me)
- [How to Reach Me](#how-to-reach-me)

### My Stack
> `Languages`<br>
> <img src="./docs/python_icon.png" width="40"></img>
> <img src="./docs/javascript_icon.png" width="40"></img>
> <img src="./docs/r_icon.png" width="40"></img>
> <img src="./docs/mongodb_icon.svg" width="40"></img>
> <img src="./docs/sql_icon.png" height="40"></img>
> <img src="https://github.com/user-attachments/assets/873d56c1-7e77-4798-bd9d-860023d7fb8e" height="40"></img>


> `Web Core`<br>
> <img src="./docs/html_icon.png" width="40"></img>
> <img src="./docs/css_icon.png" width="40"></img>
> <img src="./docs/htmx_icon.png" height="40"></img>

> `Frameworks`<br>
> <img src="./docs/fastapi_icon.svg" width="40"></img>
> <img src="./docs/white_flask_icon.png" height="40"></img>
> <img src="./docs/react_icon.png" width="40"></img>
> <img src="./docs/django_icon.png" width="40"></img>

> `Tools`<br>
> <img src="./docs/docker_icon.png" width="40"></img>
> <img src="./docs/azure_icon.svg" width="40"></img>
> <img src="./docs/Git_icon.png" width="40"></img>
> <img src="./docs/tableau_icon.svg" width="40"></img>
> <img src="./docs/vscode_icon.png" width="40"></img>

### My Projects

#### Birddex
> `A lifelist app for birders`<br>
> [Live Site](https://canarydevs.github.io/birddex)<br>
> [Gitlab Repo](https://gitlab.com/canarydevs/birddex)<br>
> We deliver a single-page application on the front end using React and a backend API using FastAPI. Data is managed by a PostgreSQL database. The Birddex repo contains several design diagrams and our project journals.
>
> I integrated Azure blob storage in order to allow users to upload their own images to the site.
>
> Topics: Dynamic Rendering Web Page, User Authentication, API, SQL Database, Automated Testing, Heroku

#### Proficient
> `A portal to your web-based teaching aid`<br>
> [Live Site](https://www.proficientdr.com)<br>
> [Gitlab Repo](https://github.com/jonalfarlinga/proficient)<br>
> Proficient is a portal to my available teaching aids. We have [Pdiff](#pdiff) and [Calends](#Calends) with more to come! Proficient manages your login details accross all the apps, and keep an eye out for more functionality on the portal as well!
>
> Topics: Authentication, React, FastAPI, Rest, Automated Testing, CI/CD, SQL Database, CDN, DNS, Heroku

#### Calends
>  `A syllabus-building utility for professors`<br>
> [Live Site](https://calends.proficientdr.com)<br>
> [Github Repo](https://www.github.com/jonalfarlinga/calends-lite)<br>
> This project uses a React front end hosted on Azure Storage and Azure Functions to serve the backend API. The business logic involves scraping html for data, then building a dictionary containing dates that can be rendered in HTML as a table-style calendar.
>
> This project was originally using Django backend. I rebuilt the backend in FastAPi, and at the same time switched from a `create-react-app` front end to `Vite`. I then rebult the backend for Azure Functions.
>
> Topics: Web-scraping, Dynamic Rendering Web Page, API

#### PDiF
> `A simple utility to calculate diff on PDFs`<br>
> [Live Site](https://pdiff.proficientdr.com)<br>
> [Github Repo](https://www.github.com/jonalfarlinga/pdiff)<br>
> Have you ever tried had to grade a second draft of a 15-page final? Only to find out the student only changed 3 words?! PDiF to the rescue! This app runs a Meyer's diffing algorithm on 2 pdfs and outputs the text of the pdf with removals highlighted in red, and additions highlighted in green.
>
> Topics: React, Azure Functions, API, Meyer's diff.

#### Portfolio Project
> `My cloud-hosted resume and portfolio page`<br>
> [Live Site](https://portfolio.denny-buklin.net)<br>
> [Github Repo](https://www.github.com/jonalfarlinga/portfolio)<br>
> Following the Cloud Resume Challenge, I created my portfolio as a full stack app using Azure Storage hosting and Azure Functions. I used HTMX to build the single-page application with page updates served as strings from the Azure functions API.
>
> Topics: HTMX, Dynamic Rendering Web Page, API, Azure Function App

#### Codename true-quasar
> `A sci-fi hero-drafting game using Go and Ebiten`<br>
> [Github Repo](https://github.com/jonalfarlinga/true-quasar)<br>
> A full-screen game app where players draft a team of characters to take on boss monsters.
>
> Topics: Go, Game Design

#### Chat-12
> `An instant messaging app for developers`<br>
> Work in progress<br>
> [Gitlab Repo](https://www.gitlab.com/base-12/chat-12)<br>
> We built an API using Flask with a persistant database using MongoDB. In the next phase we will build a front end using React and websockets.
>
> I created unit tests for the database interface. In the first iteration, the tests were tightly coupled by mocking to the tested code. To fix this, I created Pytest fixtures that start an in-memory Mongo database for proper interations during test.
>
> Topics: Flask, MongoDB, Data Design, Automated Testing

#### Lawn Mower
> `A system utility to keep the desktop clean`<br>
> [Github Repo](https://www.github.com/jonalfarlinga/lawn-mower)<br>
> I wrote this script to keep my computer desktop clean. I wrote an install batch file that sets the target directory and the desktop locations, and I created a run batch file that starts the script as a background process.
>
> The running script moves all files off the desktop every two minutes.
>
> Topics: File System Manipulation, Task Scheduling, Shell scripting

### About me
As a high school student, my fascination with software development sparked a lifelong passion for software development. Despite career detours, my affinity for problem solving has remained unwavering. I thrive on collaborative projects and effective project management, orchestrating cohesive workflows for optimal outcomes. Transitioning towards software development aligns with my pursuit of happiness and productivity, fueling my daily quest for discovery and problem-solving.

My approach to my work emphasizes practicality, prioritizing functionality while maintaining adherence to standards and best practices. Outside of software, my experiences as a sailor taught me valuable lessons in holistic thinking and adaptability, mirroring my approach to project management.

Looking ahead, I aspire to design impactful systems that aid people regardless of scale, aiming to be a reliable support figure and providing assistance when needed. In essence, I am driven by a relentless pursuit of knowledge, blending technical expertise with a collaborative spirit and a passion for crafting solutions that truly make a difference.

### How to Reach Me
- 📫 Connect on GitHub or [LinkedIn](https://www.linkedin.com/in/dennis-bucklin)
- ⛵ Check out my [portfolio](https://portfolio.denny-bucklin.net)
