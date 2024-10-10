# Introduction

This project uses **P**lain **O**ld **J**ava to store, manipulate, process
and save user data into a PostgreSQL database.

> **WARNING:** This project is **NOT** recommended to be used in production environment or any real world application, it lacks security for such sensible data.

The main focus of this project is to save data into the database using JDBC and create HTTP requests using POJO, not 
using SpringBoot.

It's been created to compare the efficiency using POJO and using SpringBoot, nothing too crazy...

## Comparison 

In this project, there's no need to use SpringBoot dependencies or anything. 

For the project using SpringBoot, the repository is located [here]()

The main focus of the comparison is to validate the time to start the app, the time needed to process, save and retrieve
the data from the database and the overall size of the project, and check if it's better to use SpringBoot or stick with
the POJO strategy.