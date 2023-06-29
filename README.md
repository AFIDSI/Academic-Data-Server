<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<p align="center">
	<div align="center">
		<img src="./images/icon.svg" alt="Logo" style="width:33%">
	</div>
</p>

<!-- ABOUT THE PROJECT -->
# Academic Data Server

This is a server application / API for managing academic data.  It allows storing and retreiving data about university people and activities such as grants, articles, and patents.

## Applications
This data server is used in the [University of Wisconsin Campus Knowledge Map](http://datascience.sharedigm.com/cmap).
<p align="center">
	<div align="center">
		<img src="./images/knowledge-map.png" alt="UW Campus Knowledge Map" style="width:75%">
		<div style="text-align:center">
			<label>UW Campus Knowledge Map</label>
		</div>
	</div>
</p>
<p align="center">
	<div align="center">
		<img src="./images/knowledge-map-grants.png" alt="UW Campus Knowledge Map Search Results" style="width:75%">
		<div style="text-align:center">
			<label>Example UW Campus Knowledge Map Search Results</label>
		</div>
	</div>
</p>

<!-- GETTING STARTED -->
## Documentation
The API routes that are implemented by this data server are described in the
[Academic Data API Reference](docs/academic_data_api_reference.pdf).

## Requirements

- PHP 8.0
- A SQL Database (MySql or MariaDB)

## Built With

The following tools and frameworks were used in the construction of this project:

* [![Laravel][Laravel.com]][Laravel-url]

## Configuration

Before running these scripts, you will need to first create a database to store the information.

1. Create a database

First, you'll want to create a database to store the information.  The database schema that is used for this utility is located in the file: [database/academic_data_structure.sql](database/academic_data_structure.sql).

2. Configure your web server

Since this is a web server application, you will need to configure your web server to run it.  Please see the documentation for your particular type of web server ([Apache](https://httpd.apache.org), [Nginx](https://www.nginx.com), etc.) for details.

3. Configure the .env file

Next, you'll need to configure the academic data server to connect with your database.  This application is built on top of the [Laravel](https://laravel.com) framework, so please see the [Laravel documentation](https://laravel.com/docs/10.x/configuration) for details.

<!-- LICENSE -->
## License

Distributed under the MIT License. See the [license](./LICENSE.txt) for more information.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This project was funded by the [American Family Insurance Data Science Institute](https://datascience.wisc.edu) at the [Univeristy of Wisconsin-Madison](https://www.wisc.edu)

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/AFIDSI/Academic-Data-Server/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/AFIDSI/Academic-Data-Server/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/AFIDSI/Academic-Data-Server/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/AFIDSI/Academic-Data-Server/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/AFIDSI/Academic-Data-Server/LICENSE.txt
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com