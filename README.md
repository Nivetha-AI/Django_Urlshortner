# Django_Urlshortner
# URL Shortener Project Overview
This URL shortener project is built using the Django web framework and aims to provide a convenient way to shorten long URLs into shorter, more manageable links. By utilizing the power of Django's models, the project offers a reliable and scalable solution for creating, storing, and redirecting shortened URLs.

# Key Features
Shortening URLs: Users can submit long URLs through a web interface and receive shortened versions in return. These shortened links are generated using a unique identifier and are stored in the system for future use.

Redirection: When a user clicks on a shortened URL, the system redirects them to the original, full-length URL associated with it. This ensures a seamless user experience without any manual intervention.

URL Analytics: The project tracks the number of times each shortened URL is accessed, providing valuable analytics for monitoring link popularity and usage patterns. This data can be used to gain insights into user behavior and measure the effectiveness of specific links.

# Project Structure
The repository for this URL shortener project contains several files and directories. Here's an overview of the important components:

models.py: This file defines the Django models used in the project. It includes a model for storing URL entries, such as the original URL, shortened URL, creation timestamp, and access count.

views.py: The views file contains the logic for handling user requests and generating appropriate responses. It defines functions to render the web interface, process URL submissions, and handle redirection.

urls.py: This file maps URL patterns to their corresponding views. It specifies the routing configuration for the Django application, determining which view functions handle different types of requests.

templates/: This directory contains HTML templates used to render the web pages. It includes templates for displaying the URL submission form, redirection pages, and any additional pages required by the application.

static/: This directory stores static files, such as CSS stylesheets, JavaScript files, and images, used to enhance the visual presentation and functionality of the web interface.
![url](https://github.com/Nivetha-AI/Django_Urlshortner/assets/83387334/fd2c2b8d-1440-4f5b-8917-c0cc80fd9f53)
