# E-Commerce challenge

## Table of Contents
* [Description](#description)
* [Built-With](#built-with)
* [Demo](#demo)
* [Installation](#installation)
* [Usage](#usage)
* [Questions](#questions)

## Description

This is an interactive command-line application built with Node and Express that allows a user to perform Insomnia requests on product, category, and tag information stored within a MYSQL database.

## Built-With
<p>
  <img src="https://img.shields.io/badge/-Dotenv-ff69b4" />
  <img src="https://img.shields.io/badge/-ORM-brightgreen" />
  <img src="https://img.shields.io/badge/-Insomnia-red" />
  <img src="https://img.shields.io/badge/-Javascript-blueviolet" />
  <img src="https://img.shields.io/badge/-Express-grey" />
  <img src="https://img.shields.io/badge/MySql2-orange"  />
  <img src="https://img.shields.io/badge/-Node-green" />
  <img src="https://img.shields.io/badge/-SQL-blue" />
</p>

## Demo

The following link includes a video demo of the application's functionality:

[Employee Tracker Video Demo](https://drive.google.com/file/d/19RUEuH3K7C8n6PwJtaqhJJuPVSEMwqab/view)


## Installation

The user will first need to download the Node.js application onto their computer and then install the required packages by typing `npm i` into the terminal.

## Usage

In order to run this application, the user will need to type `mysql -u root -p` into the terminal to launch Sequelize. From there, the user will select the 'e-commerce' database by typing `SOURCE db/schema.sql;` and then `exit`. A user can then enter `npm run seed` to seed the database, and finally `npm run start` to start the server.

Once in Insomnia, a user can make get requests for all products, categories or tags, as well as get by Id, post(create), put(update) by Id, and delete by Id requests.

## Questions

If there are additional questions, please reach out to me here:

* GitHub: https://github.com/Seropyan1995
* Email: seropyangevork@rocketmail.com
