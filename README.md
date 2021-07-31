# Generating and Validating a Metric for Food Insecurity across New Jersey using Regression Based Machine Learning
## 2021 Governor's School of Engineering and Technology (GSET)
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
    <li><a href="#About-GSET">About GSET</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
#### Scholars: Matthew Balestier, Myra Cui, Riya Nandakumar, Anaika Tyagi, Cristian Vintimilla




[![full research paper][researchfull-shield]][researchfull-url]
[![5 pg research paper][research5-shield]][research5-url]
<!-- 

[full research paper](https://soe.rutgers.edu/governors-school-engineering-technology-research-journals) <br>
[IEEE 5 page paper](https://drive.google.com/file/d/1_xD0wUTBtjxomaljPMzFUl4MwFEgipZP/view?usp=sharing)

-->

### Abstract
As the cost of living has continued to increase in New Jersey, many are struggling to meet their basic needs. Food insecurity has progressively become a widespread issue, impacting the lives of thousands within the state. Heightened by the consequences of COVID-19, more New Jersey residents than ever have found themselves lacking secure access to nutritious food. Given the importance of this issue, this research aims to produce an accurate metric using accessible data to quantify food insecurity. To accomplish this, a literature review was conducted in order to gather relevant data sets sorted by year, county, and hypothesized variables indicative of food insecurity. 16 final variables, such as median household income and homeless pop- ulation, were chosen based on if their values were defined across 2015 to 2019. Using multiple linear regression, 14 unique metrics with variables determined by four different variable pruning methods were created. The leading metric, with an R2 value of 0.935, demonstrates the correlation between food insecurity, population, median household income, total population with health insurance, and population with private health insurance. The implementation of this metric could serve as a strong tool in predicting areas of great food insecurity, highlighting affiliated factors, and revealing connections between racial populations.
 
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

<!-- About GSET -->
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
<br>
The authors of this paper would like to gratefully thank the following: Mentor Sachin Mathew for their vast knowledge of data analysis and invaluable guidance; Residential Teaching Assistants Jasmine Khaled and Genevieve Ehasz for their constant supervision throughout the research process; Dean Jean Patrick Antoine for his enthusiastic support and insight; the Governor’s School of Engineering and Technology (GSET) and Rutgers University for the chance to increase our knowl- edge, explore engineering, and pursue new opportunities; the state of New Jersey, alumni, and sponsors for making this program possible; and lastly, NJ GSET Alumni for their continued participation and support.


<!-- MARKDOWN LINKS & IMAGES -->
[researchfull-shield]: https://img.shields.io/badge/-FULL%20RESEARCH%20PAPER-9cf?style=for-the-badge
[researchfull-url]: https://soe.rutgers.edu/governors-school-engineering-technology-research-journals
[research5-shield]: https://img.shields.io/badge/-IEEE%205%20PAGE%20PAPER-9cf?style=for-the-badge
[research5-url]: https://drive.google.com/file/d/1_xD0wUTBtjxomaljPMzFUl4MwFEgipZP/view?usp=sharing
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/myracui/
[license-shield]: https://img.shields.io/badge/LICENSE-MIT-9cf?style=for-the-badge
[license-url]: https://github.com/myracui5/foodinsecurity/blob/main/LICENSE.txt
