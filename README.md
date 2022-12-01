# Multilingual_Toxic_Comment_Classification
        Yashkumar Parikh
        Lakehead University - Computer Science
        Email: parikhy@lakeheadu.ca
        
 ## Table of Contents

1. [Project Description](#project-description)
2. [This project includes the following things](#this-project-includes-the-following-things)
3. [Install](#install)
4. [Dataset](#dataset)
5. [Code Editor](#code-editor)
6. [Contributors](#contributors)
7. [Contact Details](#contact-details)

## Project Description

Social media sites are gaining popularity day by day. They are best for communication, business, entertainment, and many other things. After more than a decade, social media have become very influential. On the flip side, fake news, hate speech, and online trolls are the biggest concerns because of social media. So, a solution to curb this issue is needed, especially in regional languages. Many social media platforms support regional languages. This paper will provide a machine learning-based solution to this problem. The focus of this paper is to classify comments written in regional languages. Firstly, a dataset has been created in Gujarati, Hindi, English, Marathi, and Punjabi languages. After that, different machine learning and deep learning models are applied to the multilingual dataset. At last, a comparison of all model performances was made.

## This project includes the following things
1. Dataset
2. .ipynb files for different models
3. Technical Report
4. Research Report

## Install

To run on local follow the given steps:

1. git clone repo_link.
2. Upload the project folder (Data and Code files) to google drive
3. Open ipynb file and change ‘dir_path’ variable to your local path
4. Execute the code cells

## Dataset

I have gathered data from various social media platforms in Indic languages like Gujarati, Hindi, Marathi, Punjabi, and English. The shape of the data is (14995, 2). It has two columns comment_text and toxic. The comment_text column contains actual text, and the toxic column contains '1' for toxic and '0' for non-toxic comments. The pre-processing step removes URLs, hashtags, mentions, punctuations, and extra white spaces from the comments. Plus, removed rows with empty or null values. 
  
## Code Editor

Google Colab

Colaboratory, sometimes called Colab, is a Google Research product. Colab is particularly well suited to machine learning, data analysis, and education. It enables anyone to create and execute arbitrary Python code through the browser. Technically speaking, Colab is a hosted Jupyter notebook service that offers free access to computer resources, including GPUs, and requires no setup.
  
## Contributors

[Yash Parikh](https://github.com/yparikh8036)  ![twitter](https://img.shields.io/twitter/follow/parikh_y?style=social)

## Contact Details

Anyone has any questions or wants to contribute to the project then write an email at parikhy@lakeheadu.ca.

## Licence

Copyright 2021 Province of Ontario, Canada

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at 

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
