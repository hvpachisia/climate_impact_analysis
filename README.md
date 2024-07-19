# Climate and Natural Disasters Analysis

## Overview

This project delivers a multifaceted analysis of climate change and its impacts through the use of advanced analytical techniques, including interactive dashboards, Natural Language Processing (NLP), and computer vision. It is divided into three major sections:

1. **Natural Disasters in the United States: Frequency, Cost & Politics**  
   Analyzes disaster frequency and cost using Python and Dash, integrating data visualization and political analysis.

2. **RedditGoesGreen: Public Opinion on Climate Change**  
   Investigates public sentiment and discourse using advanced NLP techniques, including Transformer models and topic modeling.

3. **Urban Land Use Maps: Temporal Changes**  
   Converts static land use maps into interactive formats using computer vision and georeferencing for temporal analysis.

Each section showcases distinct coding skills and methodologies, providing a comprehensive view of climate change's diverse impacts. The code for each project is organized in its respective subfolder.

## Detailed Project Descriptions

## Natural Disasters in the United States: Frequency, Cost & Politics

This section examines the increasing frequency and cost of natural disasters in the U.S. over recent decades, along with the political responses to these changes.

**Technologies and Skills:**
- Python
- Dash for interactive dashboard creation
- Data scraping and API usage
- Data analysis and visualization

**Key Features:**
- Visualize the frequency and cost of natural disasters over time.
- Highlight impacts on specific states and counties.
- Analyze voting patterns on climate-related legislation.
- Utilize FEMA data, Climate IRA bill voting records, and the Census API for socio-economic data.

**Description:**

**42.63%** of natural disasters in the U.S. since 1980 have occurred in the last 12 years, highlighting the increasing frequency and cost of such events due to climate change. This dashboard visualizes these trends, examines state-specific impacts and political stances, and identifies high-risk counties based on socio-economic factors. The data sources include [FEMA disaster data](https://www.fema.gov/openfema-data-page/disaster-declarations-summaries-v2), [public assistance data](https://www.fema.gov/openfema-data-page/public-assistance-funded-project-summaries-v1), Climate IRA bill voting records, and the [Census API](https://www.census.gov/data/developers/data-sets.html).

**Running the Project:**
1. Clone the project repository.
2. Navigate to the project directory: `cd 30122-project-snow-lm`
3. Install dependencies using Poetry: `poetry install`
4. Activate the virtual environment: `poetry shell`
5. Set the environment variable for the U.S. Census API key: `export CENSUS_API_KEY=YOUR_KEY_HERE`
6. Run the project: `python3 -m snowlm`

Open the Dash application in your browser to view the interactive dashboard. Press `Ctrl+C` in your terminal to close the application.

## RedditGoesGreen: Public Opinion on Climate Change

This section explores public opinion on climate change through advanced NLP techniques, analyzing the Reddit Climate Change Dataset.

**Technologies and Skills:**
- PyTorch
- NLP techniques: sentiment analysis, topic modeling
- Transformer models (e.g., ClimateBERT)
- Data visualization

**Key Features:**
- Analyze sentiment trends over time.
- Compare the effectiveness of different NLP models.
- Extract and visualize key topics discussed in relation to climate change.

**Description:**

This project uses advanced NLP techniques to analyze sentiment and discourse on climate change from Reddit discussions. It evaluates the effectiveness of Transformer-based models like ClimateBERT compared to Word2Vec and uses topic modeling techniques such as LDA and BERTopic. The findings offer insights into public perceptions of climate change, valuable for policymakers, activists, and researchers.

**File Structure:**
1. `data/` folder: Contains filtered data. Note: Some datasets are stored in Google Drive due to size.
2. `eda/` folder: Contains exploratory data analysis scripts.
3. `models/` folder: Contains scripts for various NLP models and their evaluations.

## Urban Land Use Maps: Temporal Changes

This section converts static images of land use maps into interactive and classified maps for analyzing temporal changes.

**Technologies and Skills:**
- Python
- Computer Vision (OpenCV)
- Georeferencing (QGIS)
- Data visualization

**Key Features:**
- Convert static land use maps into interactive formats.
- Classify land use categories and analyze changes over time.
- Provide code templates for similar processes in other cities.

**Description:**

Most land use maps in developing countries are stored as static images in PDFs. This section, developed for the Energy Policy Institute at Chicago (EPIC), converts static images from 1972 to 2015 into interactive land use maps using computer vision and georeferencing techniques. While interactive maps cannot be shared, the provided code outlines how to perform similar processes for other cities.

## Contact Me

I’m always open to discussing my projects, potential collaborations, or opportunities. Feel free to reach out to me through the following channels:

- **Email**: [Email](mailto:hvpachisia@gmail.com)
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/hvpachisia)
- **GitHub**: [GitHub Profile](https://github.com/hvpachisia)
- **Portfolio**: [Personal Website](https://harshpachisia.com) 

Thank you for your interest in my work!