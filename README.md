# **Airbnb Seattle Data Analysis**

![Airbnb Seattle](https://www.digital.ink/wp-content/uploads/airbnb_logo_detail.jpg)  <!-- Add an image link relevant to the project -->

## **Project Overview**
This project explores the Airbnb Seattle dataset to analyze various factors that affect property prices and availability. Using Python libraries like `pandas`, `seaborn`, and `scikit-learn`, we dive into trends, correlations, and insights for Airbnb hosts, focusing on improving their listings’ performance.

## **Dataset**
The dataset used for this project is publicly available on Kaggle: [Airbnb Seattle Dataset](https://www.kaggle.com/datasets/airbnb/seattle).

### Key Files:
- `listings.csv`: Detailed information about Airbnb listings.
- `calendar.csv`: Daily availability and price data for listings.
- `reviews.csv`: Review data associated with listings.

## **Business Questions Addressed**
This project seeks to answer several business-critical questions:
1. **What are the most important factors influencing Airbnb listing prices?**
2. **How do seasonal trends affect booking demand and pricing?**
3. **What impact do reviews and ratings have on a listing’s success?**

## **Installation**

To run the code, follow these instructions:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/airbnb-seattle-analysis.git
   cd airbnb-seattle-analysis

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook airbnb_seattle_analysis.ipynb.

## **Libraries and Tools**
The project uses the following libraries:

1. **Pandas**: Data manipulation and cleaning.
2. **NumPy**: Numeric computations.
3. **Matplotlib & Seaborn**: Data visualization.
4. **Scikit-learn**: Machine learning and data modeling.
5. **KaggleHub**: Dataset download integration.

## **Project Workflow**
1. **Data Download**:
The dataset is downloaded using KaggleHub from Kaggle’s Airbnb Seattle dataset.

2.**Data Cleaning**:
- Irrelevant columns with high missing data were dropped (e.g., license, square_feet).
- Missing values in essential columns (e.g., reviews_per_month) were filled with appropriate values.
- The price column was cleaned by removing special characters and converting it into a numeric format.
  
3.**Exploratory Data Analysis (EDA)**:

***Price distribution***: Insights into how prices vary across listings.
***Correlation analysis***: Investigated the relationship between key listing features (e.g., room type, location) and price.
***Booking trends***: Analyzed seasonal demand patterns in Seattle.

4.**Modelling**:
- A linear regression model was built to predict listing prices using features such as the number of bedrooms, review scores, and room type.
- The model’s performance was evaluated using mean squared error (MSE).

**Key Insights**
- **Room type and location**: Private rooms and entire homes tend to fetch higher prices.
- **Seasonal trends**: Booking demand surges during summer months, and prices rise accordingly.
- **Reviews and ratings**: Highly rated listings with more reviews tend to command higher prices and better booking success.

**Results**
The analysis highlights key factors for Airbnb hosts in Seattle to consider, such as room type, location, and review management, to optimize their listing prices and bookings.

**Example Visualizations**:

1.**Price Distribution**
2.**Correlation Heatmap**

**File Descriptions**
- airbnb_seattle_analysis.ipynb: Jupyter Notebook containing the analysis and model.
- README.md: Overview of the project, instructions, and insights.

**Acknowledgments**
- Dataset: Airbnb Seattle via Kaggle.
- Python libraries: Special thanks to the open-source libraries used in this analysis.
