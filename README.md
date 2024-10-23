## Sales Funnel Analysis and A/A/B Test for a Food Company

This project aims to investigate user behavior within an app of an emerging company that sells food products. The analysis includes two main phases: studying the sales funnel and analyzing the results of an A/A/B test.

### Project Description

The company needs to better understand how users interact with the application, especially in the context of the purchase process. The analysis addresses two key aspects:

1. **Sales Funnel**: 
   - The goal is to discover how users reach the purchase stage within the app.
   - Key questions:
     - How many users actually reach the purchase stage?
     - How many users get stuck in earlier stages?
     - Which specific stages experience the most friction?

2. **A/A/B Test Analysis**:
   - The design team is evaluating changing the typography throughout the app, but there is concern that the changes might negatively impact the user experience.
   - To make a data-driven decision, an A/A/B test was conducted. Users were divided into three groups:
     - **Group A**: Control group, using the old fonts.
     - **Group A (duplicate)**: A second control group with the same old fonts to validate result consistency.
     - **Group B**: Test group, using the new fonts.
   - The analysis seeks to answer:
     - Which font set yields better results in terms of conversion and app usage?
     - Are there significant differences between the two Group A control groups? If so, what factors might be influencing these results?

### Benefits of Having Two Group A Control Groups

Using two control groups has key advantages:
- It ensures the results are reliable and accurate. If there are significant differences between the two Group A control groups, this may indicate underlying issues in the experiment or factors affecting the results.
- It helps estimate the amount of time and data needed for future tests, improving the planning of subsequent experiments.

### Dataset Used

The dataset contains information about user behavior within the app and will be used for both the sales funnel analysis and the A/A/B test.

### Project Contents

- **`notebooks/`**: Contains the notebooks where the complete analysis of the sales funnel and the A/A/B test is performed.
- **`datasets/`**: Includes the data used in the analysis (if sharing is allowed).
- **`environment.yml`**: File with the necessary dependencies to reproduce the environment.
- **`README.md`**: This file containing the project’s general description.

### Installation and Usage

To reproduce this analysis, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/704k0-dev/a_a_b_test.git
   ```

2. Create a Conda environment and install the dependencies:
   ```bash
   conda env create -f environment.yml
   conda activate environment_name
   ```

3. Open Jupyter Notebook and explore the analyses:
   ```bash
   jupyter notebook
   ```

### Project Conclusions

The results of this analysis enable the company to better understand user behavior within the sales funnel and make data-driven decisions regarding design changes in the app. In particular:
- Key points were identified where users tend to get stuck in the sales funnel, highlighting clear areas for improvement.
- The A/A/B test results showed that the new typography did not negatively affect the conversion rate, suggesting that it is safe to implement the new design across the app.

### License

This project is licensed under the MIT License – see the LICENSE file for details.
