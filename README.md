<h5 align="center"> Team - Tech Vision | 6° BD </h5>

<br>

<p align="center">
<img src ="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/simbolo%20(sem%20fundo).png" width="250" height="250"/>
 </h3>
<p align="center">

<p align="center">
      <h3 align="center"> Tech Vision </h3>
<p align="center">

<hr>

<p align="center"> 
   <a href="#pencil2-challenge">Challenge</a> •
   <a href ="#dart-project-requirements"> Requirements </a> •
   <a href ="#hourglass_flowing_sand-delivery-planning"> Planning </a> •
   <a href="#date-sprints">Sprints</a> •
   <a href ="#joystick-technologies-used"> Technologies </a> •
   <a href ="#bulb-methodology-used"> Methodology </a> •
   <a href="#crystal_ball-backlogs">Backlogs</a> •
   <a href="#mortar_board-team">Team</a>
</p>

<h4 align="center"> 
 <a href="https://www.python.org/"><img src = "https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/></a>
 <a href="https://react.dev/"><img src = "https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/></a>
 <a href="https://azure.microsoft.com/pt-br"><img src = "https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white"/></a>
 <a href="https://flask.palletsprojects.com/en/2.2.x/"><img src = "https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"/></a>
</h4>

<br>

<details open><summary>:computer: Project configuration</summary>

**Requirements:**

Tech parent project including tech-backend and tech-frontend as submodules

```
git clone --recurse-submodules https://github.com/TechVisionn/tech-parent.git
```

- To update submodules projects in tech-parent after having cloned the project ( Replace "branch_name" with branch name)

```
git pull --recurse-submodules origin <branch_name>
```

- First of all, open ".env" file and configure the path of projects paste, as in the example below:

[Git Submodules Documentation](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

</details>

<br>

## :pencil2: Challenge

Organization of a public Proagro database for quick queries and analysis in the Geographic Information System.

<br>

## :dart: Project Requirements

<img align="right" width="200" height="180" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/edicao.png">

**Functional Requirements**
  - [x] Model a relational spatial database from the Proagro tables;
  - [x] Cleaning sensitive data (LGPD);
  - [x] Organize the data provided by the client;
  - [x] Plotting the perimeter of the plots provided in the Proagro tables in a geographic information system;
  - [x] Attribute relevant agricultural information to the plots in the geographic information system;
  - [x] Cross-reference the land parcel's spatial information with its location (municipality and state);
  - [x] Develop a button to select the gleba and return an information table (pop up) relating to the selected gleba;
  - [x] Develop a button to select the area and return the vegetation index time series in graphical form;
  - [x] Connect to and consume Visiona's Vegetation Index Time Series API;
  - [x] The query to Visiona's API should return a time series for each glebe consulted;
  - [x] Save the consumed/consulted time series in a database;
  - [x] Develop a simple front end that shows the glebes spatially distributed, a glebe selection button and the vegetation index graph;
  - [x] The time series of the vegetation index should be presented by the dates defined between 30 days before the planting date and 30 days after the harvest date informed in the Proagro tables and organized in the database.<br><br>

**Non-Functional Requirements**
  - [x] The site's response time must be below 1.5 minutes in 99.99% of requests;
  - [x] The application's query engine must generate trails in JSON format (optional);
  - [x] The system must contain metrics to help observe its behavior: Qty of requests, response time, qty and % of failures when obtaining data from Golden Sources.<br><br>

<br>

**:link: Click the link below to view the *Kanban* of team activities:**
> [Kanban Projects GitHub](https://github.com/orgs/TechVisionn/projects/1)

<br>

## :hourglass_flowing_sand: Delivery Planning

<img align="right" width="230" height="200" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/calendario.png">

- [x] [Kickoff](https://github.com/TechVisionn/tech-parent/blob/main/docs/KickOff%20-%20Visiona.pdf) - 21/08/2023 to 28/08/2023

- [x] [SPRINT 1](https://github.com/TechVisionn/tech-parent/blob/main/sprints/sprint-1.md) - 04/09/2023 to 24/09/2023

- [x] [SPRINT 2]() - 25/09/2023 to 15/10/2023

- [x] [SPRINT 3]() - 16/10/2023 to 05/11/2023

- [x] [SPRINT 4]() - 06/11/2023 to 26/11/2023

- [x] Solutions Fair - 12/12/2023 at 7 pm

<br>

## :date: Sprints

<img align="right" width="200" height="196" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/app-de-apresentacao-de-slides.png">

🔖 SPRINT 1 ([Folder Link](https://github.com/TechVisionn/tech-parent/blob/main/sprints/sprint-1.md)): In Progress 🕗

🔖 SPRINT 2: Waiting 🏗️

🔖 SPRINT 3: Waiting 🏗️

🔖 SPRINT 4: Waiting 🏗️

<br>

## :joystick: Technologies Used

<img align="right" width="218" height="190" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/contracao-muscular.png">

* **Database:** Microsoft Azure and MongoDB
* **Backend:** Python
* **Front-end:** React
* **Tools:** Visual Studio Code, GitHub.

<br>

## :bulb: Methodology Used

* **Agile Methodology:** Framework [Scrum](https://www.scrum.org/)

<br>

<span id="backlogs">

## :crystal_ball: Backlogs

<h1 align="center"> <img src = "https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/backlogs.png" /></h1>

## :magic_wand: Epics and User Stories

<h1 align="center"> <img src = "https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/%C3%89picos%20e%20Hist%C3%B3rias.png" /></h1>

<br>

## :mortar_board: Team 

|Avatar|Name|Role|LinkedIn|GitHub|
| -------- |-------- |-------- |-------- |-------- |
<img src = "https://avatars.githubusercontent.com/u/70216549?v=4" height="50"/> |**Bryan Ribeiro**|Product Owner|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/bryanrribeiro/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/BryanRibeiro)
<img src = "https://avatars.githubusercontent.com/u/74521818?v=4" height="50"/> |**Carlos Souza**|Scrum Master|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/carlos-fernando-souza-94aa074b/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/CarlosSouza87)
<img src = "https://avatars.githubusercontent.com/u/64873345?v=4" height="50"/> |**Camila Pacheco**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/camilaffpacheco/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/camilaffpacheco)
<img src = "https://avatars.githubusercontent.com/u/81338441?v=4" height="50"/> |**Andrew Augusto**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/andrew-augusto-778585127/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/AndrewAugusto)
<img src = "https://avatars.githubusercontent.com/u/81268185?v=4" height="50"/> |**Zaion Felippe**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/zaion-gomes-b17657214/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/ZaionKun)
<img src = "https://avatars.githubusercontent.com/u/80988756?v=4" height="50"/> |**José Santos**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/jos%C3%A9-maria-reis-dos-santos/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/Jose-dos-santos)
<img src = "https://avatars.githubusercontent.com/u/48994698?v=4" height="50"/> |**Gabriel Santos**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/gabriel-santos-87922b170/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/gabrieljssantos)
<img src = "https://avatars.githubusercontent.com/u/71853528?v=4" height="50"/> |**Orlando Pereira**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/orlando-pereira-a09ba9214/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/Orlandi-a11)
<img src = "https://avatars.githubusercontent.com/u/79945984?v=4" height="50"/> |**Kauã Borgarelli**|Dev Team|[<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/kau%C3%A3-borgarelli-5bb67220a/)|[<img src="https://camo.githubusercontent.com/fbc3df79ffe1a99e482b154b29262ecbb10d6ee4ed22faa82683aa653d72c4e1/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4769744875622d3130303030303f7374796c653d666f722d7468652d6261646765266c6f676f3d676974687562266c6f676f436f6c6f723d7768697465" />](https://github.com/Borgarelli)

<br>


