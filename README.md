# Project API RESTful Planner with Spring Boot

## Table of Contents

1. [General Objective](#general-objective)
2. [Project Overview](#project-overview)
   1. [Features](#features)
   2. [Maven Dependencies](#maven-dependencies)
3. [Technologies Used](#technologies-used)
4. [Versions](#versions)
5. [Installations](#installations)

---

## General Objective

- Help the user organize trips for work or leisure. 
- The user can create a trip with a name, start and end date. 
- Within the trip, the user can plan their trip by adding activities to carry out each day.

---

## Project Overview

### Features

- The user registers a trip by informing the destination location, start date, end date, guests' emails and also their full name and email address.
- The trip creator receives an email to confirm the new trip via a link. When clicking on the link, the trip is confirmed, guests receive attendance confirmation emails and the creator is redirected to the trip page.
- Guests, when clicking on the confirmation link, are redirected to the application where they must enter their name (in addition to the email that will already be filled in) and will then be confirmed on the trip.
- On the event page, trip participants can add important travel links such as AirBnB reservations, places to visit, etc…
- Still on the event page, the creator and guests can add activities that will occur during the trip with title, date and time.
- New participants can be invited within the event page via email and must go through the confirmation flow like any other guest.
 
### Maven Dependencies

- Spring Boot DevTools
- Spring Web
- Spring Data JPA
- Flyway
- Lombok
- H2 Database

---

## Technologies Used

- Java
- Spring Framework
- H2 database

---

## Versions

- Java 21 
- Spring Boot 3.3.1

---

## Installations

- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/?section=mac)
- [Insomnia](https://insomnia.rest/download)





