# amitree-interact

## This application aims to interact with the Amitree API and demonstates how developers can exploit the capabilities of the API.

<hr/>
<h2 style="text-align: center"><a href="https://ioanniskousis.github.io/amitree-interact/">Working Demo</a></h2>

<hr/>

<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
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

<hr/>

<!-- ABOUT THE PROJECT -->

## About the project

<br/>

The file index.html contains all the functionality to be demonstrated.  
<br/>
<hr/>
<br/>

- Adding a referral_code search parameter i.e 

```
/index.html?referral_code=some_valid_referral_code 
```

will insert the code into the signup form

<h2 style="text-align: center"><a href="https://ioanniskousis.github.io/amitree-interact?referral_code=cce01187a4764b5f09ee">Sample</a></h2>


<hr/>
<br/>

- By default the requests are directed to 

```
https://boiling-fjord-82978.herokuapp.com
```
where a runing version is hosted at heroku

Adding an apiURL search parameter i.e 

```
/index.html?apiURL=http://localhost:3000
```

the app will do the requests to your local runing rails server

Note that you may need to adjust the connection port 3000 to what is appropriate

<h2 style="text-align: center"><a href="https://ioanniskousis.github.io/amitree-interact?apiURL=http://localhost:3000">Sample</a></h2>

<hr/>
<br/>

- Alternatively
  
You may edit the file close to line 172 to adjust the preferred server address

<br/>
<hr/>
<br/>

<!-- CONTACT -->

## Contributors

:bust_in_silhouette: **Author**

## Ioannis Kousis

- Github: [@ioanniskousis](https://github.com/ioanniskousis)
- Linkedin: [Ioannis Kousis](https://www.linkedin.com/in/jgkousis)
- E-mail: jgkousis@gmail.com

<br/>
<hr/>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/ioanniskousis/amitree-interact.svg?style=flat-square
[contributors-url]: https://github.com/ioanniskousis/amitree-interact/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ioanniskousis/amitree-interact.svg?style=flat-square
[forks-url]: https://github.com/ioanniskousis/amitree-interact/network/members
[stars-shield]: https://img.shields.io/github/stars/ioanniskousis/amitree-interact.svg?style=flat-square
[stars-url]: https://github.com/ioanniskousis/amitree-interact/stargazers
[issues-shield]: https://img.shields.io/github/issues/ioanniskousis/amitree-interact.svg?style=flat-square
[issues-url]: https://github.com/ioanniskousis/amitree-interact/issues
