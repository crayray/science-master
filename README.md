ScienceMaster
====================================

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Requirements](#requirements)
* [Installation](#installation)
* [Credits](#credits)

---

## General info
Do you know as much as a 5th grade science student? Find out by taking this science quiz. This web app has the following interactive functionalities: 
- Select from three different science categories
- Enter a name and trigger the timer to start playing
- You'll be shown ten multiple choice questions:
- - If you select the incorrect answer, the correct anwswer will be highlighted 
- As you get answers correct, watch the beaker fill up with green ooze!
- At the end you'll see your time, score and the top 5 fastest players


---

## Technologies
This is a single page app that loads all data via Javascript on the front end. It retrieves data from our Ruby on Rails API. The data is stored in a PostgreSQL database. 


## Requirements
This app will require the following:
- Ruby
- Ruby on Rails
- PostgreSQL

## Installation
Run bundle install:
```
// ♥ bundle install
```
Migrate the database to create the schema:
```
// ♥ rails db:migrate
```
Seed the database to get the questions and answers:
```
// ♥ rails db:seed
```
Start the server and load the site on localhost:3000:
```
// ♥ rails s
```

## Credits


The humble developers in training that built this are:


**Rachel Fuerst** [LinkedIn](https://www.linkedin.com/in/rachfuerst) // [Github](https://github.com/crayray)

&

**Mei Wong** [LinkedIn](https://www.linkedin.com/in/fong-mei-wong-594a2451/) // [Github](https://github.com/fmwong77)

