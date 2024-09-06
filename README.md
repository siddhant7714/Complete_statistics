# Detailed Statistics Mind Map
![Statistics Mind Map](./Statistics%20mind%20map%20in%20png.png)



# Detailed Statistics Mind Map

## 1. Descriptive Statistics
Descriptive statistics summarize data and help you understand the basic patterns and characteristics. 

- **Types of Data**
  - **Quantitative (Numerical Data)**
    - **Discrete Data**: Whole numbers that cannot have decimal points.
      - **Example**: The number of books in a library. You can have 10 or 20 books, but not 10.5 books.
    - **Continuous Data**: Numbers that can take any value, including decimals.
      - **Example**: Height or weight. Someone could be 170.5 cm tall or weigh 68.75 kg.
  - **Qualitative (Categorical Data)**
    - **Nominal Data**: Categories that do not have an inherent order.
      - **Example**: Eye color (blue, brown, green), types of cars (sedan, truck, SUV).
    - **Ordinal Data**: Categories that follow a meaningful order or rank.
      - **Example**: Education levels (high school, bachelor’s, master’s), satisfaction levels (low, medium, high).

- **Measures of Central Tendency** (Summarizing the center of your data)
  - **Mean (x̄)**: The sum of all values divided by the number of values.
    - **Example**: The average test score in a class.
  - **Median (M)**: The middle value when data is ordered.
    - **Example**: Median household income.
  - **Mode**: The value that occurs most frequently.
    - **Example**: The most common shoe size in a store.

- **Measures of Dispersion** (Understanding how spread out the data is)
  - **Range (R)**: The difference between the maximum and minimum values.
    - **Example**: If the highest exam score is 95 and the lowest is 60, the range is 35.
  - **Variance (σ² or s²)**: Measures how far each data point is from the mean.
    - **Example**: If people's weights vary widely in a group, the variance is high.
  - **Standard Deviation (σ or s)**: The square root of variance.
    - **Example**: In a class where everyone scored similarly, the standard deviation would be low.
  - **Interquartile Range (IQR)**: Measures the spread of the middle 50% of the data.
    - **Example**: Difference between the 75th percentile (Q3) and 25th percentile (Q1).

- **Data Visualization Tools**
  - **Histogram**: Shows the frequency distribution of continuous data.
  - **Bar Chart**: Compares different categories of data.
  - **Box Plot**: Shows the spread of the data, including the median, quartiles, and outliers.

- **Skewness and Kurtosis** (Shape of Data)
  - **Left Skewed (Negative Skew)**: The left tail is longer, and most values are concentrated on the right.
  - **Right Skewed (Positive Skew)**: The right tail is longer, and most values are concentrated on the left.
  - **Symmetric Distribution (Normal)**: Mean, median, and mode are equal.

---

## 2. Inferential Statistics
Inferential statistics allow you to make predictions or generalizations about a population based on sample data.

- **Sampling Methods**
  - **Simple Random Sampling**: Every individual has an equal chance of being selected.
  - **Stratified Sampling**: Population divided into subgroups (strata) and random samples are taken from each.
  - **Cluster Sampling**: Population divided into clusters and entire clusters are sampled.

- **Estimation**
  - **Point Estimate**: A single value estimate of a population parameter (e.g., sample mean).
  - **Interval Estimate**: A range of values likely to include the population parameter.
    - **Confidence Interval (CI)**: Range of values within which the true population parameter lies.

- **Hypothesis Testing**
  - **Null Hypothesis (H₀)**: Assumes no effect or difference exists.
  - **Alternative Hypothesis (H₁)**: Assumes an effect or difference exists.
  - **P-Value (p)**: Probability of obtaining results as extreme as the observed ones if H₀ is true.
  - **Z-Test (Z)**: Used for large samples when population variance is known.
  - **T-Test (t)**: Used for smaller samples or when population variance is unknown.
    - Types: Paired, Unpaired, One-sample.

- **Errors in Hypothesis Testing**
  - **Type I Error (α)**: Rejecting H₀ when it’s true.
  - **Type II Error (β)**: Failing to reject H₀ when it’s false.

- **ANOVA (Analysis of Variance)**: Compares means across multiple groups to see if they differ significantly.
  - **One-Way ANOVA**: Compares means of one factor across several groups.
  - **Two-Way ANOVA**: Compares means across two factors.

---

## 3. Probability Distributions
A probability distribution describes how the values of a random variable are spread out.

- **Normal Distribution (N(μ,σ²))**: A symmetric bell-shaped curve where mean, median, and mode are equal.
  - **Example**: Heights of people, IQ scores.

- **Bernoulli Distribution (P(X=1))**: A distribution with two outcomes: success (1) or failure (0).
  - **Example**: Flipping a coin.

- **Binomial Distribution (B(n,p))**: Describes the number of successes in a fixed number of independent trials.
  - **Example**: Number of heads in 10 coin tosses.

- **Poisson Distribution (P(X=k))**: Used for counting the number of events happening in a fixed interval of time or space.
  - **Example**: Number of calls received at a call center per hour.

- **Uniform Distribution**: All outcomes are equally likely.
  - **Example**: Rolling a fair die (each face has a 1/6 probability).

- **Log-Normal Distribution**: A distribution where the logarithm of the variable is normally distributed.
  - **Example**: Stock prices.

---

## 4. Correlation and Regression
Exploring relationships between variables.

- **Covariance (Cov(X,Y))**: Measures how two variables move together.
- **Correlation (ρ or r)**: A normalized version of covariance.
  - **Pearson Correlation (rₓᵧ)**: Measures the strength of the linear relationship.
  - **Spearman's Rank Correlation (ρₛ)**: Measures monotonic relationships (not necessarily linear).
- **Regression**
  - **Linear Regression (Y = β₀ + β₁X)**: Predicts the value of a dependent variable based on an independent variable.
  - **Multiple Regression (Y = β₀ + β₁X₁ + β₂X₂ + ...)**: Uses more than one independent variable to make predictions.

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
