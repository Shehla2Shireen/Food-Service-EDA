# Food-Service-EDA

This project performs an Exploratory Data Analysis (EDA) on food service data to analyze various factors affecting food waste, meal service efficiency, and operational trends. The dataset includes variables like meals served, staff experience, temperature, humidity, and waste category.

Project Overview
Objective: Analyze food service data and provide insights into how various factors like staff experience, temperature, and meal volume affect food waste and operational efficiency.

Variables:

meals_served: Number of meals served per day.

kitchen_staff: Number of staff working.

temperature_C: Temperature in Celsius.

humidity_percent: Humidity percentage in the kitchen.

special_event: Indicator of whether the day is a special event or not.

past_waste_kg: Amount of food waste produced (in kilograms).

staff_experience: Experience level of the kitchen staff (e.g., beginner, intermediate, expert, pro).

waste_category: Category of food waste (e.g., meat, dairy, vegetables).

Key Insights
Food Waste Trends: We found significant correlations between certain staff levels, temperature, and food waste. Specifically, waste tends to increase with extreme temperatures, suggesting issues with storage or consumption at these extremes.

Optimal Staffing: Kitchen staff efficiency peaks with 6-16 staff members, reducing food waste and improving operational efficiency.

Waste Categories: Meat is the most wasted category, with significant variation in waste levels. This suggests a focus on better managing meat-related waste could lead to overall waste reduction.

Staff Experience: While staff experience did not show a clear trend in reducing food waste, the more experienced staff generally exhibited less variation in food waste, indicating a more consistent performance.

Installation
Clone the repository to your local machine:

bash
Copy
Edit
git clone https://github.com/yourusername/food-service-eda.git
Navigate to the project directory:

bash
Copy
Edit
cd food-service-eda
Create and activate a virtual environment:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the main script to begin the exploratory data analysis:

bash
Copy
Edit
python eda_script.py
Visualizations: The script will generate several plots showing trends and correlations, including:

Meals Served vs. Food Waste

Staff Experience vs. Food Waste

Temperature vs. Food Waste

Meals Served and Waste Category Breakdown

Time-Based Analysis: The script also performs time-based analysis to explore how daily trends in meal volume and food waste evolve over time, allowing you to identify any seasonal or event-based patterns.

Project Structure
data/: Contains the raw and processed data.

notebooks/: Contains Python scripts for data cleaning, analysis, and visualization.

requirements.txt: Lists the Python dependencies.


Dependencies
The project requires the following Python libraries:

pandas — for data manipulation and analysis

numpy — for numerical computations

matplotlib — for data visualization

seaborn — for statistical data visualization

statsmodels — for statistical modeling

You can install all the dependencies with:

bash
Copy
Edit
pip install -r requirements.txt
