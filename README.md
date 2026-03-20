<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
<div align="center">

[![Contributors][contributors-shield]][contributors-url] [![Forks][forks-shield]][forks-url] [![Stargazers][stars-shield]][stars-url] [![Issues][issues-shield]][issues-url] [![LinkedIn][linkedin-shield]][linkedin-url]

</div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">Hospital Management System</h3>

  <p align="center">
    A comprehensive Hospital Management System leveraging custom Data Structures, a MySQL database, and an animated JavaFX interface!
    <br />
    <br />
    <a href="https://github.com/AmmarKeon/Hospital_Management_System/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/AmmarKeon/Hospital_Management_System/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage--video-demo">Usage & Video Demo</a></li>
    <li><a href="#features--implementation">Features & Implementation</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This is my most comprehensive project yet, It's a robust **Hospital Management System** heavily focused on both back-end architecture and front-end user experience. 

On the back-end side, it deviates from simple built-in collections and focuses strictly on implementing custom algorithms and data structures from scratch:
*   **Binary Search Trees (BST)** for fast and optimal patient record lookups and manipulation (`PatientBST`).
*   **Priority Queues** to successfully handle hospital waiting lists, prioritizing patient emergencies gracefully.

Additionally, It integrates seamlessly with an external **MySQL Database** for full persistent data storage (billing, patients, and appointments).

On the front side, I have pushed my boundaries and mastered **JavaFX** to create a deeply polished UI, integrating modern fonts (`Electrolize.ttf`), CSS styling, and custom animations to give interactive elements a premium UI/UX modern feel.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

<div align="center">

[![Java][Java.com]][Java-url] [![JavaFX][JavaFX.com]][JavaFX-url] [![CSS][CSS.com]][CSS-url] [![MySQL][MySQL.com]][MySQL-url]

</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* Java Development Kit (JDK) 8 or higher
* JavaFX SDK (if not included in your JDK)
* MySQL Server (Ensure it is running locally or remotely)
* An IDE like IntelliJ IDEA, Eclipse, or VS Code

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/AmmarKeon/Hospital_Management_System.git
   ```
2. Open the project in your IDE.
3. Setup the MySQL Database:
   * Import the provided `hospital_db.sql` database dump included in the `DataProject` folder into your MySQL server.
   * Update the connection credentials in the `DatabaseManager.java` file (or respective config) if needed.
4. Add the provided MySQL Connector (`mysql-connector-j-9.1.0.jar`) to your project structure/dependencies if not using an automated build tool.
5. Configure the JavaFX SDK path in your module settings or build configurations if needed.
6. Run the main class of the application.

*Note if you wish to use Maven or Gradle to setup JavaFX, use https://openjfx.io/openjfx-docs/ and head to your preferable tool setup guide.*

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage & Video Demo

GUI fully created by myself, not fancy but definitely robust and clean, prioritizing user experience.

[![Hospital Management System Video Demo](https://img.youtube.com/vi/GMwysgPQYoQ/maxresdefault.jpg)](https://youtu.be/GMwysgPQYoQ "Watch the Showcase on YouTube")

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FEATURES IMPLEMENTED -->
## Features & Implementation

Here's an overview of the core modules explicitly driving the system:

* **Patient Management:** Create, delete, update, and search patient details rapidly using custom `PatientBST` routing.
* **Appointments & Waiting List:** Add appointments for patients and queue them inside a managed `PriorityQueue` based on appointment type or emergency severity.
* **Billing & Reporting:** Code leverages `BillingManager` and `ReportGenerator` closely integrated securely with the hospital SQL tables.
* **Interactive UI:** Mastered JavaFX view elements driving a highly polished interactive user GUI flow with smooth Java/CSS transitions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

You can fork the project and add features/adjust code to what your heart desires.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Ammar - [Github Profile](https://github.com/AmmarKeon) - ammarkeon@gmail.com

Project Link: [https://github.com/AmmarKeon/Hospital_Management_System](https://github.com/AmmarKeon/Hospital_Management_System)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/AmmarKeon/Hospital_Management_System.svg?style=for-the-badge
[contributors-url]: https://github.com/AmmarKeon/Hospital_Management_System/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AmmarKeon/Hospital_Management_System.svg?style=for-the-badge
[forks-url]: https://github.com/AmmarKeon/Hospital_Management_System/network/members
[stars-shield]: https://img.shields.io/github/stars/AmmarKeon/Hospital_Management_System.svg?style=for-the-badge
[stars-url]: https://github.com/AmmarKeon/Hospital_Management_System/stargazers
[issues-shield]: https://img.shields.io/github/issues/AmmarKeon/Hospital_Management_System.svg?style=for-the-badge
[issues-url]: https://github.com/AmmarKeon/Hospital_Management_System/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ammarkeon/
[Java.com]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[Java-url]: https://www.java.com/
[JavaFX.com]: https://img.shields.io/badge/JavaFX-FF0000?style=for-the-badge&logo=java&logoColor=white
[JavaFX-url]: https://openjfx.io/
[CSS.com]: https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white
[CSS-url]: https://developer.mozilla.org/en-US/docs/Web/CSS
[MySQL.com]: https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com/