# Web Flask Project

A sub-project within AirBnB where Flask was utilized to integrate the back-end storage engine with the web static HTML/CSS pages previously developed.

## Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
- [Features](#features)

## About

This project aimed to enhance the AirBnB platform by integrating Flask. It involved the gradual development of templates based on the existing HTML pages for HBnB. The most comprehensive Flask app-template can be found in the Flask module `100-hbnb.py`.

## Getting Started

To run the Flask app, follow these instructions:

1. Execute the following command from the root directory of the project:

   ```bash
   HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_flask.100-hbnb
   ```

2. The app can be accessed at `0.0.0.0:5000/hbnb`.

## Features

- Integration of Flask
- Gradual development of complex templates based on HTML pages
- Seamless integration of the back-end storage engine with web static HTML/CSS pages
