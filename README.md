
<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->
<div align="center">

[![LinkedIn][linkedin-shield]][linkedin-url]

</div>
<!-- PROJECT LOGO -->
<div align="center">
  <a href="https://github.com/Zulqarnain-cc34/Flocking">
    <img src="bird.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Flocking</h3>

  <p align="center">
    This is an implemetation of the flocking algorithm on boids.
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details >
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#references">references</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<!--  [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

  <a href="https://github.com/Zulqarnain-cc34/Flocking">
    <img src="flocking.png" alt="screenshot">
  </a>

This is an implementation of flocking Algorithm in which our entities boids follow the three main priciples.
- Seperation
- Cohesion
- Alignment

The result is 

![Flocking](flocking.gif)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Alignment
Takes all the boids in the canvas and calculates the group vector for the boids in the perception radius. Then normalizes the group vector to an average vector. Subtracts the own boids velocity from
the average boids velocity to get the vector which when added to our velocity will align the boid w.r.t to the flock in the perpection radius. 


<!-- GETTING STARTED -->
## Getting Started

The instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Installation

1. Clone the Repo
   ```sh
   git clone https://github.com/Zulqarnain-cc34/Flocking.git
   ```
2. Open the index.html file in any browser.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- References-->
## References

1. https://github.com/CodingTrain

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/muhammad-zulqarnain-a29664247 



