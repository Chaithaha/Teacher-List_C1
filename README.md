Cumulative01 Teacher Management System
Welcome! This project is a straightforward Teacher Management System that allows users to interact with an API to retrieve and display teacher information. It is developed using ASP.NET Core and utilizes MySQL for data storage and management.

Table of Contents
Project Overview

Technologies Used

API Endpoints

Controller Functions

Frontend Integration

Setup Guide

Project Overview
This system is divided into two primary components:

API Controller – Handles database interactions to retrieve teacher data.

Page Controller – Passes the retrieved teacher information to the frontend, displaying it in a list or detailed format.

Key features include:

Viewing a complete list of teachers

Accessing detailed information about a specific teacher using their ID

Filtering teachers based on their hire date

Technologies Used
ASP.NET Core – Framework for building the web application

MySQL – Database for storing teacher details

C# – Programming language for backend development

MVC Architecture – Used to structure the application

API Endpoints
1. TeacherAPIController
This controller processes requests related to teacher data.

GET api/Teacher/List

Retrieves all teacher records from the database.
