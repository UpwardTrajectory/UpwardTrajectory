### Hi there 👋

My name is David Kaspar and I'm a creative data scientist/engineer and design thinker with experience in python, statistical analysis, machine learning, and natural language processing. With a background in math education and entrepreneurship, I build and connect data pipelines, creating robust & performant tools while answering business-centric questions. I transform numbers, data, and abstract ideas into something that makes sense to people and organizations so that they can make informed, data-driven decisions.


#### My Time as a Data Science Consultant
Due to signing an NDA, I cannot discuss anything here in great detail, but I can share some high-level ideas and some of the tools I used to collaborate with both our internal team and our external clients (technical & non-technical) to solve a wide variety of challenging, data-related problems.
* Source-control: Git, GitHub, Atlassian BitBucket
* Python Machine Learning Libraries: Pandas, NumPy, Scikit-Learn, PyTorch, Tensorflow, SpaCy, NLTK, Facebook Prophet
* Visualization: Tableau, Power BI, Matplotlib, Seaborn, Plot.ly
* Cloud Computing: 
    - Amazon Web Services (AWS, S3, EC2, SageMaker)
    - Google Cloud Platform (GCP, App Engine, Compute Engine, Cloud Functions, Cloud Storage, BigQuery, Cloud AI, Cloud IAM)
    - IBM Watson (Natural Language Understanding, Natural Language Classifier, Speech to Text)

## ⚡ Highlighted Projects

#### [Tracking Customer Engagement in 3D Space](https://i.imgur.com/2RaL6jR.mp4) (on a team of 4 ppl)

Understanding how customers interact with a physical space is often difficult (and expensive) to measure accurately. If done wrong, it can easily be seen as an invasion of privacy. However, if done well, it can give a lot of insights into how a company might want to do things differently in order to optimize their customers' experience or simply to improve their own bottom line. This project focused on assessing anonymous movement trends & group behaviors across a multi-story space covering an area that exceeds 500,000 sq ft with 45 distinct zones. Extracting trends based on visit duration, day of the week, time of the year, and then comparing with historical data. All findings were presented in a Tableau dashboard that was updated once per day.
* Automatically processed tens of millions of records per night using cloud computing & scheduling
* Gather raw data -> Google Big Query (raw) -> Modeling & Analysis (Python) -> Google Big Query (processed) -> Tableau Front-end
* Source control & collaboration using GitHub 
* My individual contributions & responsibilites included:
  - Model iteration improvements: improve zone labeling algorithm for labeling an interaction in one of 45 zones from a random guess, 2.22% accuracy, to over 60% accuracy
  - Improve performance & legibility of inherited legacy code
  - Automate cloud scheduling to read & write from Google BigQuery daily, as well as backfill data for previous months

#### [User Recommendations Engine](https://i.imgur.com/2RaL6jR.mp4) (on a team of 4 ppl)

Create serendipitous recommendations for a user-base in the hundreds of thousands to recommend opportunities for personal growth. Leveraging Tensorflow & AWS SageMaker, build a recommendation system that can compare implicit user-profiles & opportunity-profiles, records of past interactions, and explicit feedback from the users to deliver relevant options that delight the user & foster greater adoption and interaction with the smartphone app.
* Gather raw data -> AWS S3 Data Lake -> AWS SageMaker -> AWS S3 Data Lake -> Smartphone app -> Cycle feedback back into the AWS S3 Data Lake
* Source control & collaboration using Atlassian BitBucket
* My individual contributions & responsibilities included:
  - Onboarding our team to AWS SageMaker & configuring the environment
  - Connecting to the S3 Data Lake to read inputs
  - Validating & cleaning input data
  - Integrating the "User Profile" into the Tensorflow model to address the "cold-start problem" as well as improve ongoing recommendations
  - Validating model outputs to ensure useful results were being served to the smartphone app
  - Sending outputs back to the S3 Data Lake
  
#### [Meander Maker](https://github.com/UpwardTrajectory/meander-maker) (solo developer)

Google Maps is great for finding individual places to go, but if you want to find a cluster of multiple related places, it can take a lot of work. There's a lot of scrolling, saving things for later, interacting with the search bar over and over, and eventually just eyeballing what you think might work, and hoping for the best. This location discovery tool addresses that frustration, and is great for things like:
 * Planning an urban themed walk
 * Efficiently visiting the nearest group of shoe stores
 * Creating an itinerary for winetasting through a cluster of walkable tasting rooms
 * Discovering a neighborhood in a foriegn city with a high density of something you like (museums, gluten-free restaurants, etc)
 * Of course, there's always the good old-fashioned pub crawl
  
Meander Maker leverages user-input to customize the "best" cluster based on how much the end user values:
* High ratings from Google Maps
* Overall quantity of stops within the cluster
* Short initial distance from the user's starting position
* Short transit distance within the stops of the cluster (after initial travel to stop #1 is completed)

## 💬 Blog Articles
<!--
**Natural Language Processing**
- [Leveraging AI+ Written/Spoken Word for Sales Enablement](http://blog.pandata.co/leveraging-ai-written-spoken-word-for-sales-enablement/)
- [Joy to the World: Holid.AI Card Generator Volume III](http://blog.pandata.co/joy-to-the-world-holid-ai-greetings-volume-iii/)


**Mathematics**
-->
- [Determinining Underlying Growth Models Mathematically](https://dev.to/upwardtrajectory/something-is-growing-and-it-s-growing-very-fast-but-how-fast-1li6)
- [Engineering Location Features with Haversine's Formula for Prediction Modeling](https://dev.to/upwardtrajectory/engineering-location-features-with-haversine-s-formula-for-prediction-modeling-23n2)

## 📫 Connect with Me
<a href="https://www.linkedin.com/in/davidkasparworks/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://dev.to/upwardtrajectory" target="_blank"><img alt="dev.to" src="https://img.shields.io/badge/dev blog-%2312100E.svg?&style=for-the-badge&logoColor=white" /></a> <a href="mailto:datakaspar@gmail.com" target="_blank"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?&style=for-the-badge&logo=Gmail&logoColor=white" /></a> 

## 🔭 Currently Working On

- Clustering of unlabeled text documents with Natural Language Understanding (NLU) techniques
- Pros & Cons between cloud-computing services (AWS, GCP, Azure, IBM Watson, etc)
- Contributing to Open-Source machine learning libraries
- Drafting a "Performant Pandas" blog. A collection of tips to improve performance & readability for many common Pandas DataFrame operations


<!--
**UpwardTrajectory/UpwardTrajectory** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
