The motivation behind this repository comes from the need to simplify and clarify the application of time series interpolation methods. While researching time series analysis, I noticed there was a lack of easy-to-understand tutorials that explain interpolation techniques in a practical, real-world context. I decided to create this repository to fill that gap and offer a beginner-friendly explanation of three common interpolation methods—**linear**, **polynomial**, and **spline**. By using key macroeconomic indicators like **GDP** and **CPI** as sample data, I aim to provide a hands-on approach that not only explains the statistical rationale behind each method but also demonstrates their practical application through Python visualizations.

# Time Series Interpolation Methods

This repository is dedicated to exploring key data science questions related to time series interpolation, both in terms of content and techniques. It contains projects and tutorials that I am confident enough to publish and believe others will find valuable. While conducting my research on time series analysis, I found there were few tutorials that clearly explain interpolation methods in a practical and easy-to-understand manner. This project was created to fill that gap, providing a straightforward approach to three common interpolation methods—**linear**, **polynomial**, and **spline**—using real-world macroeconomic indicators like **GDP** and **CPI** as sample data. The goal is to explain the rationale behind these methods with clear, practical applications and visualizations in Python.
  
## Overview

Interpolation is a method of estimating unknown values that fall within a range of known values in a time series dataset. This repository demonstrates the application of three widely-used interpolation methods for time series data, providing both theoretical explanations and practical Python implementations. The project uses macroeconomic indicators like **GDP** and **CPI** to illustrate the methods and includes visualizations for a clear comparison of the techniques.

### Methods Covered:
1. **Linear Interpolation**: A simple method where unknown values are estimated based on a straight line between known data points.
2. **Polynomial Interpolation**: A more flexible method that fits a polynomial to the data, providing a smoother curve than linear interpolation.
3. **Spline Interpolation**: Uses piecewise polynomials to create a smooth curve that passes through the data points, with more flexibility than polynomial interpolation.

## Getting Started

To get started with this project, you will need to have Python installed along with the necessary libraries. If you don't have them, you can install them via `pip`:

### Prerequisites

- Python 3.x
- Jupyter Notebook or another Python IDE
- Required libraries:  
  `numpy`, `pandas`, `matplotlib`, `scipy`

You can install the necessary libraries with the following:

```bash
pip install numpy pandas matplotlib scipy

```

### Sample Data: 
1.**UK monthly GDP from Jan 2021 to Apr 2023** <br />
2.**UK CPI**
