
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
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="#">
    <img src="./images/MusicLabLogo.png" alt="Logo"/>
  </a>

  <h3 align="center">Music Lab</h3>

  <p align="center">
    Make a tune, or don't. It's up to you.
    <br />
    <a href="https://github.com/lpaschka/Music_Lab"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/lpaschka/Music_Lab">View Demo</a>
    ·
    <a href="https://github.com/lpaschka/Music_Lab/issues">Report Bug</a>
    ·
    <a href="https://github.com/lpaschka/Music_Lab/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
        <!-- <li><a href="#prerequisites">Prerequisites</a></li> -->
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

### Our Idea
To create a music app that would allow users to create songs that they could share
with others through our app. Anyone can view a song but a visitor must be logged
in to be able to comment on a song. Songs are saved in a users account for reference.

A list of commonly used resources that I find helpful are listed in the acknowledgements.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Bootstrap](https://getbootstrap.com)
* [FontAwesome](https://fontawesome.com)
* [MySQL](https://mysql.com)
* [Sequelize](https://sequelize.org/)



<!-- GETTING STARTED -->
## Getting Started
There are a few important steps in getting this project setup. Follow the instructions

<!-- ### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```
* My Sql
  ```sh
  npm install npm@latest -g
  ``` -->

### Installation

 <!--Get a free API Key at [https://example.com](https://example.com) -->
1. Clone the repo
   ```sh
   git clone https://github.com/lpaschka/Music_Lab.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Enter your local MySql information in `.env.example`
   ```
    DB_HOST=localhost
    DB_NAME=music_lab
    DB_USER=your_username
    DB_PASSWORD=your_password

    SESSION_SECRET=your_secret_phrase
   ```
4. Seed the DB
   ```sh
   node seeds/index.js
   ```
5. Run the Application
   ```sh
   npm start
   ```
6. View the application:
   [View in Browser](localhost:3001)



<!-- USAGE EXAMPLES -->
## Usage

Visit the site, sign up and make some music. If you would like to contribute please contact us.

_For more examples, please refer to the [Documentation](https://github.com/lpaschka/Music_Lab)_

Heroku Link:
https://dry-wildwood-18175.herokuapp.com/


<!-- ROADMAP -->
## Roadmap

Planned Features:

* Ability to delete and edit songs
* Additional sets of default sounds
* Song rating system
* Make it so users can record sounds to be used within the app, and share those sounds with the community.
* Add song artwork functionality
* Ability to download their own songs as a file to the machine for publish wherever 
* Song categorization and tags for enhanced search

<!-- See the [open issues](https://github.com/lpaschka/Music_Lab/issues) for a list of proposed features (and known issues). -->



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact the Contributors

Drew Olsen - [@drewole](https://github.com/drewole)
Levi Schwartzberg - [@levischwartz](https://github.com/Levischwartzberg)
Luke Paschka - [@lpaschka](https://github.com/lpaschka37)

Project Link: [https://github.com/lpaschka37/Music_Lab](https://github.com/lpaschka37/Music_Lab)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Choose an Open Source License](https://choosealicense.com)
* [Font Awesome](https://fontawesome.com)
* [Bootstrap](https://getbootstrap.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/lpaschka/Music_Lab.svg?style=for-the-badge
[contributors-url]: https://github.com/lpaschka/Music_Lab/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/lpaschka/Music_Lab.svg?style=for-the-badge
[forks-url]: https://github.com/lpaschka/Music_Lab/network/members
[stars-shield]: https://img.shields.io/github/stars/lpaschka/Music_Lab.svg?style=for-the-badge
[stars-url]: https://github.com/lpaschka/Music_Lab/stargazers
[issues-shield]: https://img.shields.io/github/issues/lpaschka/Music_Lab.svg?style=for-the-badge
[issues-url]: https://github.com/lpaschka/Music_Lab/issues
[license-shield]: https://img.shields.io/github/license/lpaschka/Music_Lab.svg?style=for-the-badge
[license-url]: https://github.com/lpaschka/Music_Lab/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/lpaschka
[product-screenshot]: /public/images/screenshot.png
[product-logo]: /public/images/musicLabLogo.png
