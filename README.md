# IPL Data Analysis with Apache Spark<br />

# # Project Overview<br />
*This project performs an in-depth analysis of IPL cricket match data using Apache Spark. 
It covers tasks like reading data, filtering, transformations, aggregations, and 
generating various statistics related to batting and bowling performances.*

##  Project Structure<br />
The project is structured as follows:
1.Source Code: The main code is contained in the obj object within the pack33 package.
2.Data Source: The data is read from a CSV file containing detailed information about IPL match deliveries.

##  Key Features<br />
### 1.Data Loading and Exploration:
The project begins by reading the IPL dataset and performing basic explorations like displaying the schema and distinct match IDs.
### 2.Innings-wise Data Segregation:
Separates data for the first and second innings for detailed analysis.
### 3.Batting and Bowling Scorecards:
Batting Analysis: Includes aggregating total runs, counting boundaries (4s and 6s), and calculating strike rates for each batsman.
Bowling Analysis: Includes total runs conceded, balls bowled, wickets taken, and calculating economy rates.
### 4.Advanced Aggregations:
Calculation of bowling maidens by considering only valid deliveries and runs.
### 5.Data Transformation and Window Functions:
Utilizes window functions to determine the batting order and other rank-based calculations.

    
## Usage<br />
   ##  Prerequisites:
   - Apache Spark
   - Scala
   - A suitable IDE or text editor for Scala development
  ##   Running the Project:
   - Clone the repository and navigate to the project directory.
   - Set up your environment and make sure all dependencies are installed.
   - Run the main object obj to execute the code.
   ##  Data File:
   Ensure the data file "deliveries.csv" is available at the specified path.

## final scorecard :<br />
 ### 1st innings:<br />
batting:<br />
*See the **[final 1st batting scorecard](https://github.com/Harshavardhan71/ipl-scorecard/blob/main/screenshots/1st%20innings/final%201st%20batting%20scorecard.jpg)***  
 bowling:<br />
*See the **[final 1st bowling scorecard](https://github.com/Harshavardhan71/ipl-scorecard/blob/main/screenshots/1st%20innings/final%201st%20bowling%20stats.jpg)***    
			
### 2nd innings:
batting:<br />
*See the **[final 2nd batting scorecard](https://github.com/Harshavardhan71/ipl-scorecard/blob/main/screenshots/2nd%20innings/final%202nd%20batting%20scorecard.jpg)***  
bowling:<br />
*See the **[final 2nd bowling scorecard](https://github.com/Harshavardhan71/ipl-scorecard/blob/main/screenshots/2nd%20innings/final%202nd%20bowling%20stats.jpg)***  
 
