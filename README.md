# Integrated Project II: App UX Analysis & A/A/B Testing

## Description
This is the second capstone project of the curriculum, representing a comprehensive application of data science to Product Analytics. The project evaluates User Experience (UX) through a controlled experiment, analyzing user behavior within an app to determine the impact of design changes on conversion and retention.

## Project's Objective
The primary goal is to perform a rigorous A/A/B test to validate the integrity of the testing environment and measure the effectiveness of specific UI/UX modifications. By utilizing the full data stack, the project aims to provide a final recommendation on whether to implement new app features.

## Results
- **Experiment Validation:** Successful A/A testing confirmed that user groups were split without bias and that the testing platform was functionally sound for 2026 standards [1].
- **UX Insights:** Detailed mapping of the conversion funnel, identifying exactly where users drop off.
- **Statistical Verdict:** Documented evidence on whether the "B" variant (new design) outperformed the "A" variants with statistical significance.

## Methodology
The project follows a high-level experimental workflow:
1.  **Funnel Exploration:** Analyzing the sequence of events (Login -> Product Page -> Cart -> Payment) to establish baseline behavior.
2.  **A/A Testing:** Comparing two control groups to ensure the statistical tools do not find significant differences where none should exist.
3.  **A/B Testing:** Comparing the control groups against the test group (Group B) to evaluate the new UX feature.
4.  **Significance Testing:** Applying Z-tests and T-tests to analyze conversion rates between groups.

## Utilized Tools
- **Data Engine:** [Pandas](https://pandas.pydata.org) & [NumPy](https://numpy.org).
- **Interactive Visuals:** [Plotly](https://plotly.com) (used for dynamic funnel visualizations and user flow charts).
- **Static Analysis:** [Seaborn](https://seaborn.pydata.org) (for distribution and error bar plotting).
- **Statistics:** [SciPy](https://scipy.org) (for hypothesis testing and calculating p-values).

## Acquired/Developed Abilities
- **A/A/B Testing Rigor:** Understanding the necessity of twin control groups to validate experimental design.
- **Product Analytics:** Calculating funnel conversion rates and identifying friction points in the user journey.
- **Advanced Visualization:** Crafting interactive funnels that allow stakeholders to see data at various granularities.
- **Decision Science:** Making high-stakes product recommendations based on statistical power and significance levels.

## Upgrades to be Made
- [ ] Implement **Segmented A/B Testing** to see if the new UX affects different operating systems (iOS vs. Android) differently.
- [ ] Add **Retention Cohorts** to measure the long-term impact of the UX change beyond the initial conversion.
- [ ] Integrate **Bayesian Statistics** for faster decision-making in real-time testing scenarios.

## How to Run It
You can run the project files in two ways:

### Option 1: Google Colab
1. Upload the `.ipynb` files directly to [Google Colab](https://colab.research.google.com).
2. Run the cells sequentially.

### Option 2: Local Environment (VS Code)
1. Ensure you have [Python](https://www.python.orgdownloads/) installed.
2. Install the **Jupyter Extension** in VS Code.
3. Open the `.ipynb` file and select your Python interpreter.

---
## Contact & Contribution
If you want to contribute or have any questions, feel free to reach out:
- [**GitHub:**](https://github.com/Lord-of-Souls)
- [**Linkedin:**](www.linkedin.com/in/lucasfranciscon)
