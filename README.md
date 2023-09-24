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
   <a href="#milky_way-challenge">Challenge</a> •
   <a href ="#dart-project-requirements"> Requirements </a> •
   <a href ="#hourglass_flowing_sand-delivery-planning"> Planning </a> •
   <a href="#date-sprints">Sprints</a> •
   <a href ="#joystick-technologies-used"> Technologies </a> •
   <a href ="#bulb-methodology-used"> Methodology </a> •
   <a href="#crystal_ball-product-and-sprint-backlog">Backlogs</a> •
   <a href="#mortar_board-team">Team</a>
</p>

<h4 align="center"> 
 <a href="https://www.python.org/"><img src = "https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/></a>
 <a href="https://react.dev/"><img src = "https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/></a>
 <a href="https://www.mysql.com/"><img src = "https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white"/></a>
 <a href="https://azure.microsoft.com/pt-br"><img src = "https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white"/></a>
 <a href="https://flask.palletsprojects.com/en/2.2.x/"><img src = "https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white"/></a>
</h4>

<br>

<details>
	
<summary>:computer: Project configuration</summary>


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

## :pencil2: Problem

The company requires the implementation of a Geographic Information System (GIS) to speed up analysis and improve internal processes. Although the data is available in the public sphere of ProAgro, we face challenges such as a lack of organization, the presence of sensitive information and an excess of data to be managed.

(ProAgro is a federal government program aimed at agricultural financing for small and medium-sized Brazilian producers).

<br>

## :rocket: Solution

We propose a comprehensive solution that involves the collection and refinement of public data from ProAgro, efficient restructuring of the database and the development of a personalized Geographic Information System (GIS), providing information in a simpler and more organized way for the user. This approach seeks to facilitate the understanding and analysis of data, contributing to improvements in the company's internal processes.

<br>

## :milky_way: Challenge

Organization of a public Proagro database for quick queries and analysis in the Geographic Information System.

<br>

## :dart: Project Requirements

<img align="right" width="200" height="180" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/edicao.png">

**📌 Functional Requirements**
- Model a spatial relational database from Proagro tables;
- Plot the perimeter of the plots reported in the Proagro tables in the geographic information system;
- Attribute relevant agricultural information to plots plotted in a geographic information system;
- Cross-reference the Gleba’s spatial information with its location (Municipality and State);
- Connect and consume the Visiona Vegetation Index Time Series API;
- The Visiona API query must return a time series for each plot consulted;
- Save consumed/queried time series in the database;
- Develop a simple front end that shows the spatially distributed plots, a plot selection button, and the vegetation index graph;
- The vegetation index time series must be presented by dates defined between 30 days before the planting date and 30 days after the harvest date informed in the Proagro tables and organized in the database.<br><br>

**📌 Non-Functional Requirements**
- The site's response time must be below 1.5 minutes in 99.99% of requests;
- The application's query engine must generate trails in JSON format (optional);
- Documentation (Fatec Requirement)
- The system must contain metrics to help observe its behavior: Qty of requests, response time, qty and % of failures when obtaining data from Golden Sources.<br><br>

<br>

## :hourglass_flowing_sand: Delivery Planning

<img align="right" width="230" height="200" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/calendario.png">

- [x] [Kickoff](https://github.com/TechVisionn/tech-parent/blob/main/docs/KickOff%20-%20Visiona.pdf) - 21/08/2023 to 28/08/2023

- [x] [SPRINT 1](https://github.com/TechVisionn/tech-parent/blob/main/sprints/sprint-1.md) - 04/09/2023 to 24/09/2023

- [x] SPRINT 2 - 25/09/2023 to 15/10/2023

- [x] SPRINT 3 - 16/10/2023 to 05/11/2023

- [x] SPRINT 4 - 06/11/2023 to 26/11/2023

- [x] Solutions Fair - 12/12/2023 at 7 pm

<br>

**:link: Click the link below to view the *Kanban* of team activities:**
> [Kanban Projects GitHub](https://github.com/orgs/TechVisionn/projects/1)

<br>

## :date: Sprints

<img align="right" width="200" height="196" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/app-de-apresentacao-de-slides.png">

🔖 SPRINT 1 ([Folder Link](https://github.com/TechVisionn/tech-parent/blob/main/sprints/sprint-1.md)): Done ☑️ 

🔖 SPRINT 2: In Progress 🕗

🔖 SPRINT 3: Waiting 🏗️

🔖 SPRINT 4: Waiting 🏗️

<br>

## :joystick: Technologies Used

<img align="right" width="218" height="190" src="https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/contracao-muscular.png">

* **Database:** MySQL and MongoDB
* **Backend:** Python
* **Front-end:** React
* **Tools:** Visual Studio Code, GitHub.

<br>

## :bulb: Methodology Used

* **Agile Methodology:** Framework [Scrum](https://www.scrum.org/)

<br>

<span id="backlogs">

## :crystal_ball: Product and Sprint Backlog

<h1 align="center"> <img src = "https://github.com/TechVisionn/tech-parent/blob/main/docs/Images/backlogs.png" /></h1>

## :flying_saucer: Epics and User Stories

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


