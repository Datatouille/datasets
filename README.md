# awesome-datasets
Curated datasets for machine learning tasks according to use cases adapted from a [now defunct article on Kaggle](https://www.pinterest.com/pin/541980136382090788/). Also check out this [repo of winning solutions](https://www.kaggle.com/sudalairajkumar/winning-solutions-of-kaggle-competitions).

For each type of analysis think about:
* What problem does it solve and for who?
* How is it being solved today?
* What are the data inputs and where do they come from?
* What are the outputs and how are they consumed? Online models, static or dynamic reports?
* Is it a revenue leakage (“saves us money”) or a revenue growth (“makes us money”) problem?

# Use Cases By Functions and Verticals
## Marketing
### Demand Forecasting
Forecast volumes of sales, inventory needed, etc.
* [Rossman](https://www.kaggle.com/c/rossmann-store-sales) - Supermarket sales forecasting
* [Online Product Sales](https://www.kaggle.com/c/online-sales/data) - self-help product sales forecasting
### Predicting Lifetime Value / Recency-Frequency Matrix
Identify the most lucrative and loyal segments of your customers
* [Lifetimes](https://github.com/CamDavidsonPilon/lifetimes) - Synthetic data and library for calculating CLV
* [CDNow](http://brucehardie.com/datasets/) - CDNow transaction records
### Churn / Up-sell 
Identify characteristics and timing of customer churns/upgrades in order to prevent/encourage them
* [KKBox's Churn Prediction Challenge](https://www.kaggle.com/c/kkbox-churn-prediction-challenge/data)
### Customer Segmentation
Identify main customer clusters and their characteristics
* [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)
* [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
* [Loyal Customer Prediction](https://www.kaggle.com/c/loyal-customer-prediction/data) - new customers from 11/11 event on Tmall
### Product Grouping / Category Tree
Group products together in the most reasonable category trees
* [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)
* [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)
### Cross-selling / Recommendation / Market Basket Analysis
Identify which products a customer is going to buy based on past purchases
#### Explicit Ratings
* [MovieLens](https://movielens.org/) - Movie recommendation dataset
* [Jester](http://eigentaste.berkeley.edu/) - Joke recommendation dataset
* [Book-Crossings](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) - Book recommendation dataset
* [HetRec](https://grouplens.org/datasets/hetrec-2011/) - Music recommendation dataset
#### Implicit Ratings
* [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis)
* [WikiLens](https://grouplens.org/datasets/wikilens/) - Wiki edits dataset
* [OpenStreetMap](https://planet.openstreetmap.org/planet/full-history/) - OpenStreetMap edits dataset
### Channel Attribution and Optimization
Allocate credits fairly to all ads channels and have portfolio for your ads spending
* [AnalyzeCore](https://analyzecore.com/2016/08/03/attribution-model-r-part-1/) - Synthetic data and attribution models
### Ad Optimization
Predict and price impressions, clicks, conversions or any performance metrics for ads
* [Avazu Click-Through Rate Prediction](https://www.kaggle.com/c/avazu-ctr-prediction) - Mobile ads click-through-rate prediction
* [Avito Demand Prediction Challenge](https://www.kaggle.com/c/avito-demand-prediction) - Predict demand for an online classified ad
### Ad Fraud
Detect ad click/install frauds
* [TalkingData AdTracking Fraud Detection Challenge](https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data) - Can you detect fraudulent click traffic for mobile app ads?
### Dynamic Pricing
Optimal price for growth, profit, customer retention, etc.
* [AWS Spot Pricing Market](https://www.kaggle.com/noqcks/aws-spot-pricing-market/home)
### Store Layout Optimization
Optimal store/website layout for growth, profit, customer retention, etc.
### Customer Feedback
Text classification to determine customer feedbacks/sentiment about your products
* [IMDb](https://www.imdb.com/interfaces/) - Movie reviews
* [Amazon Reviews](http://jmcauley.ucsd.edu/data/amazon/)
* [Yelp Open Dataset](https://www.yelp.com/dataset) - Yelp reviews
* [Wongnai Challenge](https://www.kaggle.com/c/wongnai-challenge-review-rating-prediction) - Restaurant reviews
* [OpinRank Review Dataset](https://archive.ics.uci.edu/ml/datasets/OpinRank+Review+Dataset) - TripAdvisor and Edmunds Reviews

## Customer Support
### Question Answering
Generate natural language answers based on given context and questions
* [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) - Stanford Question Answering Dataset
### Wait Time Prediction
Predict wait time based on customer history, time of day, call volumes, products owned, churn risk, LTV, etc.

## Human Resources
### Resume screening
Score candidates based on resumes and internal records
* [DonorsChoose.org Application Screening](https://www.kaggle.com/c/donorschoose-application-screening)
### Employee Churn
Predicts which employees are most likely to leave
* [SAS Employee Turnover](http://shell.cas.usf.edu/~pspector/sasdir/datasets.html) - Synthetic employee churn dataset
* [IBM HR Employee Attrition and Performance](https://www.ibm.com/communities/analytics/watson-analytics-blog/hr-employee-attrition/) - Synthetic employee churn dataset
* [Employee Attrition](https://www.kaggle.com/HRAnalyticRepository/employee-attrition-data) - Synthetic employee churn dataset

## Healthcare
### Medical Image Classification
Classify medical images according to conditions
* [Grand Challenges](http://www.grand-challenge.org/) - Collection of Biomedical Image Competitions
* [MURA](https://stanfordmlgroup.github.io/competitions/mura/) - Large Dataset for Abnormality Detection in Musculoskeletal Radiographs
* [ISIC](https://isic-archive.com/) - International Skin Imaging Collaboration
* [DermNet](http://www.dermnet.com/) - Skin Disease Atlas
* [TCIA](http://www.cancerimagingarchive.net/) - Cancer Imaging Archive
* [OASIS](http://www.oasis-brains.org/#data) - Longitudinal Neuroimaging Dataset
* [DDSM](http://marathon.csee.usf.edu/Mammography/Database.html) - Digital Database for Screening Mammography
* [Breast Histopathology Images](https://www.kaggle.com/paultimothymooney/breast-histopathology-images/)
* [NIH Chest X-rays](https://www.kaggle.com/nih-chest-xrays)
* [HERLEV](http://mde-lab.aegean.gr/downloads/) - Pap-smear Database
* [Stanford Tissue Microarray Database](https://tma.im/cgi-bin/home.pl)
* [CheXPert](https://stanfordmlgroup.github.io/competitions/chexpert/)
* [MIMIC-CXR](https://arxiv.org/abs/1901.07042)
### Readmission risk
Predict risk of re-admittance based on patient attributes, medical history, diagnose & treatment
* [Diabetes 130-US hospitals for years 1999-2008 Data Set](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)
### Patient Report Summary
Generate natural language reports based on tabular data
### Automated Triage
Classify patients according to their initial complaints
### Hospital Operations Management
Optimize/predict operating theatre & bed occupancy based on initial patient visits
* [Healthcare in Washington](https://www.doh.wa.gov/DataandStatisticalReports/HealthcareinWashington/HospitalandPatientData)
* [Mini Heritage Health Prize](https://github.com/jiunjiunma/heritage-health-prize) - Processed version of [Heritage Health Prize dataset](https://www.kaggle.com/c/hhp)
### Real-time Patient Monitoring
Activity monitoring of patients
* [OPPORTUNITY](https://archive.ics.uci.edu/ml/datasets/OPPORTUNITY+Activity+Recognition) - Dataset for Human Activity Recognition from Wearable, Object, and Ambient Sensors
* [PAMAP2](https://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring) - Physical Activity Monitoring Data Set 
### Survival Analysis
Predict survival rates of patients
* [Haberman's Survival Data Set](https://www.kaggle.com/gilsousa/habermans-survival-data-set) - Survival of patients who had undergone surgery for breast cancer
### Dosage Effectiveness
Analyse effects of admitting different types and dosage of medication for a disease

## Media
### News Summary
Generate short length descriptions of news articles.
* [NEWS SUMMARY](https://www.kaggle.com/sunnysai12345/news-summary)

## Insurance
### Claim Prediction
Predict timing and size of claims
* [TSA Claims Database](https://www.kaggle.com/terminal-security-agency/tsa-claims-database/home)
* [Allstate Claims Severity](https://www.kaggle.com/c/allstate-claims-severity)
### Claim Fraud
Outlier detection for insurance claim fraud
### Policy Prediction
Predict type of insurance
* [Insurance Company Benchmark (COIL 2000) Data Set](https://archive.ics.uci.edu/ml/datasets/Insurance+Company+Benchmark+%28COIL+2000%29)

## Finance
### Credit Scoring / Loan Approval / Debt Recovery
Predict which customers are going to default
* [Statlog (German Credit Data) Data Set](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
* [Statlog (Australian Credit Approval) Data Set](https://archive.ics.uci.edu/ml/datasets/Statlog+%28Australian+Credit+Approval%29)
* [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk)
* [A Fin tech fraud transaction classification](https://www.kaggle.com/c/a-fin-tech-fraud-transaction-classification) - default prediction with anonymized features
### Portfolio Optimization
Optimize portfolio of assets according to risks and returns
* [quantmod](https://www.quantmod.com/) - library for financial modeling in R; APIs for downloading fundamental and technical data
* [Stanford EE103](https://stanford.edu/class/ee103/portfolio.html) - Popular ETFs from 2006 to 2016
### Automated Trading
Trade financial assets using automated models
* [quantmod](https://www.quantmod.com/) - library for financial modeling in R; APIs for downloading fundamental and technical data
* [Get Rich or Die Modelin'](https://datatouille.org/competition/) - Bitcoin trading signals
### Fraud Detection
Identify fraudulent transactions and parties with outlier detection and network analysis
* [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) - Anonymized features
* [PaySim Synthetic Financial Datasets For Fraud Detection](https://www.kaggle.com/ntnu-testimon/paysim1)
* [Bitcoin Transactions](http://www.vo.elte.hu/bitcoin/downloads.htm)

## Manufacturing
### Quality Control
Detect malfunctioning pieces with computer vision
### Process Optimization
Find bottlenecks in manufacturing processes
* [Mercedes-Benz Greener Manufacturing](https://www.kaggle.com/c/mercedes-benz-greener-manufacturing)
### Warranty Analytics
Predict your products' rate and timing of failures
### Design
Design new products
* [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) - Labeled fashion images

## Agriculture, Geography and Environment
### Yield Forecasting
Forecast agricultural yields
* [Honey Production In The USA (1998-2012)](https://www.kaggle.com/jessicali9530/honey-production)
* [Agricuture Crops Production In india](https://www.kaggle.com/srinivas1/agricuture-crops-production-in-india)
### Satellite Image Classification and Extraction
* [Planet: Understanding the Amazon from Space](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space)
* [SpaceNet](https://spacenetchallenge.github.io/datasets/datasetHomePage.html) - Annotated satellite images of buildings and roads
* [Dstl Satellite Imagery Feature Detection](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection)
### Air Quality
* [Italy Air Quality Data Set](https://archive.ics.uci.edu/ml/datasets/Air+Quality)
### Wildlife Classification
Classify wild animals
* [North American Camera Trap Images (NACTI)](https://www.biorxiv.org/content/early/2018/06/14/346809) - images of trapped animals

## Real Estate
### Pricing
Predict real estate values based on their characteristics
* [Zillow’s Home Value Prediction (Zestimate)](https://www.kaggle.com/c/zillow-prize-1)

## Education
### Automated Essay Scoring
Score essays based on past pieces
* [The Hewlett Foundation: Automated Essay Scoring](https://www.kaggle.com/c/asap-aes)

## Utilities
### Distribution Network Optimization
Optimize distribution networks of electricity, water, etc.
* [Individual household electric power consumption Data Set](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)

# Others
* [Analyze Survey Data for Free](http://asdfree.com/)
