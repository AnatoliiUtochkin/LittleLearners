<p align="center"><h1 align="center">LittleLearners</h1></p>
<p align="center">
	<em><code>❯ A modern, responsive school website built with Flask, HTML, SCSS, and JavaScript to enhance communication and accessibility in the educational environment.</code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/AnatoliiUtochkin/LittleLearners?style=for-the-badge&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/AnatoliiUtochkin/LittleLearners?style=for-the-badge&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/AnatoliiUtochkin/LittleLearners?style=for-the-badge&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/AnatoliiUtochkin/LittleLearners?style=for-the-badge&color=0080ff" alt="repo-language-count">
</p>
<p align="center">Built with the tools and technologies:</p>
<p align="center">
	<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white" alt="HTML5">
	<img src="https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white" alt="CSS3">
	<img src="https://img.shields.io/badge/SCSS-CC6699.svg?style=for-the-badge&logo=Sass&logoColor=white" alt="SCSS">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=for-the-badge&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white" alt="Python">
	<img src="https://img.shields.io/badge/Flask-000000.svg?style=for-the-badge&logo=Flask&logoColor=white" alt="Flask">
	<img src="https://img.shields.io/badge/SQLite-003B57.svg?style=for-the-badge&logo=SQLite&logoColor=white" alt="SQLite">
</p>
<br>

## 🔗 Table of Contents

- [📍 Overview](#-overview)
- [👾 Features](#-features)
- [📁 Project Structure](#-project-structure)
  - [📂 Project Index](#-project-index)
- [🎗 License](#-license)
- [📸 Screenshots](#-screenshots)
  
## 📍 Overview

LittleLearners is a responsive and interactive web application for a modern educational institution.
It provides students, teachers, and parents with access to school information, admission details, events, and contact tools.
The project combines frontend technologies (HTML, SCSS, JavaScript) with a Flask backend, offering clean design, dynamic content rendering, and real-time interaction.


## 👾 Features

🌐 Fully responsive layout for desktop and mobile devices

🧩 Modular architecture using Flask and Jinja templates

🎨 Modern, minimalistic user interface

⚙️ Dynamic data rendering from JSON sources

📨 Functional contact form connected to the backend

📚 Pages for academics, admissions, and student life

🧠 Intuitive navigation and accessible UX design


## 📁 Project Structure

```sh
└── LittleLearners/
    ├── LICENSE
    ├── README.md
    ├── app.py
    ├── static
    │   ├── images
    │   ├── scripts
    │   └── styles
    └── templates
        ├── 404.html
        ├── about.html
        ├── academics.html
        ├── admission.html
        ├── base.html
        ├── contact.html
        ├── home.html
        └── student-life.html
```


### 📂 Project Index
<details open>
	<summary><b><code>LITTLELEARNERS</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>/</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/app.py'>app.py</a></b></td>
				<td><code>❯ Main Flask application file</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- templates Submodule -->
		<summary><b>/templates</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/home.html'>home.html</a></b></td>
				<td><code>❯ Main landing page of the website</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/about.html'>about.html</a></b></td>
				<td><code>❯ Provides information about the school’s history, mission, vision, and teaching philosophy.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/student-life.html'>student-life.html</a></b></td>
				<td><code>❯ Showcases extracurricular activities, student clubs, and school events with gallery support.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/admission.html'>admission.html</a></b></td>
				<td><code>❯ Displays the admission process, requirements, and fee details fetched from a JSON file.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/academics.html'>academics.html</a></b></td>
				<td><code>❯ Highlights academic programs, curriculum structure, and teaching methodology.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/base.html'>base.html</a></b></td>
				<td><code>❯ Parent layout template used across all pages — contains header, footer, and navigation bar components.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/404.html'>404.html</a></b></td>
				<td><code>❯ Custom “Page Not Found” error page that maintains consistent styling with the rest of the website.</code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/AnatoliiUtochkin/LittleLearners/blob/master/templates/contact.html'>contact.html</a></b></td>
				<td><code>❯ Contact and feedback page with a working form that submits data to the Flask backend.</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

## 🎗 License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).  
For full details, please see the [LICENSE](LICENSE) file.

## 📸 Screenshots

<table>
  <tr>
    <td><img src="screenshots/1.png" alt="Screenshot 1" width="400"/></td>
    <td><img src="screenshots/2.png" alt="Screenshot 2" width="400"/></td>
    <td><img src="screenshots/3.png" alt="Screenshot 3" width="400"/></td>
  </tr>
  <tr>
	<td><img src="screenshots/4.png" alt="Screenshot 6" width="400"/></td>
    <td><img src="screenshots/5.png" alt="Screenshot 7" width="400"/></td>
    <td><img src="screenshots/6.png" alt="Screenshot 8" width="400"/></td>
  </tr>
</table>
