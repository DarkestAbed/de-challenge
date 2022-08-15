# Data Engineer - Challenge
This is the first Data Engineer Challenge. The goal of these Challenges is to assess the candidate's ability to code and provide answers to business scenarios and questions.

## Business Scenario

A retail store wants to create a new section for videogames. To bring custom videogame information to the clients, the Analytics team requests a new report each day with several videogames information. This information will be used to create several ML models and Data Science and Analytics work, as well as BI and Data Viz workloads. This aims to provide the end user with the best customer experience and enhance the purchase decision.

## Business Requirement

For this Challenge, you should develop an ETL job (or jobs) that provide the Data team the required data, with some considerations:
- The job should be developed in Python, Scala or Javascript/Typescript
- The data model for the proposed solution must be delivered in PNG or SVG format
- The code should have a deployment method

## ETL Job

The job must receive the datasets & brings a few things:
- The top 10 best games for each console/company.
- The worst 10 games for each console/company.
- The top 10 best games for all consoles.
- The worst 10 games for all consoles.
The data is in the folder data/ in the root. The report can be exposed in any way you want, but remember this is an ETL Job.

## Data Model

The Data Model must be in 3NF. 
Save the model in the DataModel folder in both formats (data model format & JPG/PNG).
```
Use any tool, but please tell us the tool you choose & why.
```

## Deployment

We want you to give us the way to deploy your job and run it in any environment, So please put the way to deploy very clearly.

## Concerns

- You can create a new README for anything you want to tell us. Please don't name README.md
- We want to see if you know how to code in a professional way, so use the best practices of Software Engineering!.
- This is an ETL Job, so show us all you know about good practices to do ETL's.
- Save all the changes in your personal GitHub account using a Fork from this repository and send us the link to clone and see the repository.


### Disclaimer Note

> This challenge is your cover letter, the elections you choose to do & not to do matters, and will be asked in the next interview


## Datasets

We use the data from TopGames provided by Metascore.

* [Kaggle: Metacritic reviewed games since 2000](https://www.kaggle.com/destring/metacritic-reviewed-games-since-2000)
