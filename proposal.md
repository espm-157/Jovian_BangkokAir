# Final project proposal


Please prepare a short proposal on your final project idea by **Nov 2**. The proposal should include:

- Title & description of the project
- Your name & partner's name
- A description of the data required, and how it will be obtained (e.g. URL/DOI to data source)
- 3 questions / analysis tasks you will perform on the data; in the spirit of the assignments we have been doing.

Project Title: Tracking the Air Pollution in Chiang Mai, Thialand

Description: There are four main sources for the air pollution in Chiang Mai, including traffic, power plants, industrial activities, and agricultural burning. This project aims to use the existing data to analyze, compare, and rank their contributions to the air pollution. 

Name: Jieyuan Kan (Individual Final Project)

Data Source: There is a open source dataset from United Nations Economic and Social Commission for Asia and Pacific. 
https://github.com/worasom/aqi_thailand2

Questions / Analysis Tasks on the Data:
1. Perform the analysis on the influences of each factor on the air pollution.
2. Rank the extent of their influences through high to low.
3. By how much reduction can we make to make the air pollutin in a healthy level in Chiang Mai.

*You may choose to work with your partner or independently on the final project. Please indicate which clearly in your proposal.*

Replicating results of an existing study and exploring the impact of alternative assumptions in the data preparation, statistical methods chosen etc can provide an excellent template for an analysis (you'll see more of this in units 3 & 4)


Please create your proposal in a markdown file called `proposal.md` in the root directory of the final project repo.  


## Project Guidelines

### Project questions must illustrate all of the following tasks:

- Some form of data access / reading into R
- Data tidying preparation
- Initial data visualization
- Use of GitHub
- Reproducible execution with use of Travis
- RMarkdown writeup, with final submission as a nicely formatted PDF document that includes code and results.
- Overall clean and clear presentation of repository, code, and explanations.

### and at least three of the following skills (this list may be modified/extended):

- Use of at least 5 `dplyr` verbs / functions
- Writing / working with custom R functions
- Creating an R package for functions used in the analysis
- Interaction with an API
- Use of regular expressions
- Use of an external relational database
- Preparing processed data for archiving / publication
- Parsing extensible data formats (JSON, XML)
- Use of spatial vector data (`sf` package) and visualization of spatial data
- Creation of an R package
- Expansion of ggplot functions (to include more than default characteristics)
- Making layout and presentation into secondary output (e.g. .pdf, website) - should enhance presentaiton
- use lintr to clean code (checks adherence to a given style, syntax errors and possible semantic issues)

# Final Rubric 30 pts total

 - 5pts Proposal, turned in on time and with team member names, background, dataset, and 3 potential questions.

 - 10pts Polished github repository, including:
	 -  3pt updated readme with functional travis badge 
	 -  2pt passing travis build 
	 -  2pt clean and well formatted output document (html, pdf, or md with associated files). 
	 -  3pt enough supporting text that we can easily understand the project undertaken.
	 
 - 15 pts Project Substance: Objectives, Code, Visualization. Do you meet all of the required project objectives and at least 3 of the supplementary objectives.
	 - 15pts: exceptional
	 - 13pts: adequate and complete
	 - 11pts: adequate 2 questions, meeting 3 supplementary objectives
	 - 9pts: adequate 2 q, meeting 1-2 supplementary objectives
	 - 7pts: adequate 1 q, meeting 3 supplementary objectives
	 - 5pts: adequate 1q, meeting 1-2 supplementary objectives
