<div align="center">

<img src="banner.svg" alt="Hussein Oloyede, Product Engineer. Design and build, end to end." width="100%"/>

### I design the screen, then build everything behind it.

<p>
Product Engineer working across Figma, C#/.NET, Angular and Azure.<br>
Currently looking for a software engineering internship.
</p>

<a href="https://github.com/hussenoloyede">
<img src="https://img.shields.io/badge/GitHub-hussenoloyede-0a0f1a?style=for-the-badge&logo=github&logoColor=22d3ee"/>
</a>

<a href="https://www.linkedin.com/in/hussein-oloyede-281b74388/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0a0f1a?style=for-the-badge&logo=linkedin&logoColor=22d3ee"/>
</a>

<a href="https://toolfleet-hussein-euf6h0g7bxbrhabk.eastasia-01.azurewebsites.net">
<img src="https://img.shields.io/badge/Live_demo-ToolFleet-0a0f1a?style=for-the-badge&logo=microsoftazure&logoColor=22d3ee"/>
</a>

</div>

---

# About me

I'm Hussein, and I work as a product engineer: I design the interface in Figma, then write the API, the database layer, the tests and the pipeline that ships it. Most of my time goes into one question. Does every part of the screen do what it says?

That question became a rule on my main project. Nothing on screen may be fake. If a button does nothing, or a number has no code behind it, it doesn't go in, even when the design shows it. My Figma file had search, a notification bell and a batch-update button. The shipped app has none of them, because none of them worked yet.

I explain my code in plain English and keep the business rules in classes with no framework code, so they can be tested without a database. If I can't explain a piece at a whiteboard, I don't commit it.

- Designs in Figma, then turns the design into a working Angular app
- Writes backend services in C# with ASP.NET Core and EF Core
- Deploys to Azure with no passwords or keys in code, pipeline or settings
- Tests the business rules first, then the HTTP layer, then the screens

---

# Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=cs,dotnet,ts,angular,sass,nodejs,sqlite,azure,figma,git,github,vscode&perline=12" />

</div>

<br>

<div align="center">

![SQL Server](https://img.shields.io/badge/Azure_SQL-0a0f1a?style=for-the-badge&logo=microsoftsqlserver&logoColor=22d3ee)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0a0f1a?style=for-the-badge&logo=azuredevops&logoColor=22d3ee)
![Blob Storage](https://img.shields.io/badge/Azure_Blob_Storage-0a0f1a?style=for-the-badge&logo=microsoftazure&logoColor=22d3ee)
![xUnit](https://img.shields.io/badge/xUnit-0a0f1a?style=for-the-badge&logoColor=22d3ee)
![Vitest](https://img.shields.io/badge/Vitest-0a0f1a?style=for-the-badge&logo=vitest&logoColor=22d3ee)

</div>

<br>

I've shipped all of the above in ToolFleet. Everything else I'm learning stays off this list until it's in a repo.

---

# Featured projects

<table>
<tr>

<td width="50%" valign="top">

## ToolFleet

A web app for tracking downhole drilling tools across field bases and rolling out firmware in stages, so a bad build is caught on a few tools before it reaches the whole fleet.

- Canary rollout with an automatic halt when failures pass a threshold
- Manual approval before the build goes to the rest of the fleet
- Firmware files held in private Azure Blob Storage, with a SHA-256 fingerprint and download links that expire after 15 minutes
- Audit log written in the same transaction as every change
- 76 tests (35 domain, 20 API, 21 web), about 92% line coverage
- Deployed on Azure through a pipeline that runs on every push to main

`C#` `ASP.NET Core` `EF Core` `Angular` `TypeScript` `Azure SQL` `Azure Blob Storage` `Azure DevOps`

<br>

<a href="https://github.com/hussenoloyede/tool-fleet">
<img src="https://img.shields.io/badge/View_code-0a0f1a?style=for-the-badge&logo=github&logoColor=22d3ee"/>
</a>
<a href="https://toolfleet-hussein-euf6h0g7bxbrhabk.eastasia-01.azurewebsites.net">
<img src="https://img.shields.io/badge/Live_demo-22d3ee?style=for-the-badge&logoColor=0a0f1a&labelColor=0a0f1a"/>
</a>

The demo runs on a free tier, so the first load after a quiet spell takes 20 to 30 seconds.

</td>

<td width="50%" valign="top">

## Drilling telemetry monitor

Status: next up.

Replays real drilling data from Equinor's public Volve dataset as a live stream, stores it as time series and shows it on a dashboard that flags problems as they happen. The screen is designed for someone glancing at it on a rig floor: high contrast, large numbers, alerts that can't be missed.

Planned stack: `Go` `NATS` `TimescaleDB` `Angular` `Kubernetes`

Repo link goes here once the first commit lands.

</td>

</tr>

<tr>

<td width="50%" valign="top">

## Well report assistant

Status: planned.

Upload well reports, ask questions in plain English and get answers that cite the source page. It will say "I don't know" when the reports don't cover a question, and the README will carry an accuracy score measured on 30 test questions with known answers.

Planned stack: `Python` `FastAPI` `pgvector` `Azure OpenAI`

Repo link goes here once the first commit lands.

</td>

<td width="50%" valign="top">

## Insurance claims portal

Status: planned.

Customers submit a claim with documents, an agent reviews it and both sides see the status. This one doubles as my design case study: Figma flows, a small component library, a usability test with five people and a write-up of what changed afterwards.

Planned stack: `Java` `Spring Boot` `RabbitMQ` `PostgreSQL` `React`

Repo link goes here once the first commit lands.

</td>

</tr>
</table>

---

# What I'd build next on ToolFleet

- A field agent on each base's workshop PC that claims jobs, checks the SHA-256 and reports back
- Sign-in with Microsoft Entra ID, with separate engineer and approver roles
- Optimistic concurrency, so two approvers can't promote a rollout at the same moment
- Automatic rollback to the previous firmware when a rollout halts

---

# Connect

<div align="center">

I'm open to internship conversations and to feedback on ToolFleet. If you find something in the demo that doesn't work, tell me.

<br><br>

<a href="https://www.linkedin.com/in/REPLACE-WITH-YOUR-LINKEDIN-HANDLE/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0a0f1a?style=for-the-badge&logo=linkedin&logoColor=22d3ee"/>
</a>

<a href="https://github.com/hussenoloyede?tab=repositories">
<img src="https://img.shields.io/badge/All_repositories-0a0f1a?style=for-the-badge&logo=github&logoColor=22d3ee"/>
</a>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0a0f1a,100:22d3ee" width="100%"/>

</div>
