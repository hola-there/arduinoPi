<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



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
[![Website Status][website-status-shield]][website-url]

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/hola-there/arduinoPi">
    <img src="design_assets/ardunioPi_logo_Arduino Pi.png" style="background-color:white;" alt="Logo" width="100%">
  </a>

  <h3 align="center">arduinoPi</h3>

  <p align="center">
    An opensource framework that enables easy reuse/management of hardware and code!
    <br />
    <a href="https://github.com/hola-there/arduinoPi_docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/hola-there/arduinoPi">View Site</a>
    ·
    <a href="https://github.com/hola-there/arduinoPi/issues">Report Bug</a>
    ·
    <a href="https://github.com/hola-there/arduinoPi/issues">Request Feature</a>
    ·
    <a href="https://github.com/hola-there/arduinoPi/projects/1">RoadMap Board</a>
    ·
    <a href="https://github.com/hola-there/arduinoPi/projects/2">Bug Project Board</a>
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
        <li><a href="#prerequisites">Prerequisites</a></li>
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

[![Product Name Screen Shot](/design_assets/arduinoPi_Website.png "Screenshot of Main Website")](https://arduinopi.tech/)

This project is meant to make it easier to connect with microcontrolls such as arduinos and other supported by [platformio.org](https://platformio.org/).

### Features

Some of the features of this software includes:
* Faster Sketches
> Edits can be made on the fly with the browser based IDE & PlatformIO. Due to the 32,256 byte limit on Arduino UNO's and similar limits on other microcontrollers being able to modify sketches easily on one or more microcontrollers from any computer or microcomputer speeds things along and due to networking & more being handled by the computer more of the storage limit can be used for the task at hand instead of something that a microcontroller is not made for and may not be secured for usage with.  
* Serial Output Viewer
> Specify the socket and other parameters to view the output of serial connections! This aids the testing process!
* Web UI Control
> Utilize web ui controls in order to direct motors, flash lights, make sounds, open values, & anything else you create!
* Browser Based IDE
> Using the [Microsoft Monaco Editor](https://github.com/microsoft/monaco-editor) users are able to utilize an IDE hosted and connected to ArduinoPi that provides the following features to desktop browsers so mobile browsers nor mobile web app frameworks are supported:
>> Quick file navigation
>> Code Syntax Highlighting
>> Bracket matching
>> Errors & warnings
>> And many more stipulated [here](https://code.visualstudio.com/docs/editor/editingevolved) & [here](https://github.com/microsoft/monaco-editor#monaco-editor).
* Arduino Templates
> A few example templates are provided for some basic arduino projects + some project setup instructions
* Mobile Friendly Control
> Connect and control aspects of the using the platform from wifi capable devices (phones, tablets, laptops, etc.)
* Secure Wifi Control
> Instead of utilizing Bluetooth technology for projects; you can utilize each component in the best way. Microcomputers for more secure network based needs & microcontrollers for precise and accurate analog data procurement or device control.
* Real-time Data Visualization
> After setting up output in a format on the microcontroller; visualize data provided in real-time in browser with [Chart.js](https://www.chartjs.org/). Create your own dashboard, add video input as one of your data sources, & more. Customize the starting point provided to meet you and your project's needs!
* Role-Based Permissions
> Create guest users, add roles, limit permissions and more with local authentication and social media authentication if internet is available!
* 800+ MicroControllers Supported
> More than [800+ other microcontrollers](https://platformio.org/boards) are supported. Feel free to use other microcontrollers; Arduino Uno R3 isn't the only one supported. Try out Arduino Mega's, ESP-xx boards, and more. Due to integration with [PlatformIO](https://platformio.org/)! Even the microcomputer doesn't have to be a Raspberry Pi or even a normal computer can be used. The options are endless as long as the software required are able to be installed on your computer or microcomputer of choice.

### Built With

This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* [Bootstrap](https://getbootstrap.com)
* [Vue Js](https://vuejs.org/)
* [Python 3.X](https://www.python.org/downloads/)
* [Django 3.X](https://www.djangoproject.com)


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

#### Prerequisites on Windows Devices (Windows 10 and Above)
1. Install [Python 3.X](https://www.python.org/downloads/)
#### Prerequisites on Mac Devices (Mac OS 10.X and Above)
#### Prerequisites on Raspberry Pi Devices (Raspberry Pi Zero & 3 + Above)
#### Prerequisites on Linux OS Devices (Kernel... & Above)

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

#### Installation on Windows Devices (Windows 10 and Above)
1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```JS
   const API_KEY = 'ENTER YOUR API';
   ```
5. Collect the api keys needed for social logins or comment out the entire app or specific OAuth2 Logins you don't need/want
6. Run the project
   ```sh
   ...._start_project_command....
   ```
#### Installation on Mac Devices (Mac OS 10.X and Above)
#### Installation on Raspberry Pi Devices (Raspberry Pi Zero & 3 + Above)
#### Installation on Linux OS Devices (Kernel... & Above)

<!-- USAGE EXAMPLES -->
## Usage

Useful examples of how the project can be used will be coming soon.

Additional screenshots, code examples and demos will be added as well. 

I will also link to more resources.

_For more examples, please refer to the [Documentation](https://github.com/hola-there/arduinoPi_docs)_

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/hola-there/arduinoPi/issues) for a list of proposed features (and known issues).
Or see the Project Board created for organizing the proposed and in progress features: https://github.com/hola-there/arduinoPi/projects/1

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
## Contact

# 👋🏿 Ola B.
![image](https://user-images.githubusercontent.com/22028053/118379597-7ca1a180-b5a9-11eb-9bf5-331da8640e5e.png)
* [![Ola's Contact Email:][ola-mail-shield]][ola-mail-url]
* [![Ola's LinkedIn][linkedin-shield]][linkedin-url]
* [![Ola's Twitter][twitter-shield]][twitter-url]
* [![Swapp Technologies][swapp-tech-shield]][swapp-tech-url]
* [![Ola's Website][ola-s-website-shield]][ola-s-website-url]
* My Profile: [![Ola's Profile][ola-s-profile-shield]][ola-s-profile-url]

Project Link: [https://github.com/hola-there/arduinoPi](https://github.com/hola-there/arduinoPi)
Project Docs Link: [https://github.com/hola-there/arduinoPi_docs](https://github.com/hola-there/arduinoPi_docs)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/hola-there/arduinoPi.svg?style=for-the-badge
[contributors-url]: https://github.com/hola-there/arduinoPi/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/hola-there/arduinoPi?style=for-the-badge
[forks-url]: https://github.com/hola-there/arduinoPi/network/members
[stars-shield]: https://img.shields.io/github/stars/hola-there/arduinoPi?style=for-the-badge
[stars-url]: https://github.com/hola-there/arduinoPi/stargazers
[issues-shield]: https://img.shields.io/github/issues/hola-there/arduinoPi?style=for-the-badge
[issues-url]: https://github.com/hola-there/arduinoPi/issues
[license-shield]: https://img.shields.io/github/license/hola-there/arduinoPi?style=for-the-badge
[license-url]: https://github.com/hola-there/arduinoPi/LICENSE
[docs-website-status-shield]: https://img.shields.io/website?down_message=incomplete&style=for-the-badge&up_message=operational&url=https%3A%2F%2Fdocs.arduinopi.tech%2F%23
[docs-website-url]: https://docs.arduinopi.tech/
[website-status-shield]: https://img.shields.io/website?down_message=website%20down&style=for-the-badge&up_message=operational&url=https%3A%2F%2Farduinopi.tech%2F%23
[website-url]: https://arduinopi.tech/
[ola-mail-shield]: https://img.shields.io/badge/📧%20code%40olab%2Cdev-Email%20Ola%20B.-orange?style=for-the-badge
[ola-mail-url]: mailto:code@olab.dev
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/ola-bamisaiye
[twitter-shield]: https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Ftwitter.com%2Folabamisaiye%3Flang%3Den
[twitter-url]: https://twitter.com/olabamisaiye?lang=en
[swapp-tech-shield]: https://img.shields.io/badge/Swapp%20Tech.%20LLC-https%3A%2F%2Fwww.swapp.solutions%2F-blue?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGRhdGEtbmFtZT0iTGF5ZXIgMSIgdmlld0JveD0iLTAuNSAtMC4xIDM1IDM3LjIiIHdpZHRoPSI4MDAiIGhlaWdodD0iODAwIiBzdHlsZT0iJiMxMDsgICAgY29sb3I6IHdoaXRlICFpbXBvcnRhbnQ7JiMxMDsiPjxnIGRhdGEtbmFtZT0iJmx0O0dyb3VwJmd0OyI+PHBhdGggeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiBkYXRhLW5hbWU9IiZsdDtDb21wb3VuZCBQYXRoJmd0OyIgZD0iTTAgMTguMzZ2LjQ5YTMuMjcgMy4yNyAwIDAwMS44NSAyLjQxbDI3LjEgMTUuNThoLjFhNSA1IDAgMDAxLjM5LjIxIDMuMjcgMy4yNyAwIDAwMS44NS0uNTQgNC40IDQuNCAwIDAwMS43LTIuOTRWMy40OGE0LjQgNC40IDAgMDAtMS43LTIuOTQgMy43NCAzLjc0IDAgMDAtMy4yNC0uMzJoLS4xOWwtMjcgMTUuNTJhMy4yNyAzLjI3IDAgMDAtMS44NSAyLjQxem0xLjc2LjA4YTEuNTYgMS41NiAwIDAxLjg0LTFsLjA5LS4wNUwyOS42NCAxLjg4YTIgMiAwIDAxMS42Ny4xMiAyLjYxIDIuNjEgMCAwMS45MiAxLjY5djE0LjJoLTYuNTVhMi4yNCAyLjI0IDAgMTAwIDEuNDFoNi41NXYxNC4xNGEyLjU5IDIuNTkgMCAwMS0uOTIgMS42NCAyIDIgMCAwMS0xLjY3LjEyTDIuNjUgMTkuNjlIMi42YTEuNTMgMS41MyAwIDAxLS44My0xem0yMS43OSAxLjI1YTEuMTkgMS4xOSAwIDAxMC0yLjM4IDEuMTkgMS4xOSAwIDAxMCAyLjM4eiIgZmlsbD0iYmxhY2siLz48cGF0aCBkYXRhLW5hbWU9IiZsdDtDb21wb3VuZCBQYXRoJmd0OyIgZD0iTTUuNzcgMTguNTRhMS44OCAxLjg4IDAgMDAxIDEuNjVsMjEuMyAxMi4yOWExLjg4IDEuODggMCAwMDEuOTEgMCAxLjkgMS45IDAgMDAuOTUtMS42NXYtOS4wNmgtMy40OGwtMi4xNCAyLjE0aC00LjkzYTEuNDIgMS40MiAwIDEwMCAuN2g1LjIzbDIuMTYtMi4xNGgyLjQ4djguMzZhMS4yIDEuMiAwIDAxLTEuOCAxTDcuMDUgMTkuNThhMS4xOCAxLjE4IDAgMDEtLjU1LS42OWg5LjQxYTIuMDcgMi4wNyAwIDEwMC0uN0g2LjVhMS4yMSAxLjIxIDAgMDEuNTUtLjY5TDI4LjQyIDUuMjFhMS4yMiAxLjIyIDAgMDExLjIgMCAxLjE5IDEuMTkgMCAwMS42IDF2OC43OGgtMi40NWwtMi4zLTIuNDhoLTVhMS40IDEuNCAwIDAwLTEuMzctMS4wOSAxLjQyIDEuNDIgMCAxMDAgMi44MyAxLjQxIDEuNDEgMCAwMDEuMzYtMWg0Ljc0bDIuMjEgMi40NGgzLjUyVjYuMjVhMS45MSAxLjkxIDAgMDAtMi44Ni0xLjY1TDYuNyAxNi44OWExLjg4IDEuODggMCAwMC0uOTMgMS42NXptMTQtNS43YS43MS43MSAwIDExLS43MS0uNzIuNzEuNzEgMCAwMS43MS43MnptLTMuMTQgNS43QTEuMzcgMS4zNyAwIDExMTggMTkuOTFhMS4zNiAxLjM2IDAgMDEtMS40Mi0xLjM3em0zLjE0IDUuNzFhLjcxLjcxIDAgMTEtLjcxLS43Mi43MS43MSAwIDAxLjcxLjcyeiIgZmlsbD0iI2ZmZiIvPjwvZz48L3N2Zz4=
[swapp-tech-url]: https://www.swapp.solutions/
[ola-s-website-shield]: https://img.shields.io/badge/🌍%20My%20Website%20LLC-https%3A%2F%2Fcheckout.olabamisaiye.me%2F-blue?style=for-the-badge
[ola-s-website-url]: https://checkout.olabamisaiye.me/
[ola-s-profile-shield]: https://avatars.githubusercontent.com/u/22028053?s=60&v=4
[ola-s-profile-url]: https://github.com/hola-there
