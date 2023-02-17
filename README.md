<a name="readme-top"></a>

<div align="center">
  <h2 align="center">STM8 LCD I2C LIBRARY</h2>

  <p align="center">
    Library for stm8 to work with LCD with I2C convertor
    <br />
    <a href="https://github.com/matejkrenek/stm8-lcd-i2c/issues">Report Bug</a>
    ·
    <a href="https://github.com/matejkrenek/stm8-lcd-i2c/issues">Request Feature</a>
  </p>
</div>

<br/>

<!-- TABLE OF CONTENTS -->
### Table of contents
  <li>
    <a href="#about-the-toolchain">About The Library</a>
  </li>
  <li>
    <a href="#installation">Installation</a>
    <ul>
      <li><a href="#requirements">Requirements</a></li>
    </ul>
  </li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#limitations">Limitations</a></li>



<!-- ABOUT THE LIBRARY -->
## About The Library

This toolchain is based on compilation with SDCC and programming the controller with STVP. This allows you to use all the features of C99 standard and use any programmer that is supported by STVP.

In addition to this, unused functions are removed during compilation with the use of sdccrm.

<!-- INSTALLATION -->
## Installation

Follow all the steps below for desired functionality of the toolchain.

Disclaimer: the steps are described for windows because i suppose linux users are much smarter than windows users so they don't need to be guided XD

### Requirements

Before running the toolchain on your machine, some necessary tools need to be downloaded.

You may have some of these tools already downloaded.

<!-- USAGE EXAMPLES -->
## Usage
- After any adjustment of config.js run:

   ```sh
   make update
   ```
   or
   
   ```sh
   make install
   ```
- For libraries there is associated folder lib:

   ```sh
   |--app
      |--inc
      |--src
   |--lib
      |--SPL
        |--inc
        |--src
      |--Your-Library
        |--inc
        |--src
   ```

<!-- CONTACT -->
## Contact

Matěj Křenek - [mate23.krenek@gmail.com](mailto:mate23.krenek@gmail.com)

Project Link: [https://github.com/matejkrenek/stm8-toolchain](https://github.com/matejkrenek/stm8-toolchain)

<!-- LIMITATIONS -->
## Limitations

- You have to run make file commands in git bash 😥
