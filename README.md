# Data Engineer - Challenge
This is the first Data Engineer Challenge. The goal of these Challenges is to assess the candidate's ability to code and provide answers to business scenarios and questions.

## Business Scenario

A retail store wants to create a new section for videogames. To bring custom videogame information to the clients, the Analytics team requests a new report each day with several videogames information. This information will be used to create several ML models and Data Science and Analytics work, as well as BI and Data Viz workloads. This aims to provide the end user with the best customer experience and enhance the purchase decision.

## Business Requirement

For this Challenge, you should develop an ETL job (or jobs) that provide the Data team the required data, with some considerations:
- The job should be developed in Python, Scala or Javascript/Typescript. The choice must be documented and justified
- The data model for the proposed solution must be delivered in PNG or SVG format
- The code should have a deployment method available

## ETL Job

The job must receive the datasets and provide the following answers daily:

- The top 10 best games for each console/company
- The worst 10 games for each console/company
- The top 10 best games for all consoles
- The worst 10 games for all consoles

The data is in the `data/` folder. The reports can be exposed in any way you want, but keep in mind this is an ETL job.

## Data Model

The Data Model must be in 3NF.<br>
Save the model in the `DataModel/` folder in PNG or SVG format. If you want, you can provide an extensible and versionable format as well (e.g. `drawio.xml`).<br>
Use any tool, but please tell us the tool you choose and why you're choosing it.

## Deployment

We want you to provide a way to deploy your job and run it in any environment, so please provide a deploying mechanism and describe it on its own `README.md` on the `Deployment/` folder.

## Concerns

- We want to see how you code in a professional way, so use the best practices of Software Engineering you know about!
- This is an ETL job, so show us all you know about best practices to do ETLs
- Save all the changes in your personal GitHub account using a fork from this repository and send us the link to clone and see the final repo
- You can use any and all modules, code pieces and tools you want to build this job and complete this challenge, but you must document them and justify them


### Disclaimer Note

> This challenge is your cover letter, the elections you choose to do & not to do matters, and will be asked in the next interview


## Datasets

We use the data from TopGames provided by Metascore.

* [Kaggle: Metacritic reviewed games since 2000](https://www.kaggle.com/destring/metacritic-reviewed-games-since-2000)
