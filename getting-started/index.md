---
layout: archive
title: "Getting Started with Chichinabo.org"
date: 2016-10-04T00:00:00-00:00
excerpt:
tags: []
image:
  feature: road-1600x800.gif
  teaser: road-400x250.gif
  thumb: road-120x120.gif
---

The basics for understanding what Chichinabo.org is (and what it isn't).

{% include toc.html %}

## Purpose

It is said that about the 80% of data analysis is spent in data preparation tasks. Cleaning, organizing, collecting new data sets, creating charts or mining for paterns are some of the tasks required before you can get some insight from data. Chichinabo.org looks for datasets where these tasks could be done only one more time.

We want to create simple, cheap and rehusable code projects for improving accesibility of certain public datasets.


## Conditions for creating a project

Chichinabo.org is organized into simple and useful data projects. 

Internet and database technologies may change, but a Chichinabo project will remain:

1. Atomic
  * Very simple data tasks
  * Easy to model as objects
2. Inmutable
  * The database structure won't ever change.
  * Source data won't change in the future.
3. Universal
  * Source datasets should be publicly available arround the world.
  * Include data at different spatial and temporal scales.
  * Expected outputs should be easy to analyze by anybody.
4. Colaborative
  * Users
  * Infomediaries
  * Scientists
  * Developers

It is not a condition but, originally, Chichinabo.org was intended to work with spatial datasets. You may find many features for working with maps.



## Architecture and technologies

### Datawarehouse

- PostgreSQL/PostGIS
- Redis
- ES
- Mongo DB

### Services

- RESTful API

### Web Apps

- R Shiny

### Software orchestration

- Dockers


## Currently working projects

- Popyramids. It is a geospatial database which stores population data by sex and age groups, associated to a geographical area. Take a look at the different apps developed on the top of this database.


## Contributing


### Users

You don't need to be a developer for joining this team. These are some ways we can collaborate:

- Keep us informed of new datasets we should include in a Chichinabo database.
- Prepare new datasets following our specifications.
- Design teaching experiments.
- ...


### Developers

Found a bug or aren't quite sure how something works? By all means submit an issue to the corresponding code project on GitHub. For straight forward bug fixes feel free to submit pull requests in the apropiate GitHub project. 


**Chichinabo.org** was built predominately as a platform for working with geospatial datasets. However, feel free to propose other projects that could fit the above mentioned conditions for a Chichinabo project.




## License

The different code projects generated here are always free and open source software, distributed under the GPL3 License.
