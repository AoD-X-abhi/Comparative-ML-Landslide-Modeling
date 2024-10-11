# Comparative-ML-Landslide-Modeling
<big><big><b>Comparative ML Landslide Modeling</b></big></big><br>
This project aims to predict landslides by utilizing machine learning models and real-world geographical data. The dataset includes critical features such as temperature, moisture, rainfall, pressure, displacement, and more, which are known to influence landslide occurrences. To enhance prediction accuracy, models like Random Forest, XGBoost, Support Vector Machine (SVM), and Neural Networks were employed, with extensive preprocessing applied to clean and normalize the data.
<br>
In this project, we compare the performance of these models using accuracy and error metrics. To provide insights into the data and model predictions, various visualizations such as pair plots, heat maps, PCA, and Actual vs Predicted plots were generated. The results from these models help classify landslides into alert zones, such as Red, Yellow, and Green, enabling more accurate and timely predictions that can inform early-warning systems and reduce disaster impacts.
<br>
<big>1. Pair Plot for Input Parameters</big>
<br>
The pair plot provides a grid of scatter plots showing relationships between every pair of features in the dataset. Each scatter plot helps visualize the correlation between two variables, while the diagonal often contains histograms for each feature to illustrate their distribution. This allows for quick identification of trends, potential correlations, or clusters among the input parameters.
<br>
The pair plot in this project helps in:
<br>Understanding relationships between variables such as temperature, moisture, rainfall, pressure, and displacement.
<br>Visualizing potential patterns and correlations between features that may influence landslide prediction.
<br>
<big>2. Heat Map for Input Parameters</big>
<br>
A heat map displays the correlation matrix of input parameters, where each cell is color-coded based on the correlation coefficient between the corresponding features. The heat map makes it easier to visually spot highly correlated features or any multicollinearity in the dataset, which may affect model performance.
<br>
In this project, the heat map helps in:
<br>Identifying input features with strong positive or negative correlations.
<br>Understanding which features might be more influential or redundant in the model for landslide prediction.
<br>
<big>3. Principal Component Analysis (PCA)</big>
<br>
PCA is a dimensionality reduction technique that transforms the dataset into a set of orthogonal (uncorrelated) components that capture the most variance in the data with fewer dimensions. By reducing the dimensionality of the dataset, PCA helps in improving model efficiency and reduces the risk of overfitting, especially when the dataset contains many features.
<br>
In this project, PCA was used to:
<br>Reduce the number of input features while retaining the most important variance information.
<br>Simplify the model training process by focusing on the most impactful components.
<br>Visualize the data in a reduced feature space, offering insights into how the data is distributed across the new principal components.
<br>
<big>4. Actual vs Predicted Plots</big>
<br>Scatter Plot: A scatter plot was created to visualize the relationship between the actual and predicted values, giving an immediate sense of how closely the model's predictions match the true data points. A perfect fit would align all points along the diagonal, while deviations from the line indicate prediction errors.
<br>Line Graph: The actual vs predicted line graph compares the trends of both sets of values over time. This plot helps in observing how well the model captures the pattern of changes in displacement over time.
