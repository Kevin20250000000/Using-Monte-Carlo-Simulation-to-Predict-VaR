# Using-Monte-Carlo-Simulation-to-Predict-VaR

# Value at Risk (VaR) 

 **Value at Risk (VaR)** is a widely used statistical measure in financial risk management that estimates the potential maximum loss of a portfolio or asset over a specified time frame, given a certain confidence level. It provides a probabilistic assessment of the worst-case scenario under normal market conditions.


**Key Components of VaR**

Time Horizon: The period over which the risk is assessed (e.g., one day, ten days, or one month).

Confidence Level: The probability that the loss will not exceed the VaR estimate (commonly 95% or 99%).

Potential Loss Amount: The estimated maximum loss in monetary terms or as a percentage of the portfolio's value.


##**Example**

Consider a portfolio with a one-day VaR of  1  million dollars at a 95% confidence level. This implies that there is a 95% chance that the portfolio will not lose more than $1 million in a single day, and a 5% chance that the loss could exceed this amount.


## **Calculation Methods**
**VaR can be calculated using several methods:**

### 1. Historical Simulation Method

For a given confidence level \( \alpha \) (e.g., 95% or 99%) and a historical dataset of returns, VaR can be estimated as:



### **VaR𝛼=Quantile𝛼(Return Distribution)**

where $(\text{Quantile}_{\alpha}$) is the value below which $( \alpha \% $) of the observations fall.

### 2. Variance-Covariance Method

In this method, assuming returns are normally distributed, VaR can be calculated using:

### **[VaR𝛼=𝜇−𝑍𝛼⋅𝜎]**



where:
- $(\mu$) = Mean of the portfolio returns
- $(\sigma$) = Standard deviation of the portfolio returns
- $(Z_{\alpha}$) = Z-score corresponding to the confidence level $( \alpha $) (e.g., 1.645 for 95% confidence)

### 3. Monte Carlo Simulation

VaR can also be estimated using Monte Carlo simulation by simulating a large number of portfolio returns and calculating the percentile value at the desired confidence level.



### **Limitations**

While VaR is a valuable tool for risk assessment, it has certain limitations:

Tail Risk Ignorance: VaR does not provide information about losses beyond the confidence level threshold, potentially underestimating extreme losses.

Assumption Sensitivity: The accuracy of VaR is highly dependent on the assumptions made regarding market behavior and return distributions.

Methodological Variance: Different calculation methods can yield varying VaR estimates for the same portfolio.

Despite these limitations, VaR remains a fundamental metric in financial risk management, aiding institutions in understanding and controlling potential losses.


### Part I
### **Variance-Covariance Method**

### Part II
### **Monte Carlo Method**
### Portfolio A: 95% VAR using MCM

![image](https://github.com/user-attachments/assets/d6cdc8ea-50b1-41a9-8c25-6f954eda30af)

![image](https://github.com/user-attachments/assets/1372cc24-967a-478f-acda-6b85f8a40c0f)

![image](https://github.com/user-attachments/assets/65f813b8-d282-485b-8f78-f4af10ba984d)


### Portfolio B: 95% VAR using MCM

![image](https://github.com/user-attachments/assets/b9e28a9e-792d-46dc-bb39-d2fcbe8fe225)

![image](https://github.com/user-attachments/assets/2da10835-731a-44c8-9d36-1367a96f19ef)

![image](https://github.com/user-attachments/assets/cfac10e9-7e07-4bab-82e5-f6f9eb356f01)






## Conclusion

Value at Risk (VaR) is a fundamental tool in financial risk management, providing a standardized measure to estimate potential losses in investment portfolios over a specified time frame and confidence level. By quantifying the maximum expected loss under normal market conditions, VaR enables investors and institutions to make informed decisions, optimize portfolios, and implement effective risk mitigation strategies.
