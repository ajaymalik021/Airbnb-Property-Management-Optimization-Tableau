# Airbnb Property Management Optimization  

This project focuses on optimizing Airbnb’s rental strategies by analyzing property data to provide actionable insights for both Airbnb and its hosts. Using **Tableau**, this project explores key metrics like neighborhood popularity, property type demand, customer satisfaction, seasonal trends, and the impact of amenities on pricing.

---

## 📋 **Objectives**

### **1. Neighborhood Popularity and Pricing**  
- Identify neighborhoods with the highest number of listings.  
- Analyze how pricing varies across different locations.  

### **2. Property Type Distribution**  
- Investigate the types of properties (entire homes, private rooms, shared rooms).  
- Determine which property types are most in demand.  

### **3. Customer Satisfaction and Ratings**  
- Explore the relationship between listing prices and customer review ratings.  
- Identify key factors contributing to higher customer satisfaction.  

### **4. Seasonality and Booking Trends**  
- Detect seasonal trends in Airbnb listings and bookings.  
- Understand how bookings fluctuate throughout the year.  

### **5. Host and Listing Analysis**  
- Determine hosts with the highest number of listings.  
- Analyze pricing strategies of top hosts.  

### **6. Impact of Amenities on Pricing**  
- Examine how the presence of certain amenities affects listing prices.  

---

## 🛠 **Tools and Techniques**  
- **Tools Used:** Tableau, Microsoft Excel  
- **Techniques:**  
  - Data Cleaning and Preparation  
  - Exploratory Data Analysis (EDA)  
  - Data Visualization with Tableau  
  - Advanced Calculations and Metrics  

---

## 📊 **Key Tableau Calculations**

### **1. Popularity by Neighborhood**  
```tableau
COUNT([Listing_ID]) BY [Neighborhood]
