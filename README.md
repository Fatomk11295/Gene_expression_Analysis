
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<div align="center" width="50">
<img src="https://bitesizebio.com/wp-content/uploads/2020/03/3-mRNA-Seq-1024x512.png" alt="Welcome!" width="800" height="300"/>
  
<br />
<div align="left" width="50">

Gene expression analysis is most simply described as the study of the way genes are transcribed to synthesize functional gene products, functional RNA species or protein products. The study of gene regulation provides insights into normal cellular processes, such as differentiation, and abnormal or pathological processes.
  
In this project, I constructed a pipeline using a python programming language for analyzing Gene expression data obtained from the GEO database. The Gene Expression Omnibus (GEO) database is a part of the NCBI databases and holds a large number of gene expression datasets. 

Use the `Gene_Expression_Analysis_pipeline.ipynb` to get started.

List of libraries/datasets used for constructing the pipeline:

* [GEO dataset](https://www.ncbi.nlm.nih.gov/geo/)
* [pandas.py](https://pandas.pydata.org/)
* [SciPy.py](https://scipy.org/)
* [seaborn.py](https://seaborn.pydata.org/)
* [matplotlib.py](https://matplotlib.org/)
* [GEOparse](https://geoparse.readthedocs.io/en/latest/#)
* [bioinfokit](https://pypi.org/project/bioinfokit/)
* [Scikit-learn](https://scikit-learn.org/stable/install.html)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

In this pipeline i used transcriptomics data of the maturing erythroblast with an ID GSE22552. The dataset contain gene expression values of 16 samples. Erythoblasts grown in vitro were harvested at the CFU-E, Pro-E, Int-E and Late-E stages and FACS sorted cells based on expression of cell surface marker.
  
You can view the page of this dataset on the GEO website if you like at https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE22552.

To learn more about maturing erythoblast process (erythropoieses) from this article https://teachmephysiology.com/immune-system/haematology/erythropoeisis/
  

### Prerequisites

There are no prerequisites other than always reading about the data you are dealing with to help you structure the best-suited analysis pipeline.

### GEOparse python package
  
After installing and importing the GEOparse python package, load the dataset with the ID GSE22552. 
  You can use this line for that: gse = GEOparse.get_GEO(geo="GSE22552")

For your information, here are some nomenclature used by the GEO database:
  - GSE##### is a data series, which consists of a number of samples
  - GSM##### is a single data sample
  - GPL##### is a platform ID, which is the technology used to generate the data
So a given series (GSE) will have multiple samples (GSMs) and will have been generated using a given platform (GPL).
  

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This pipeline can be used for almost any gene expression data. Nevertheless, always take a deeper look into the preprocessing steps because some types of datasets may require additional or removal steps. However, you can use the pipeline to polish your analysis skills using python and learn new machine learning approaches.
  
The pipeline as well is perfect for junior data scientists and students of bioinformatics, enjoy it :) 

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap
  
Simplified analysis pipeline steps:

1. Load the dataset
2. Preprocess the data
3. PCA Analysis
4. Clustering 
5. GO Enrichment analysis
6. Conclusion

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Fatima Farhan - [@linkedin](https://www.linkedin.com/in/fatimafarhan112/) - fatimafarhan11295@gmail.com

Project Link: [https://github.com/Fatomk11295/Gene_expression_Analysis](https://github.com/Fatomk11295/Gene_expression_Analysis)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
