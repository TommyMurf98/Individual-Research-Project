# Individual-Research-Project
This project is a research study focused on exploring weapon balance and popularity in battle royale games, with a specific emphasis on *Call of Duty: Warzone 2*. The goal is to investigate patterns in the popularity of certain guns and how developers address imbalances through "balance patches." The research aims to understand why certain guns become more dominant and how game publishers attempt to create a more balanced variety of weapons in first-person shooter (FPS) games.

Here’s a breakdown of the files and their purposes:

1. **Ethical Approval Form**: This document outlines the ethical considerations of the project, stating that no significant ethical issues were identified, and the research primarily uses data from questionnaires and publicly available datasets on gun popularity in *Warzone 2*. The study does not involve vulnerable groups, sensitive data, or other high-risk ethical concerns【10†source】.

2. **Google Forms Questionnaire**: The questionnaire asks participants about their gaming habits and opinions on weapon variety and balance in *Warzone 2*. It collects data on how players perceive weapon popularity and the role of certain types of guns in achieving success in the game【13†source】.

3. **Jupyter Notebook**: The Python notebook, titled *Individual Research Project.ipynb*, contains the developed software for analyzing the data from the questionnaire. Once opened and executed in Jupyter, it loads the data from the associated Excel sheet and generates graphs based on the responses【11†source】.

4. **Excel Data Sheet (Demo Responses)**: This sheet contains the raw responses from participants of the questionnaire, which are processed and analyzed in the Jupyter notebook to generate insights about the patterns of weapon popularity【11†source】【12†source】.

5. **Graph Results**: These are visual representations of the data collected from the survey responses, illustrating trends and patterns related to weapon balance and player preferences【12†source】.

In summary, the project examines how weapon choices and balance in *Warzone 2* influence gameplay, using a combination of survey data and analysis tools developed in Python. The findings aim to shed light on how game publishers manage weapon variety and balance in battle royale games.

Code Description
The Jupyter notebook is structured to analyze data collected from a questionnaire, focusing on player preferences and behavior in the game *Call of Duty: Warzone 2*. Here's a breakdown of the key parts of the code:

1. **Imports and Setup**: 
   - The notebook imports several libraries, such as `pandas`, `matplotlib`, `numpy`, and `re` for handling data, visualizing plots, and regular expressions.
   - It also adjusts the display format in Jupyter Notebook to optimize the layout for presenting the analysis results.

2. **Loading Data**:
   - The code reads in the data from the Excel sheet *Demo (Responses).xlsx* using `pandas`. The raw data is then renamed to more concise column names for easier reference, such as renaming questions related to preferences for specific gun types (e.g., machine guns, sniper rifles, etc.).

3. **Data Aggregation**:
   - A function called `aggregate_data_for_scatter_plot` is defined to aggregate the questionnaire responses. It groups the data by the values of the specified x-axis and y-axis columns (such as weekly gaming hours or skill level).
   - It also assigns a color code to represent the amount of data in each group. The color scheme is based on the frequency of the responses, where higher amounts are represented by red, followed by orange and blue.

4. **Plotting Data**:
   - The aggregated data is plotted using scatter plots. The scatter plots visualize the relationship between various player preferences (such as gun types, rate of fire, or meta weapon usage) and the player's self-reported skill level.
   - The size of the points in the scatter plot corresponds to the frequency of responses, making it easier to visualize which combinations of preferences and skill levels are more common among respondents.

5. **Additional Plots**:
   - The final part of the code iterates over different player preferences (such as "Machine gun preference", "Sniper rifle preference") and generates scatter plots to visualize how these preferences correlate with skill level, providing a comparative analysis of player behavior based on weapon choice.

In summary, this code processes and visualizes data from a questionnaire on *Warzone 2* player habits, focusing on the relationships between their weapon preferences and skill levels. The output consists of various scatter plots that help to identify trends in player choices and behavior.
