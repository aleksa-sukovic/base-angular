# Base Angular setup 

This repository serves as starting point for my Angular based web applications.

## What is included

1.) Angular 8

2.) Tailwind CSS

3.) Docker configuration

## Allowed commands

1.) docker exec -it base-angular ng test --watch=false

2.) docker exec -it base-angular ng e2e --port 4201

3.) docker exec -it base-angular bash

## Setup

1. Clone this repository wherever you see fit.
2. From terminal, navigate to cloned repository.
3. Run `docker-compose build`.
4. Run `docker-compose up`.
5. From host machine: `docker exec -it base-angular bash`.
6. Run `npm i`.
7. Run `ng serve --host 0.0.0.0`.
8. Navigate to *http://localhost:4200*.
9. Upon next container initialization, command number 8. will be automatically run.
