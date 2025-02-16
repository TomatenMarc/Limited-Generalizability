# :see_no_evil: Limited Generalizability in Argument Mining: State-Of-The-Art Models Learn Datasets, Not Arguments :speech_balloon: :hammer:

![image](https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252)
![image](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![image](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![image](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![image](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![image](https://img.shields.io/badge/-HuggingFace-FDEE21?style=for-the-badge&logo=HuggingFace&logoColor=black)
![image](https://img.shields.io/badge/ChatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)

This repository contains code and data for the paper *"Limited Generalizability in Argument Mining: State-Of-The-Art Models Learn Datasets, Not 
Arguments"*.

**Table of Contents:**

- [Repository Layout](#repository-layout)
- [Licensing](#licensing)
- [Contact](#contact)

## Repository Layout

1. [notebooks](./notebooks)
   1. [dataset_assets.ipynb](./notebooks/dataset_assets.ipynb): Pulling and integrating the ground truth data (*).
   2. [preprocessing_and_sampling.ipynb](./notebooks/preprocessing_and_sampling.ipynb): For pre-processing, sampling, examples and creating data distributions.
   3. [classification.ipynb](./notebooks/classification.ipynb): To execute all experiments.
   4. [results.ipynb](./notebooks/results.ipynb): For generating the results.
   5. [generate_tables.ipynb](./notebooks/generate_tables.ipynb): For generating the tables.
2. [output](./output)
   1. [classification](./output/classification): Results of each experiment performed.
      1. [train-one-one-test-on-another](./output/classification/train-on-one-test-on-another): The results for research question Q2.
      2. [to-what-transformers-pay-attention](./output/classification/to-what-transformers-pay-attention): The results for research question Q3.
      3. [leave-one-out](./output/classification/leave-one-out): Results of the additional experiment as mentioned in the appendix.
   2. [images](./output/images): Final visualizations of the results.
   3. [statistics](./output/statistics): Numerical description of dataset features. 
3. [datasets.csv](./datasets.csv): Details about all 52 datasets considered.

> [!NOTE]  
> (*) For `TACO` and `UKP`, you need to create an `assets` folder to store the requested data. Follow the instructions in this notebook to place 
> the folder and files correctly.

## Licensing

<p>
  <a property="dct:title" rel="cc:attributionURL" href="https://github.com/TomatenMarc/Limited-Generalizability">Limited-Generalizability</a> by 
  <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="mailto:marc.feger@hhu.de">Marc Feger</a> is licensed under 
  <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0</a>
  <div style="display:block;">
    <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1">
    <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1">
    <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1">
    <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1">
  </div>
</p>

## Contact

If you have any questions, don't hesitate to reach out to  [marc.feger@hhu.de](mailto:marc.feger@hhu.de), [katarina.boland@hhu.de](mailto:katarina.boland@hhu.de) or [stefan.dietze@gesis.org](mailto:stefan.dietze@gesis.org).