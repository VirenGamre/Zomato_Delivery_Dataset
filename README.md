
# **Zomato Delivery Report Project**  

## **Overview**  
This project demonstrates the end-to-end workflow of a data analytics pipeline. The goal was to clean and analyze raw data, derive actionable insights, and create an interactive dashboard to visualize delivery-related metrics for Zomato.  

## **Pipeline**  
1. **Data Cleaning**:  
   - Removed duplicate records.  
   - Filled null values using statistical methods.  
   - Addressed outliers for more accurate analysis.  
   - Renamed columns for better clarity and understanding.  

2. **Data Transformation & Storage**:  
   - Cleaned data was imported into **MySQL**.  
   - Performed joins and transformations in MySQL to enrich the dataset.  

3. **Data Visualization**:  
   - Connected MySQL to **Power BI** to create an interactive and visually appealing dashboard.  
   - The dashboard showcases delivery times, weather impacts, vehicle contributions, and city-wise metrics.

## **Tools Used**  
- **Python**: For data cleaning and preprocessing.  
- **MySQL**: For storing and transforming the cleaned data.  
- **Power BI**: For visualization and dashboard creation.  

## **Key Metrics & Insights**  
- **Average Delivery Time**: 30 minutes.  
- **Average Customer Ratings**: 4.64.  
- **Registered Drivers**: 179.  
- **City-Wise Delivery Times**: Ranged from 33.67 minutes in Delhi to 20.6 minutes in Kolkata.  
- **Vehicle Type Contribution**:  
  - Motorcycles: 58.5%  
  - Scooters: 34%  
  - Electric Scooters: 7.5%  
- **Weather Impact**: Insights on how different weather conditions like fog, sandstorms, and wind affect delivery times.  

## **Dashboard Overview**  
The dashboard includes the following visuals:  
1. **Weather Conditions Impact**: A bar chart displaying the frequency of weather conditions.  
2. **Daily Order Count**: A line chart visualizing order trends.  
3. **Delivery Time in Cities**: A bar chart showing average delivery times across cities.  
4. **Vehicle Type Analysis**: A pie chart showing the contribution of each vehicle type to deliveries.  
5. **Vehicle Counts**: A bar chart indicating the number of each vehicle type used for deliveries.  


## **Conclusion**  
This project showcases the importance of a robust data analytics pipeline for extracting insights and visualizing data effectively. By integrating tools like Python, MySQL, and Power BI, we were able to turn raw data into meaningful business intelligence.  

