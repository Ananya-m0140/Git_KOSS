The presentation link is given below:
[GIT PRESENTATION.pdf](https://github.com/Ananya-m0140/Git_KOSS/files/14841718/GIT.PRESENTATION.pdf)
<div id="top"></div>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Wiki][wiki-shield]][wiki-url]

</div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/metakgp/gyft">
    <img width="140" alt="image" src="https://github.com/Ananya-m0140/Git_KOSS/assets/153496011/37b7a1cf-0956-4545-9f31-6c45cc08b978">
  </a> -->

  <h1 align="center">kronos2.0</h1>
  <br />
    <a href="https://github.com/metakgp/gyft/issues">Report Bug</a>
    ·
    <a href="https://github.com/metakgp/gyft/issues">Request Feature</a>
  </p>
</div>
<!-- TABLE OF CONTENTS -->
<details>
<summary>Table of Contents</summary>

- [About The Project](#about-the-project)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Development Notes](#development-notes)
  - [Updates To Be Made Each Sem](#updates-to-be-made-each-sem)
- [Contributing](#contributing)
- [Maintainer(s)](#maintainers)

</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This webapp displays previous year's grade distribution. It has been hosted with streamlit as an app but is still under development.

You can go [here](https://kronos.streamlit.app/) for the live version of the project. Make your choices wisely :)

You can find the container image [here](https://hub.docker.com/repository/docker/spookbite/kronosv2).

# Setup 

## (Without Docker)

### 1. Install virtual environment module
```shell
pip install virtualenv
```

### 2. Create a virtual environment (say env) 
```shell
python -m venv env
```

### 3. Activate the virtual environment 
  ```shell
  source env/bin/activate
  ```

### 4. Install Dependencies 
  ```shell
  pip install -r requirements.txt
  ```

### 5. Run the following code on your terminal:
  ```shell
  streamlit run app.py
  ```

## Using Docker

### 1. Pull the Docker image
```shell
docker pull spookbite/kronosv2:latest
```

### 2. Run the container
```shell
docker run -p 8501:8501 spookbite/kronosv2
```

You can change the {PORT}:8501 to your desired PORT.

## Usage
<!-- UPDATE -->
Use this space to show useful examples of how this project can be used. Additional screenshots, code examples and demos work well in this space.

<div align="center">
  <a href="https://github.com/metakgp/PROJECT_NAME">
    <img width="80%" alt="image" src="https://user-images.githubusercontent.com/86282911/206632640-40dc440e-5ef3-4893-be48-618f2bd85f37.png">
  </a>
</div>

<p align="right">(<a href="#top">back to top</a>)</p>

## Contributing

Please read [CONTRIBUTING.md](https://github.com/metakgp/gyft/blob/master/CONTRIBUTING.md) guide to know more.

## Maintainer(s)

- [Arpit Bhardwaj](https://github.com/proffapt)

<!-- MARKDOWN LINKS & IMAGES -->

[contributors-shield]: https://img.shields.io/github/contributors/metakgp/kronos2.0.svg?style=for-the-badge
[contributors-url]: https://github.com/metakgp/kronos2.0/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/metakgp/kronos2.0.svg?style=for-the-badge
[forks-url]: https://github.com/metakgp/kronos2.0/network/members
[stars-shield]: https://img.shields.io/github/stars/metakgp/gyft.svg?style=for-the-badge
[stars-url]: https://github.com/metakgp/kronos2.0/stargazers
[issues-shield]: https://img.shields.io/github/issues/metakgp/gyft.svg?style=for-the-badge
[issues-url]: https://github.com/metakgp/kronos2.0/issues
[license-shield]: https://img.shields.io/github/license/metakgp/gyft.svg?style=for-the-badge
[license-url]: https://github.com/metakgp/kronos2.0/blob/main/LICENSE
[wiki-shield]: https://custom-icon-badges.demolab.com/badge/metakgp_wiki-grey?logo=metakgp_logo&style=for-the-badge
[wiki-url]: https://wiki.metakgp.org

## Contact

<p>
📫 Metakgp -
<a href="https://slack.metakgp.org">
  <img align="center" alt="Metakgp's slack invite" width="22px" src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/slack.svg" />
</a>
<a href="mailto:metakgp@gmail.com">
  <img align="center" alt="Metakgp's email " width="22px" src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/gmail.svg" />
</a>
<a href="https://www.facebook.com/metakgp">
  <img align="center" alt="metakgp's Facebook" width="22px" src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/facebook.svg" />
</a>
<a href="https://www.linkedin.com/company/metakgp-org/">
  <img align="center" alt="metakgp's LinkedIn" width="22px" src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/linkedin.svg" />
</a>
<a href="https://twitter.com/metakgp">
  <img align="center" alt="metakgp's Twitter " width="22px" src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/twitter.svg" />
</a>
<a href="https://www.instagram.com/metakgp_/">
  <img align="center" alt="metakgp's Instagram" width="22px" src="https://raw.githubusercontent.com/edent/SuperTinyIcons/master/images/svg/instagram.svg" />
</a>
</p>

## Credits

This project is inspired by [metakgp/kronos](https://github.com/metakgp/kronos).
