

# NYC Taxi Data Analytics

This project analyzes trip records from NYC taxi services including Yellow, Green, and FHVHV (For-Hire Vehicle High Volume). The goal is to compare different taxi types based on trip distance, duration, pickup/drop time, and pricing for finding efficient taxi for the customer.

---

## Dataset Used

- **Yellow Taxi**
- **Green Taxi**
- **FHVHV Taxi**
  
**Link:-** https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page


Each dataset contains:

- `dropoff_datetime` : drop time
- `pickup_datetime` : pickup time
- `trip_distance`: Total trip distance in miles
- `trip_duration_minutes`: Trip duration (derived from timestamps)
- `total_amount`: Total fare amount

---

##  Objectives

- Clean and filter data for meaningful analysis
- find common columns across all datasets
- Merge datasets based on common columns
- Calculate average amount per mile
- Calculate average speed mile/hour
- Visualize comparison between taxi types

---

## Tools Used

- Python 
- Pandas
- Matplotlib 

---

##  Key Visualizations

- Bar chart showing **average fare per mile** by taxi type
- Bar chart showing **average speed mile/hour** by taxi type

---

##Run the code

jupyter notebook- jan.py

---
