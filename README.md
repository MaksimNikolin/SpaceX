_**date of creation: Janiary, 2024**_

Introduction:
This project was implemented jointly with a team of developers from IBM Skills Networks within the framework of professional certification from IBM.

Problem:
SpaceX advertises Falcon 9 rocket launches on its website at a cost of $62 million, while other suppliers cost more than $165 million each, most of the savings are achieved by SpaceX being able to reuse the first stage. Therefore, if we can determine if the first stage will land, we will be able to determine the launch cost. This information can be used if an alternative company wants to bid against SpaceX for a rocket launch.

Content:
 **1. Spacex_web_scrapped** - In this block, parsing was performed from the site wikipedia.org necessary information such as: _'Version_Booster', 'Launch_Site', 'Payload_mass', 'Orbit', 'Customer', 'Launchoutcome' and others_. The method of parsing used: _Beautifulsoup_. The result was saved to a file: _spacex_web_scrapped_.  
 **2. Dataset_part_1** - The dataset was transformed to a more readable form. The result was saved to a file: _dataset_part_1.xls_.  
 **3. Dataset_part_2** - Similarly, the dataset was transformed to a more readable form. The result was saved to a file: _dataset_part_2.xls_.  
 **4. EDA_SQL_requests** - In this block, exploratory data analysis was carried out using various SQL queries.  
 **5. EDA_data_vizualisation** - There was also an exploratory analysis of the data, or rather the dependence of the interaction of some parameters on each other. The block uses visualization methods using graphs. The result was saved to a file: _dataset_part_3.csv_.  
- **6. Launch_site_locations** - Visualization of Launch Sites, the success of first-stage landings, as well as the distance from nearby infrastructure on the map using _the Folium_ library.  
 **7. Dashboard** - A dashboard was created to demonstrate the success rate of landing the first stage at various Launch Sites, as well as which versions of boosters with what Payload were used at which Sites.  
 **8. ML_models** - Finally were considered different machine learning methods, such as: _logistic regression, SVM, decision tree, KNN_ to predict the success of the landing of the first stage, as well as the search for optimal hyperparameters. The best model for this task turned out to be _decision tree_ with accuracy_score near _0.9_.  
