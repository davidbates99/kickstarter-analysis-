# Kickstarter Campaign Analysis
  ## Overview
This analysis was designed to discover the ideal timing for launch and probability of success for a kickstarter campaign in the United States with the intentions to release a play.

Kickstarter is a crowdfunding platform based in the United States, focused on bringing creative projects to fruition. Kickstarter is unique in letting the organizer maintain total creative freedom over their project.

> Since our launch, on April 28, 2009, 19 million people have backed a project, $5.3 billion has been pledged, and 188,887 projects have been successfully funded. 

  ## Analysis and Challenge
There were some inhibiting challenges during this analysis. Unfortunately when determining the probability of success the COUNTIFS() function would not pull all of the statistics necessary to reach conclusive results. When troubleshooting this problem, it was discovered there were several hundred data points missed by the ranges created. When pulling this information without range criteria it was possible to pull more data, but for an undiscovered reason this was left unresolved despite best efforts. 

  ## Results
Based on the data provided it can be concluded, the best time to launch the Kickstarter campaign will be in the early days of May asking for less than $5000 OR a number between $35000 to $40000. Do not launch during December no matter what. 

  ![](/Theatre_outcomes_vs_Launch.png)

  ![](/Outcomes_vs_Goals.png)

Kickstarter claims to have successfully funded 188,887 projects at the time of writing this analysis, but our data only had 4,114 successful, failed or canceled campaigns to pull from. Within the data there are 2185 successful campaigns, representing less than 1% of the total successful campaigns kickstarter has had. This data is more than likely not representative of the total picture. 
      
If desired, it would be possible to determine the probability of success for other campaigns, like theatre in Great Britain. It would also be possible to determine about how many patrons to expect, how much extra funding was received based on set goal and which countries which receive the most funding for specific campaigns.
