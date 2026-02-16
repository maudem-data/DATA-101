# DATA 101 Project: Milestone #2
Exploratory Data Analysis (EDA) on selected real-world dataset, including data loading, initial inspection, univariate and bivariate analysis, handling missing values and outliers, and summarizing key findings.

### Proposed Datasets for Comprehensive Exploratory Data Analysis

Here are three real-world datasets suitable for extensive Exploratory Data Analysis, chosen for their diversity in data types and potential for insightful investigations:

1.  **Titanic Dataset**
    *   **Description**: This classic dataset contains information about passengers on the Titanic, including demographics (age, sex), class, fare, and survival status.
    *   **Suitability for EDA**: It's excellent for understanding relationships between various features and a binary outcome (survival). It features a mix of numerical (Age, Fare), categorical (Sex, Embarked, Pclass), and ordinal (Pclass) data. Key EDA areas include:
        *   **Missing Values**: 'Age' and 'Cabin' columns often have significant missing data, requiring imputation or careful handling.
        *   **Outliers**: 'Fare' can have outliers. `SibSp` and `Parch` can also be explored for unusual family sizes.
        *   **Relationships**: Investigate correlations between 'Pclass', 'Sex', 'Age', and 'Fare' with 'Survival'.
        *   **Distributions**: Analyze the distribution of 'Age' and 'Fare' across different passenger groups.

2.  **California Housing Dataset**
    *   **Description**: This dataset contains information about housing prices in California districts based on various features such as median income, housing age, average rooms, population, and location (latitude and longitude).
    *   **Suitability for EDA**: It's ideal for regression analysis and exploring geographical data patterns. It primarily consists of numerical features, offering opportunities for:
        *   **Distributions**: Analyzing the distributions of median income, housing age, and house value.
        *   **Correlations**: Investigating relationships between features like median income, average rooms, and median house value.
        *   **Geospatial Analysis**: Using latitude and longitude to visualize spatial patterns in housing prices and other features.
        *   **Outliers**: Identifying unusually high or low values for house prices, incomes, or populations.
        *   **Feature Engineering**: Opportunities to create new features like 'rooms per household' or 'population density'.

3.  **Netflix Movies and TV Shows Dataset**
    *   **Description**: This dataset includes information about movies and TV shows available on Netflix, such as title, cast, director, country, release year, duration, listed in categories, and description.
    *   **Suitability for EDA**: This dataset is rich in diverse data types, making it excellent for content analysis, trend identification, and natural language processing (NLP) tasks. EDA aspects include:
        *   **Textual Analysis**: Analyzing 'title' and 'description' for common keywords, sentiment, or themes.
        *   **Categorical Analysis**: Exploring distributions and relationships between 'type' (movie/TV show), 'director', 'country', 'listed_in' (genres), and 'rating'.
        *   **Temporal Trends**: Analyzing trends over 'release_year' and 'date_added', such as the growth of content from different countries or genres.
        *   **Missing Values**: Handling missing data in 'director', 'cast', and 'country'.
        *   **Multi-value Fields**: Effectively processing 'cast' and 'listed_in' which are often comma-separated strings.
