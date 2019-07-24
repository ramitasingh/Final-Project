# Final-Project

Here's the link to my main [portfolio](https://ramitasingh.github.io/Telling-Stories-with-Data/)
# Outline

For my project, I'm going to be focusing on creating a story for a project that I've been working on during my internship at the Healthcare Council of Western PA. The project focusses on increasing the rate of health insured people in the state with a current focus on increasing health insurance literacy. This means increasing awareness of the benefits of insurance and what insurance options people have. The Council aims to do this by conducting teach-the-trainer modules and certifying people who attend these sessions as 'health insurance literate', and this people in turn will continue to spread the information. Morevoer, a small monetary incentive is also provided to those attending these sessions.  While this sounds like a great project for community well being, it's hard to get a size-able amount of funding for the same. 
I aim to present data in a very comprehensive manner that can used for grant submissions for any type of private, state or federal funding. The data I would be focussing on presenting is the health insurance data of the state. The aim is to prove that improving health insurance literacy can lead to a decrease in the number of uninsured.

## Project Structure 
There are several facts I would want to get across to the viewer hopefully in the following order.
- First, the latest percentage of total uninsured in the state below 64 years of age. I would love to in some way incorporate a county-wise breakdown but since there are 67 counties I will have to figure out a concise way of doing this and possibly use a map for the same.
- Second, I would like to breakdown this percentage to reflect more targeted groups by differentiating them based on race, income levels and other factors
-Third ( I'm not sure if I should present this first ) is the trend of uninsured rates in the state over the past 10 years. The most recent data point is that of 2017 and I'm aware that the data is an anomaly. This visualization can then further lead to discussion about the possible reasons for the data point being so different
-Finally, I'll talk about different factors that contribute to people being uninsured and how funding such programs can help overcome this.

## Initial Sketches
![part1](https://raw.githubusercontent.com/ramitasingh/Final-Project/master/project-1.jpg

![part1](https://github.com/ramitasingh/Final-Project/blob/master/project-1.jpg)
![part2](https://github.com/ramitasingh/Final-Project/blob/master/project-2.jpg)
![part3](https://github.com/ramitasingh/Final-Project/blob/master/project-3.jpg)
![part4](https://github.com/ramitasingh/Final-Project/blob/master/project-4.jpg)


## Stakeholders
The stakeholders for this include 
- The Healthcare Council of Western Pennsylvania
- It's partners including organizations like Primary Health Network and Consumer Health Coalition
- Potential sources for funding like different state and federal organizations, for eg: The Pennsylvania Insurance Department
- Insurance providers like Highmark and UPMC Health Plan

## Challenges
- It is hard to change the mentality of people who cannot afford insurance
- Funding organizations are convinced that other social determinants of health require more funding
- Federal funding would prefer to direct funding to other states that have a higher overall percentage of uninsured
- People might take advantage of the monetary incentive and not attend sessions for it's actual purpose

# The data
The data I'm going to use for the project are the datasets from the [Small Area Health Insurance Estimates (SAHIE) Program](https://www.census.gov/data/datasets/time-series/demo/sahie/estimates-acs.html) by the US Census Bureau using the American Community Survey


I also found out the [FactFinder tool](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml) that allows you to narrow down specific census data and then download the files.


For the first few parts I will be using the most recent estimates, ie. the 2017 estimates. The dataset is huge but I'm confident I can consolidate and filter it using R programming. I've use heatmaps in datawrapper before so ideally I'd like to highlight the counties in Pennsylvania that have the lowest percentage of health insurance.

I will continue to use this dataset through the comparison amongst different social groups. I'd like to highlight the different in uninsured rates among difference races, sexes and income groups. I'd try to stay away from pie-charts in general because it would be too much information to fit in. Since everything would be a percent of the total uninsured, I think a bar chart with standardized colours is something I would lean to. I'm really very bad at comprehending Alluvial charts but I think in segmenting from the total propulation -> sex -> income -> race could be accurately represented through one. But I also want to keep in mind that my audience should be able to understand it. So I'll experiment with both the bar chart and alluvial diagram for this part and decide on the better one.
I also thought of exploring general trends of poverty and unemployment in the state to find a link, and I'll explore that through the Factfinder tool.

Finally to demonstrate the change over time in the state and the sudden disruption in 2017, I will use the SAHIE estimates from 2008 to 2017. Although this would require me downloading 10 datasets, I only need to extract a row of data from each of these datasets. I'd use a simple visualization for this since it's 10 datapoints over 10 years, like a line graph and highlight the anomaly in 2017. 

## Method and Medium
I will utilise shorthand as the medium of presenting my project. I will try to follow the project structure I've laid out and convey as much as I can through the visualizations. I'm hoping that I can somehow create a path of increasing magnitude of solemness as the user scrolls down from on visualization to the next so that by the final visualization, they can be convinced of the necessity of this project (ie, the funding! ). I will probably avoid the use of multimedia like music and video for this presentation.
 
