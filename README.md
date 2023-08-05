# Sir Silver-Screen Rentals

## Overview

This is an application suite with local database connections and online capabilities that will provide a fictional video store rental team the ability to create video rental records when customers of their store rent (or buy) videos and/or video games.

The system's server operates on a RESTful structure, thus it requires a valid and authorised user profile with an accompanying session key(s) to retrieve server and/or modify server data. These are some of the (possible) features and functions it includes:
- Storing, retrieving and modifying of customer and rental information
- Constant tracking of rentals' statuses, availability (physical media) and pricing
- Tracking rental history per individual customer
- Profiling customers and suggesting movie rentals based on their rental history and declared preferences
- Detailed categorisation of rentable multimedia (movies, games, series, etc.)

Admin access on the server is only available through the desktop application. The interface is focused on presenting the operator (owner, employee, administrator, system controller) with detailed information of the statuses of rental media, rental trends, client information, system configuration settings and a few other features dependent on their significance or necessity. 

Client side of the system is multiplatform (web, mobile) and provides the end-user with a catalog of the media they are able to rent, past history of their rentals, option to rate and review rented media, deposit funds into their account as well as other account-related functions to ensure continued access to the system (e.g. changing passwords, personal and payment details, etc.)

## Programming Languages
- PHP (server)
- C# (desktop client)
- JavaScript (web client)
- HTML (web client)
- Android (Kotlin) (mobile client)

## Frameworks
- .NET Framework (desktop)

## Server platform:
- Apache 2.4.x

## Database system:
- MySQL (server)
- SQLite (mobile, client storage)

