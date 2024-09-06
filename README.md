# Detailed Statistics Mind Map
![Statistics Mind Map](./Statistics_mind_map_in_png.png)


## 1. Descriptive Statistics
- **Types of Data**
  - **Quantitative (Numerical)**
    - **Discrete**
      - Whole numbers (No decimal points)
      - Example: Number of students, number of banks
    - **Continuous**
      - Can take any value (Decimals included)
      - Example: Weight, height, temperature
  - **Qualitative (Categorical)**
    - **Nominal**
      - Categories without any order
      - Example: Gender (Male, Female), Type of car (Sedan, SUV)
    - **Ordinal**
      - Categories with a meaningful order or rank
      - Example: Satisfaction level (Low, Medium, High), Education level (High School, Bachelor's, Master's)

- **Measures of Central Tendency**
  - **Mean**
    - Arithmetic average of the data
    - Used when data is symmetrically distributed
  - **Median**
    - Middle value of the data
    - Used when data is skewed
  - **Mode**
    - Most frequently occurring value
    - Used for categorical data

- **Measures of Dispersion**
  - **Range**
    - Difference between maximum and minimum values
    - Example: Max = 100, Min = 50, Range = 50
  - **Variance**
    - Measures the spread of data points around the mean
    - Higher variance means more spread out
  - **Standard Deviation**
    - Square root of variance, shows dispersion in original units
  - **Interquartile Range (IQR)**
    - Spread of the middle 50% of data
    - Example: Q1 = 25th percentile, Q3 = 75th percentile, IQR = Q3 - Q1

- **Data Visualization**
  - **Histogram**
    - Shows the distribution of continuous data
  - **Bar Chart**
    - Used for comparing categorical data
  - **Box Plot**
    - Visualizes spread, median, and outliers in data

- **Skewness and Kurtosis**
  - **Left Skewed (Negative)**
    - Long tail on the left
    - Example: Exam scores where most students did well
  - **Right Skewed (Positive)**
    - Long tail on the right
    - Example: Income distribution
  - **Symmetric (Normal)**
    - Data is evenly spread
    - Mean, median, mode are equal

---

## 2. Inferential Statistics
- **Sampling Methods**
  - **Simple Random Sampling**
    - Every individual has an equal chance of being selected
  - **Stratified Sampling**
    - Divides population into subgroups (strata) and samples from each
  - **Cluster Sampling**
    - Divides population into clusters and samples entire clusters

- **Estimation**
  - **Point Estimate**
    - Single best guess for a population parameter (e.g., sample mean)
  - **Interval Estimate**
    - Provides a range of plausible values for the parameter
    - **Confidence Interval (CI)**
      - Range of values within which the true population parameter lies
      - 95% CI: Means we are 95% confident the true value lies within the interval

- **Hypothesis Testing**
  - **Null Hypothesis (H0)**
    - Assumes no effect or difference exists
  - **Alternative Hypothesis (H1)**
    - Assumes there is an effect or difference
  - **P-Value**
    - Probability of obtaining results as extreme as the observed ones if H0 is true
    - Example: P < 0.05 means we reject the null hypothesis
  - **Z-Test**
    - Used for large samples when population variance is known
  - **T-Test**
    - Used for smaller samples or when population variance is unknown
    - Types: Paired, Unpaired, One-sample

- **Errors in Hypothesis Testing**
  - **Type I Error (False Positive)**
    - Rejecting H0 when it is true
  - **Type II Error (False Negative)**
    - Failing to reject H0 when it is false

- **ANOVA (Analysis of Variance)**
  - Compares means across multiple groups
  - Assumptions: Normality, Homogeneity of variance
  - **Types:**
    - **One-way ANOVA**
      - Tests for differences between means of one factor
    - **Two-way ANOVA**
      - Tests for differences across two factors

---

## 3. Probability Distributions
- **Normal Distribution (Gaussian) (PDF)**
  - Symmetrical, bell-shaped distribution
  - Mean = Median = Mode
  - Common in natural and social sciences
  - **Example**: Height of adults
  - **Uses**: Z-scores, standard normal distribution

- **Bernoulli Distribution (PMF)**
  - Two possible outcomes: Success (1) or Failure (0)
  - **Example**: Flipping a coin (Heads = 1, Tails = 0)

- **Binomial Distribution (PMF)**
  - Number of successes in a fixed number of independent trials
  - **Example**: Tossing a coin 10 times, counting heads

- **Poisson Distribution (PMF)**
  - Probability of a given number of events occurring in a fixed interval
  - **Example**: Number of phone calls received per minute

- **Uniform Distribution**
  - Every outcome has an equal probability
  - **Example**: Rolling a fair die

- **Log-Normal Distribution (PDF)**
  - Distribution of a variable whose logarithm is normally distributed
  - **Example**: Stock prices

---

## 4. Correlation and Regression
- **Covariance**
  - Measures how two variables move together
  - Positive: Variables move in the same direction, Negative: Opposite directions
- **Correlation**
  - **Pearson Correlation**: Measures the linear relationship
  - **Spearman's Rank Correlation**: Measures monotonic relationships
- **Regression**
  - **Linear Regression**: Models the relationship between a dependent and independent variable
  - **Multiple Regression**: Involves more than one independent variable

---

## 5. Chi-Square Test (Categorical Data)
- **Goodness of Fit**
  - Compares observed data with expected frequencies
- **Test of Independence**
  - Determines if two categorical variables are related

---

## 6. F-Distribution (Variance Ratio Test)
- **F-Test**
  - Used to compare variances of two groups
  - Always right-skewed
  - **ANOVA** is based on F-distribution

---

## 7. ANOVA (Analysis of Variance)
- **Assumptions of ANOVA**
  - Normality
  - Homogeneity of variance
  - Independence of observations
- **Types of ANOVA**
  - **One-way ANOVA**: Tests differences between one factor
  - **Two-way ANOVA**: Tests differences across two factors
