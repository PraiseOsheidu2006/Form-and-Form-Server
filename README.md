# Form and Form Server

This project demonstrates how to use forms and integrate them with a server to handle submissions. The server processes the form data, showcasing how backend and frontend interact in a simple web application.

## How to work with the server

To work with the server you have to first download this on your local machine, run 

```
git clone https://github.com/Ayomide-Philip/Form-and-Form-Server.git
```

## How to use the Server
You need to have Node on Your system, and to use the server, you need to run

```
cd "Form Server"
```
When you run that command it would change the directory to the form server directory.

## Form Server file structure

```
              |
              |---- Public 
              |        |------ Images
              |        |------ Stylesheet
              |        |------ Script
              |
              |---- Views
              |---- Index.js
```

### How to Install the required Node Module
Due to the use of NodeJS, i used some node package to run the server like:

```
    body-parser: V1.20.2
    ejs: V3.1.10,
    express: V4.19.2
```

To install all the required module you do 

```
npm i
```
By running the above command, it looks inside the package.json in the Form Server, and looks for all the package needed.

## Starting the Server
After installing all the need  package what you need to do is to start the server

