# awesome-datasets
Curated datasets for machine learning tasks according to use cases adapted from a [now defunct article on Kaggle](https://www.pinterest.com/pin/541980136382090788/).

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
### Training recommendation
Recommend specific trainings based of performance review data

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
### Real-time Patient Monitoring
Activity monitoring of patients
* [PAMAP2](https://archive.ics.uci.edu/ml/datasets/PAMAP2+Physical+Activity+Monitoring) - Physical Activity Monitoring Data Set 
### Physician Attribution
Attribute credits to physicians fairly
### Survival Analysis
Predict survival rates of patients
### Dosage Effectiveness
Analyse effects of admitting different types and dosage of medication for a disease

## Insurance
### Claim Prediction
Predict timing and size of claims
### Claim Fraud
Outlier detection for insurance claim fraud
### Policy Price Sensitivity
Predict consumer reaction to policy price movement

## Finance
### Credit Scoring / Loan Approval
Predict which customers are going to default
* [Statlog (German Credit Data) Data Set](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))
* [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk)
### Portfolio Optimization
Optimize portfolio of assets according to risks and returns
### Automated Trading
Trade financial assets using automated models
* [Get Rich or Die Modelin'](https://datatouille.org/competition/) - Bitcoin trading signals
### Fraud Detection
Identify fraudulent transactions and other outliers
### Debt Recovery
Predict the probablity a liability can be recovered given the characteristics of the borrower and the loan
### Anti-Money Laundering
Using machine learning and fuzzy matching to detect transactions that contradict AML legislation

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

## Geography
### Satellite Image Classification
* [SpaceNet](https://spacenetchallenge.github.io/datasets/datasetHomePage.html) - Annotated satellite images of buildings, roads and more
* [Planet: Understanding the Amazon from Space](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space)
* [
Dstl Satellite Imagery Feature Detection](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection)

## Real Estate
### Pricing
Predict real estate values based on their characteristics
* [Zillow’s Home Value Prediction (Zestimate)](https://www.kaggle.com/c/zillow-prize-1)

## Environment
### Wildlife Classification
Classify wild animals
* [North American Camera Trap Images (NACTI)](https://www.biorxiv.org/content/early/2018/06/14/346809) - images of trapped animals

## Education
### Automated Essay Scoring
Score essays based on past pieces

## Utilities
### Distribution Network Optimization
Optimize distribution networks of electricity, water, etc.
* [Individual household electric power consumption Data Set](https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption)
