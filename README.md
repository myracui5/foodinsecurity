# Regression Based Machine Learning to Generate and Validate a Metric for Food Insecurity
## 2021 Governor's School of Engineering and Technology (GSET)
### Scholars: Matthew Balestier, Myra Cui, Riya Nandakumar, Anaika Tyagi, Cristian Vintimilla

[![MIT License][license-shield]][license-url]

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#abstract">Abstract</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#about-gset">About GSET</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<!-- 
[![full research paper][researchfull-shield]][researchfull-url]
[![5 pg research paper][research5-shield]][research5-url]


[full research paper](https://soe.rutgers.edu/governors-school-engineering-technology-research-journals) <br>
[IEEE 5 page paper](https://drive.google.com/file/d/1_xD0wUTBtjxomaljPMzFUl4MwFEgipZP/view?usp=sharing)

-->

### Abstract
With the increased cost of living, exacerbated by COVID-19, thousands in New Jersey lack secure access to nutri- tious food. Given the importance of the issue, this research aims to produce an accurate metric using accessible data to quantify food insecurity. 16 potential explanatory variables, such as median household income and homeless population, were chosen as their values were defined across all NJ counties from 2015-2019. Using multiple linear regression, 14 unique metrics were created after four different variable pruning methods. The leading metric, with an adj. R2 value of 0.932, demonstrates the correlation between food insecurity, population, median household income, total population with health insurance, and population with private health insurance. The implementation of this metric could serve as a tool in predicting areas of food insecurity, highlighting affiliated factors, and revealing connections between racial populations.
 
### Built With
Python libraries and packages:
* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Scikit-Learn](https://scikit-learn.org/stable/)
* [Matplotlib](https://matplotlib.org/)
* [Statsmodels](https://www.statsmodels.org/stable/index.html)
* [Seaborn](https://seaborn.pydata.org/)
* [Geopandas](https://geopandas.org/)

<!-- GETTING STARTED -->
## Getting Started

This project was created on Jupyter Notebook, an open-source and browser-based application for collaborative documents, data manipulation, statistical analysis, and more.
* [Jupyter Notebook](https://jupyter.org/)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/myracui5/foodinsecurity.git
   ```
3. Install Jupyter Notebook
   ```sh
   pip install notebook
   ```
4. Run Jupyter Notebook
   ```sh
   jupyter notebook
   ```

<!-- ABOUT GSET -->
### About GSET
The New Jersey Governor's School of Engineering & Technology at Rutgers University is an intensive residential summer program that brings together some of New Jersey's most talented and motivated high school students. Free of grades and official credit, students spend part of the summer following their junior year studying on the campus of the Rutgers University School of Engineering at no cost to their families. During the program, students will have the opportunity to collaborate with other students on a novel research project which will be showcased in a conference-style final paper and presentation in front of hundreds of invited guests at our research symposium.  Additionally, students will be able to participate in a variety of life-skills workshops, attend site visits to local corporations, and engage in activities that will help them connect with professors, professionals, and peers from throughout the state.
<br>
<br>
All applicants must be nominated by their high schools. (High schools can nominate one applicant for every 325 members of their junior class. i.e. a school with 100 juniors may nominate 1 student; a school with 400 juniors may nominate 2 students; a school with 645 juniors may also nominate only 2 students). Admission to the program is very competitive. Following a competitive process at each high school in which dozens of students may express interest in attending the program, we generally receive between 300 and 400 applications from these nominees. Of the nominees, who are the best and brightest students at their respective schools, fewer than 25% generally receive offers of admission.

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->
## Contact
[![LinkedIn][linkedin-shield]][linkedin-url] <br>
Myra Cui: email - myracui5@gmail.com <br>


Project Link: [https://github.com/myracui5/foodinsecurity](https://github.com/myracui5/foodinsecurity)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
The authors of this paper would like to gratefully thank the following: <br>
<ul>
  <li> Mentor <strong><em> Sachin Mathew </em></strong> for their vast knowledge of data analysis and invaluable guidance </li>
  <li> Residential Teaching Assistants <strong>Jasmine Khaled </strong> and <strong>Genevieve Ehasz </strong> for their constant supervision throughout the research process </li>
  <li> <strong><em>Dean Jean Patrick Antoine </em></strong>for his enthusiastic support and insight; the Governor’s School of Engineering and Technology (GSET) and Rutgers University for the chance to increase our knowledge, explore engineering, and pursue new opportunities </li>
  <li><strong><em>The state of New Jersey, alumni, and sponsors </em></strong>for making this program possible </li>
  <li> <strong><em>NJ GSET Alumni </em></strong>for their continued participation and support </li>
</ul>

## With love :heart:
<img src = "images/gset21.jpg" width = 565>



<!-- MARKDOWN LINKS & IMAGES -->
[researchfull-shield]: https://img.shields.io/badge/-FULL%20RESEARCH%20PAPER-9cf?style=for-the-badge
[researchfull-url]: https://soe.rutgers.edu/governors-school-engineering-technology-research-journals
[research5-shield]: https://img.shields.io/badge/-IEEE%205%20PAGE%20PAPER-9cf?style=for-the-badge
[research5-url]: https://drive.google.com/file/d/1_xD0wUTBtjxomaljPMzFUl4MwFEgipZP/view?usp=sharing
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/myracui/
[license-shield]: https://img.shields.io/badge/LICENSE-MIT-9cf?style=for-the-badge
[license-url]: https://github.com/myracui5/foodinsecurity/blob/main/LICENSE.txt
