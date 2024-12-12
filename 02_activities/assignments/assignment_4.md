# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
### What software did you use to create your data visualization?
The data visualization was created using **Microsoft Excel** and **Python**, leveraging its straightforward charting tools for summarizing and visualizing data.

---

### Who is your intended audience?
The intended audience includes urban planners, city council members, transportation professionals, and the general public who are interested in understanding the distribution of road types within Toronto.

---

### What information or message are you trying to convey with your visualization?
The visualization conveys the **distribution and prevalence of various road types in Toronto**, highlighting which types dominate the city’s infrastructure (e.g., local roads being the most common).

---

### What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
1. **Substantive**: The visualization is data-driven, presenting accurate and clear information by summarizing road types and their counts in descending order.
   - Applied through sorting data for better interpretation.
2. **Perceptual**: The bar chart format ensures readability, with distinct horizontal bars making comparisons intuitive.
   - Chose a horizontal layout to accommodate longer labels (road type names).
3. **Aesthetic**: Used a clean design with minimal distractions (e.g., no unnecessary gridlines) to maintain focus on the data.
   - Customized colors and chart title to enhance visual appeal.

---

### How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
- The summary table used to create the visualization was saved and shared as an Excel file. Anyone with the file can reproduce the chart by following simple steps in Excel.
- Microsoft Excel is widely available, making reproduction relatively easy, though non-automated tools like Excel may require manual effort to repeat the process.

---

### How did you ensure that your data visualization is accessible?
- **Labeling**: Clear axis labels and a descriptive title were used to ensure the information is understandable at a glance.
- **Sorting**: Data was sorted by counts in descending order to emphasize the most prevalent road types.
- **Exportability**: The visualization can be exported as an image or embedded in presentations to reach broader audiences.

---

### Who are the individuals and communities who might be impacted by your visualization?
- **Urban Planning**: Urban planners might use this data to prioritize infrastructure investments.
- **Residents and Commuters**: Communities in Toronto can better understand the infrastructure distribution in their areas.
- **Policy Makers**: City council members can use the insights for decision-making on transportation and public works.

---

### How did you choose which features of your chosen dataset to include or exclude from your visualization?
- **Included**: The `FEATURE_CODE_DESC` column was chosen because it directly relates to road types, the focus of the visualization.
- **Excluded**: Other attributes (e.g., geometry, intersection details) were omitted as they did not contribute to the core message.

---

### What ‘underwater labour’ contributed to your final data visualization product?
- **Data Cleaning**: Extracted and summarized relevant road type data from a larger dataset.
- **Software Navigation**: Manually formatted the chart in Excel to enhance readability.
- **Justification**: Considered the needs of the audience and selected the most appropriate features for the message being conveyed.

---



# Visualization Description and Justification

## What software did you use to create your data visualization?
This visualization was created using **Python**, specifically using the `matplotlib` and `pandas` libraries. These tools allow for precise customization and integration of bar charts and line plots.

---

## Who is your intended audience?
The intended audience includes:
1. **Urban Planners and Infrastructure Analysts**: To understand the distribution of feature types in Toronto's Centreline dataset.
2. **Policy Makers and Advocacy Groups**: To identify patterns in infrastructure data that may inform decisions or initiatives.
3. **Researchers and Students**: To use this as a case study for advanced data visualization techniques.

---

## What information or message are you trying to convey with your visualization?
The chart conveys:
1. The **frequency distribution** of the top 10 feature types in Toronto (e.g., Local roads, Trails, Minor Arterials).
2. The **cumulative frequency** of these feature types, highlighting their combined contribution to the overall dataset.

---

## What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
1. **Substantive**:
   - Focused on meaningful attributes like feature type and frequency for clear insights.
   - Added a cumulative line chart to provide additional context.

2. **Perceptual**:
   - Used distinct color coding for `Category A` (green) and `Category B` (purple) in the bar chart.
   - The cumulative line chart with red markers ensures differentiation from the bars.

3. **Aesthetic**:
   - Clean layout with annotations for both bar and line values to enhance readability.
   - Clear separation of dual axes (left for bar chart, right for line chart) for better interpretability.

---

## How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
1. **Reproducibility**:
   - The entire workflow was scripted in Python, ensuring full reproducibility.
   - The code includes preprocessing steps and customization, making it easy to replicate with the same dataset.

2. **Impact of Non-Reproducibility**:
   - Not applicable, as Python ensures reproducibility.

---

## How did you ensure that your data visualization is accessible?
1. **Color Contrast**:
   - Contrasting colors (green and purple) for bars and red for the cumulative line improve clarity.
2. **Annotations**:
   - Values are labeled on both bars and line points, aiding users with limited familiarity with charts.
3. **Dual Axes**:
   - Separate Y-axes clearly convey bar frequencies and cumulative totals without confusion.

---

## Who are the individuals and communities who might be impacted by your visualization?
1. **Urban Planners**: To optimize infrastructure development.
2. **Advocacy Groups**: To highlight underrepresented infrastructure categories.
3. **Students and Researchers**: To study data distribution and visualization techniques.

---

## How did you choose which features of your chosen dataset to include or exclude from your visualization?
1. **Inclusion**:
   - Focused on `FEATURE_CODE_DESC` (feature types), which is critical for understanding infrastructure categories.
   - Included cumulative frequency to emphasize contributions of feature types to the overall dataset.

2. **Exclusion**:
   - Excluded threaded archives and historical data, as they were not directly relevant to the chart's goals.

---

## What ‘underwater labour’ contributed to your final data visualization product?
1. **Data Preprocessing**:
   - Cleaned the dataset to focus on relevant columns and rows.
   - Calculated cumulative frequencies for accuracy.
2. **Chart Design**:
   - Iterated over multiple versions to balance aesthetics and clarity.
   - Adjusted bar heights, colors, and annotations for enhanced readability.
3. **Technical Refinement**:
   - Debugged cumulative line logic to ensure alignment with bar values.
   - Adjusted axes and legends for professional presentation.



- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
