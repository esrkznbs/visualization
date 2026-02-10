# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

# Tableau visualization: ![## Visualization 1 – Neighbourhood Comparison of Reported Intimate Partner and Family Violence Incidents (Tableau)
](Tableau_visual.png)

Link to the dataset: https://open.toronto.ca/dataset/intimate-partner-and-family-violence/
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
# I used Tableau for my first visual. 
    > Who is your intended audience? 
# My intended audience is policy makers and the police force.
    > What information or message are you trying to convey with your visualization? 
# In the first visual I am communicating the intensity of intimate partner and family violence in Toronto based on the neighbourhood which can help offer tailored solutions to specific neihgbourhoods. 
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
# I first thought about using a map but I noticed that the dataset I chose didn't contain the geo-information I needed in Tableau. Then I thought the most impactful presentation of the dataset would be ordering them based on the intesity of incidents to draw attention to particular locations.
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
# This tool is less reproducible by its nature.Another user could reproduce the same visualization with the same data set only. Therefore exact replication is not as easy as it would be with Python. To mitigate this I kept the design simple.
    > How did you ensure that your data visualization is accessible?  
# Some of the neighbourhood names are pretty long. To make it more accessible I used horizontal bars to accomodate the names and to prevent overlaps. The color choice is simple one tone against a contrasting background which pops up the bars and makes it easier to differentiate from ano another. 
    > Who are the individuals and communities who might be impacted by your visualization?  
# The individuals and communities impacted by this visualization include survivors of intimate partner and family violence, their families, and the neighbourhoods where incidents are reported. These visualizations may influence how the public, policymakers, and service providers understand patterns of reported violence in Toronto.
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
# I selected variables that directly supported the specific questions each visualization was designed to answer. I used Tableau to answer the where and location comparison questions.I focused on neighbourhood and total incident count to communicate geographic variation in reported incidents.
    > What ‘underwater labour’ contributed to your final data visualization product?
# A significant amount of “underwater labour” contributed to the final visualizations, even though these steps are not visible in the charts themselves. This included reviewing the dataset to understand its structure, identifying which columns were relevant, and verifying that the incident counts were already aggregated per record. I also checked for missing or inconsistent values in key fields
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
* Submission Due Date: `23:59 - 02/02/2026`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
