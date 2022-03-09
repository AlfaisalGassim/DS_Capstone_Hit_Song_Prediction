<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
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
[![LinkedIn][linkedin-shield]][linkedin-url]

##

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="img/skills-new.jpg" alt="Logo">
  </a>

<h3 align="center">MISK DSI - Hit Song Predection</h3>

  <p align="center">
  <!--  This is project for Misk Skills - Data Science Immersive 2021-02. The goal is to build a model to predit what make a song a hit song. Using Billboerd hot 100 weekly list. -->
    <br />
    <a href="https://github.com/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction"><strong>Explore the docs »</strong></a>
    <br />
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
      <a href="#explatory-data-analysis">Explatory Data Analysis</a>
      <ul>
        <li><a href="#data-source">Data Source</a></li>
        <li><a href="#dictonary">Dictonary</a></li>
        <li><a href="#spotify-api">Spotify API</a></li>
      </ul>
    </li>
    <li><a href="#machine-learning">Machine learning</a></li>
    <li><a href="#refrances">Refrances</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

This is project for Misk Skills - Data Science Immersive 2021-02. The goal is to build a model to predit what make a song a hit song. Using Billboerd hot 100 weekly list.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Python](https://www.python.org/)
* [Spotify API](https://developer.spotify.com/documentation/web-api/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Explatory Data Analysis

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Data source 

Data downloaded form kaggle.
[Billboard "The Hot 100" Songs](https://www.kaggle.com/dhruvildave/billboard-the-hot-100-songs)

### Dictonary 


| #  | Column          | Description     |
| -- |  --------       |    --------     |
| 0  | date            | The chart week  |
| 1  | rank            | the rank of the song on that week  |
| 2  | song            | Name of the song  |
| 3  | artist          | Artist including featured artists  |
| 4  | last-week       | The rank of the song on the previos week. Null mean the song was not on the chart last week or its it frist time entring the hot 100 |
| 5  | peak-rank       | The highest rank the song got on the chart on it life time. throuout all the weeks |
| 6  | weeks-on-board  | Number of weeks the song has been on the bored   | object  |

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Spotify API

* For this i will be using Spotify api to collect songs information from Spotify. 
* I will need to create a spotify developer account or login using my current account.
* Get the client ID and client secret from spotify.
* Write the script for the API,  I followed along with this video HERE.


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Machine learning


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Refrances

* Data Source [Billboard "The Hot 100" Songs](https://www.kaggle.com/dhruvildave/billboard-the-hot-100-songs)
* Spotify API [Spotify for Developers](https://developer.spotify.com/documentation/web-api/)
* Spotify Scrept Gudie [30-Days-of-Python](https://github.com/codingforentrepreneurs/30-Days-of-Python/tree/master/tutorial-reference/Day%2019)
* README Template [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Alfaisal Alqahtani - [Linkedin](https://www.linkedin.com/in/alfaisal-gassim-581029158/)

Project Link: [DS_Capstone_Hit_Song_Prediction](https://github.com/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction)

<p align="right">(<a href="#top">back to top</a>)</p>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction.svg?style=for-the-badge
[contributors-url]: https://github.com/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction.svg?style=for-the-badge
[forks-url]: https://github.com/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction/network/members
[stars-shield]: https://img.shields.io/github/stars/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction.svg?style=for-the-badge
[stars-url]: https://github.com/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction/stargazers
[issues-shield]: https://img.shields.io/github/issues/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction.svg?style=for-the-badge
[issues-url]: https://github.com/AlfaisalGassim/DS_Capstone_Hit_Song_Prediction/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alfaisal-gassim-581029158/
[product-screenshot]: images/screenshot.png
