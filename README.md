<a name="readme-top"></a>

[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <img src="readme_files/logo.png" alt="Logo" width="80" height="80">
  <h3 align="center">AIR System UCIPs KPI Data Analysis Automation</h3>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#business-case">Business Case</a></li>
        <li><a href="#technical-solution">Technical Solution</a></li>
        <li><a href="#tech-stack">Tech Stack</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


* Project Name: AIR System UCIPs KPI Data Analysis Automation
* Version: v1.0.0
* Organization Department: Technology


### Business Case
The manual process of analyzing UCIPs KPI data for the Ericsson AIR system, involving large datasets and complex weighting algorithms, was highly time-consuming. This project automates the entire analysis workflow, reducing the hours spent on manual calculations to mere seconds. By automating the weighting of transaction records based on node characteristics, this tool significantly improves the speed and accuracy of daily UCIPs KPI analysis, enabling faster decision-making and more efficient resource management.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Technical Solution
This automation tool performs the entire UCIPs KPI analysis, from data acquisition to final insights, in a few seconds. The solution handles two large datasets, applies custom weighting factors, and merges the results for further analysis.

**Key Features:**

* Data Acquisition: Retrieves two large datasets from the Oracle database:
  * First dataset: 49,000 rows x 46 columns
  * Second dataset: 48,000 rows x 68 columns
* Weighted Calculations:
  * Each column is multiplied by a custom factor based on the node characteristics, specifically the node type and its generation (Gen) number.
* The weighting factors vary by node and column type, requiring dynamic calculation.
* Data Merging: After applying the weighting factors, both datasets are merged into a single table for final analysis.
* Utilization Analysis: The tool calculates the maximum utilization percentage across three different categories (or pools) of nodes, providing key insights into system performance.
* Automated CSV Export: Each step of the data processing workflow, including the final dataset, is saved into CSV files for future reference.

Benefits:
* Time Savings: Reduces a process that previously took long hours to just a few seconds.
* Accuracy: Automates complex calculations, reducing the risk of human error.
* Scalability: Handles large datasets daily, ensuring consistent performance regardless of data volume.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Tech Stack

This project was developed using the following tech stack:

* Python (Libraries: pandas, numpy, sqlalchemy, etc.)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Mohamed AbdelGawad Ibrahim - [@m-abdelgawad](https://www.linkedin.com/in/m-abdelgawad/) - <a href="tel:+201069052620">+201069052620</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/m-abdelgawad/
