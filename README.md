# Ford GoBike System Data Exploration
**Author: Pius Imwene**

## Dataset Description
This project explores the **Ford GoBike System Dataset**, provided by Udacity.  
The original dataset contained **183,412 rows** and **16 features**.

During the data wrangling process, several new features were engineered to support deeper analysis, including:

- `participant_age`
- `start_day`
- `end_day`
- `start_month`
- `end_month`
- `duration_hours`

Additional cleaning steps included:
- Removing missing values  
- Correcting unrealistic birth years (e.g., replacing **1878** with **1978**)  
- Addressing inconsistencies in datatype and formatting  

After wrangling, the cleaned dataset contained:

- **174,952 participants**  
- **22 features**, including **13 numeric variables**

To explore the data, three types of visualizations were used:
- **Univariate** (distribution of single variables)  
- **Bivariate** (relationships between two variables)  
- **Multivariate** (relationships involving more than two variables)

---

## Summary of Findings

### **1. Age vs Duration**
There is a **weak positive relationship** between participant age and the duration of bike trips.  
This suggests that **older participants tend to spend slightly more time completing a trip** compared to younger participants.

### **2. Gender Differences**
The findings show:
- **Males generally complete trips faster** than females  
- Females tend to take more time on average to complete the same distance

### **3. Bike Sharing vs Non-Sharing**
There was **no significant difference** between:
- Participants who shared bikes for their trips, and  
- Participants who did not share bikes  

Both groups exhibited similar trip durations.

### **4. User Types (Customer vs Subscriber)**
There was **no major difference** in trip durations between customer types:
- **Subscribers**
- **Customers**

### **5. Age Groups**
Participants aged **25 to 40** completed trips **faster** than those aged **50+**.  
This suggests younger riders tend to ride more efficiently or at a quicker pace.

---

## Key Insights for Presentation

For the presentation, the focus will be on the following variables:

- **Trip duration**
- **User type**
- **Gender**
- **Age**

The visualizations include:
- **Scatterplots** to analyze relationships between user type, gender, and trip duration  
- **Box plots** to compare trip duration across groups  
- **Histograms** to examine the distribution of trip duration (using log transformation for better visibility)

---

