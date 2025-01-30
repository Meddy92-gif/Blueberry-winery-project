# BlueBerry Wine Project

## Data description
This dataset explores two distinct Portuguese "Vinho Verde" wine varieties—red and white. It provides a comprehensive collection of samples, offering a unique opportunity to delve into the characteristics that define wine quality.

The dataset comprises 1,599 samples of red wine and 4,898 samples of white wine (as in the chart below with the percental distribution), each containing detailed physiochemical information, such as acidity, sugar levels, and alcohol content. In addition to these metrics, the dataset includes quality evaluations performed by wine experts.

The experts graded each wine on a scale from 0 (very bad) to 10 (excellent), offering a valuable benchmark for understanding the factors that influence wine quality and consumer preference.
This dataset is perfect for data analysis, machine learning, and exploratory research into the science of winemaking. It provides insights into both the quantitative and subjective elements that contribute to the art of crafting exceptional wine.

![image](https://github.com/user-attachments/assets/910c2777-07a9-4694-b5dd-38b7d79f8e31)

## Steps of Data Analysis
The goal was to target high-quality wines across both wine types based on their chemical properties:
![image](https://github.com/user-attachments/assets/d469bef6-1598-42c2-a0cb-282a4bd29e92)

### Data cleaning: Detecting and Handling Missing or Duplicate Values
 I began by identifying missing or duplicate entries in the dataset and addressed them through removal or replacement to maintain data integrity.
 The provided dataset was clean enough, only to observe duplicated values and luckily no missing values were detected. 

### Defining the values + wine comparison: Analyzing and Categorizing Quality Ratings
I examined the wine quality ratings provided by experts. 
To make the data more interpretable, I categorized the ratings into three levels: 'Low', 'Medium', and 'High'. I then compared the characteristics of each category to uncover meaningful insights.
To gain insight into how the chemical properties influence wine quality, refer to the following [charts](https://github.com/Meddy92-gif/Project-2.git)

### Statistical methods: Investigating Patterns Influencing Wine Quality
I explored correlations between physiochemical properties and quality ratings to understand what makes a wine good.
I also identified and removed intercorrelations between variables to focus on the most impactful factors.
I analyzed the heatmap metrics to identify the key factors, specifically focusing on the correlation coefficients between variables. These coefficients range from -1 to +1 and can be interpreted as follows:

- **+1**: Indicates a strong positive linear relationship.  
- **0**: Reflects the absence of any linear relationship.  
- **-1**: Denotes a strong negative linear relationship.

For enhanced visual clarity, examine the heatmaps provided in this section.


### Build ML model and train with selected variables: Training Machine Learning Models
Using the significant variables I identified, I trained machine learning models to classify wine quality effectively and evaluated their performance.



 




