# Statistical-Analysis-and-A-B-Testing

---

## Part 1: A/B Testing in Cookie Cats
**Objective**: This repository contains the code and analysis conducted for the popular game **Cookie Cats**, as well as the testing of various statistical methods. To investigate the impact of moving the gate from level 30 to level 40 on player retention.

### Details:
- **Control Group**: `gate_30` (gate at level 30).
- **Test Group**: `gate_40` (gate at level 40).
- **Key Metrics**:
  - `retention_1`: Whether the player returned to the game 1 day after installation.
  - `retention_7`: Whether the player returned to the game 7 days after installation.

---

## Part 2: Statistical Methods Testing
**Objective**: To evaluate and demonstrate the application of various statistical methods using test data.

### Methods:
1. **Distribution Analysis**:
   - A histogram of the data was created and overlaid with a linear density plot.
   - The graph shows that the data closely matches the theoretical normal distribution, exhibiting a characteristic bell-shaped form.

2. **QQ-Plot**:
   - Constructed to compare the data with the theoretical normal distribution.
   - The points on the plot lie approximately along a straight line, indicating that the data follows a normal distribution.

3. **Shapiro-Wilk Test**:
   - Conducted to assess the normality of the data distribution.
   - **Null Hypothesis (H₀)**: The data follows a normal distribution.
   - **Results**:
     - If p-value > 0.05: Fail to reject H₀, indicating the data is normally distributed.
     - If p-value ≤ 0.05: Reject H₀, indicating the data is not normally distributed.

4. **Pearson Correlation**:
   - Investigated the relationship between the total purchase amount and the number of visits.
   - Calculated the Pearson correlation coefficient and created a scatter plot to visualize the correlation.

5. **Z-Test and T-Test**:
   - Conducted tests on mean values to determine the statistical significance of differences in data.
   - Compared two datasets (July and August 2022).

6. **Chi-Square Test**:
   - Examined the relationship between categorical variables.
   - Used a contingency table to analyze dependencies.

---
