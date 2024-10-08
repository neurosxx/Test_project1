Author: Jesus Rafael Herrera

# Business Understanding
In this project, we will be looking at an aircraft dataset to provide  recommendations of which aircraft are the lowest risk for interested stakeholder.

Commerical and private enterprises is a signifcant, global market.  According to Statista, global airline industry was 762.8 billion in 2023. While that is a a staggering number, there is also a signifcant overhead in obtaining private and commercial usage of aircrafts. Stakeholders of corporations require research on factors of aircraft safety to prioritize protection of products, employees, and efficiency.  As Pfizer is interested in delivering medical cargo, the following project will focus on recommendations on safest aircrafts

# Data Understanding 
In order to obtain more information relevant to aircrafts, a dataset from https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses will be utilized.  

  * The National Transportation Safety Board [NTSB] provides information from 1962 and more recent dates about civil aviation accident and chosen incidents within the United States, territories and possessions, and in international waters. 

 * With use of the above dataset, we are able to determine factors of safety and their value to investors. 

## Data Preparation 
 * Project Description:
     * This project prepares data from NTSB Aviation Accident and will be used to determine safety standard for potential investors.
  
  Data Overview: 
  - **Source:** 'https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v3/master/data/Aviation_Data.csv'
- **Format:** CSV, JSON
- **Size:** 138 rows, 20 columns
- **Columns:**
  - `Event.Id`: Unique identifier
  - `Make`: Unique model of aircraft
  - `Total.Fatal.Injuries`: Total amount of fatal injuries in each aircraft event
  - `Number.of.Engines`: Amount of engines an aircraft has
 
   Data Preparation Steps:
  **Data Cleaning**
  - Removed rows with missing values in all columns
 
  **Data Transformation**
  - Encoded values to be lower cased to help benefit analysis
  - Encoded values to obtain only professionally built aircrafts

  ## Libraries and Tools
  - Python 3.8
  - pandas 1.2.3
  - numpy 1.19.5

# Exploratory Data Analysis 
![image](https://github.com/user-attachments/assets/0b24dd31-d100-4723-ba7d-d98dff393cee)

![image](https://github.com/user-attachments/assets/ddeb0b81-3898-4d20-be2b-5821b089c654)



# Conclusion 
In summary, the three business recommendations for investors include:

   * With regards to number of engines, the data indicates that the following engine types: Turbo fan, Turbo jet, Turbo Prop, and Turbo shaft are associated with the least amount of Fatal injuries.  Based on the Number of Engines graph, turbo jet engine would be the most recommended for safest aircraft. 

* Discussing number of engines, the safest engine would include 2, 3, or 4 engines. Aircrafts that do not have only one engine show significantly decreased fatal injuries. Multi-engine aircrafts have backup engines if engine failure occurs, which is a significant factor of increased safety. 

* Lastly, based on the data, Cessna, Piper, Beech, and Boeing are associated with the highest fatal injuries, but this may be due to common frequency of these planes being more generally accepted to use. 

## Limitations
* Obtained data set did not have full amount of data to provide an improved analysis.  With a full data set, more concise and accurate analysis would lead to better standards of aircraft safety. 

## Recommendations 
* Purchasing an airplane with an engine type of "Turbo Jet" or "Turbo Shaft" are priority for safety.  Also, multi engine airplanes like Dornier or Dassault/sud would benefit shipment of your cargo and prioritize safety of your employees. 

## Next Steps 
* Include more complete data sets to obtain improved accuracy on safety standards. 
* Look into specific prices of multi-engine models for future investors
