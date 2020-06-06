# [ WIP ]

## Logistics

**Project Team:**
Sean Riley | William Wright | Sam Russell | Andrés Ortiz Montalvo

**Scrum Master:** 
Andrés Ortiz Montalvo

## Project Description

WIP is a portal for artists and designers to gain platforms and showcase their craft. The application allows for connection between exploorers/buyers to connect with local talent selling their work.

## Wireframes

**Home Page**  
![Home Page](https://github.com/4thquarter/p4front/blob/master/Proposal/Images/Project%204.jpg)  

## MVP User Stories

_**MVP User Stories**_

- _As an artist, I would like to have a platform that allows me to make virtual expositions of my pieces and collections._
- _As a collector, I would like to access information on talent and purchase their works._
- _As a fashion enthusiast, I would like to search for upcoming designers in the market._

_**Post MVP Stretch Goals**_

- _Creating geographic functionality to search for relevant local content._
- _In-app messaging functionality._
- _Visual scanning automation for color filtering of pieces._
- _Create "Collections" layer between profiles and pieces in order to create formal expositions of curated works._

#### Database Sample Object

```json
{
	"id": 1,
	"title": "Under the Sea",
	"artist": "Ariel",
  	"medium": "Mixed",
	"dominant_color": "Blue",
	"main_image_url": "imgurl1.com",
	"optional_additional_images_urls":  [
      		"imgurl2.com",
      		"imgurl3.com",
      		"imgurl4.com"
  	],
	"collection": "Disney Classics",
  	"info": "Informational Paragraph"
}
```

#### Component Details

| Component                    		| State/Props |
| :-----------------------------------: | :---------: |
| Helper 				|    State    |
| App 					|    State    |
| Nav Bar  				|    Props    |
| Profile Page  			|    Props    |
| Item detail page  			|    Props    |
| About 				|    Props    |
| Footer 				|     N/A     |


#### Back-End Objectives and Technologies Used
- Develop a backend powered by Django and MongoDB with the use of AWS for file uploading and storage to feed the frontend ReactJS application.
- Implement (CRUD) Create, Read, Update, and Destroy functionality for all objects throughout the application.


