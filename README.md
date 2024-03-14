# JSON_Server_Deployment


This repository contains a simple guide for deploying a JSON Server using `json-server`. JSON Server is a Node.js package that allows you to create demo APIs with zero coding effort based on a JSON file.

## Prerequisites

- Node.js installed on your machine. You can download it [here](https://nodejs.org/).
- Basic understanding of the command line interface (CLI).

## Setup

1. Clone this repository to your local machine:

   ```bash
   git clone <https://github.com/shashikantRupin/talentrax-backend>


## Deploying on Render
You can also deploy your JSON Server on Render. Follow these steps:

Sign up or log in to Render.

Create a new Web Service.

Choose the GitHub repository where your JSON file and db.json are located.

Configure the service to run the following command:
 ```bash
  json-server --watch db.json --port $PORT
Deploy your service.

Once deployed, Render will provide you with a URL where your JSON Server is hosted.
