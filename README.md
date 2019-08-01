# Final-Project

Here's the link to my main [portfolio](https://ramitasingh.github.io/Telling-Stories-with-Data/)
# Outline

For my project, I'm going to be focusing on creating a story for a project that I've been working on during my internship at the Healthcare Council of Western PA. The project focusses on increasing the rate of health insured people in the state with a current focus on increasing health insurance literacy. This means increasing awareness of the benefits of insurance and what insurance options people have. The Council aims to do this by conducting teach-the-trainer modules and certifying people who attend these sessions as 'health insurance literate', and this people in turn will continue to spread the information. Morevoer, a small monetary incentive is also provided to those attending these sessions.  While this sounds like a great project for community well being, it's hard to get a size-able amount of funding for the same. 
I aim to present data in a very comprehensive manner that can used for grant submissions for any type of private, state or federal funding. The data I would be focussing on presenting is the health insurance data of the state. The aim is to prove that improving health insurance literacy can lead to a decrease in the number of uninsured.

## Project Structure 
There are several facts I would want to get across to the viewer hopefully in the following order.
- First, the latest percentage of total uninsured in the state below 64 years of age. I would love to in some way incorporate a county-wise breakdown but since there are 67 counties I will have to figure out a concise way of doing this and possibly use a map for the same.
- Second, I would like to breakdown this percentage to reflect more targeted groups by differentiating them based on race, income levels and other factors
-Third ( I'm not sure if I should present this first ) is the trend of uninsured rates in the country over the past 10 years. The most recent data point is that of 2017 and I'm aware that the data is an anomaly. This visualization can then further lead to discussion about the possible reasons for the data point being so different
-Finally, I'll talk about different factors that contribute to people being uninsured and how funding such programs can help overcome this.

## Initial Sketches
![part1](https://raw.githubusercontent.com/ramitasingh/Final-Project/master/project-1.jpg)
![part2](https://raw.githubusercontent.com/ramitasingh/Final-Project/master/project-2.jpg)
![part3](https://raw.githubusercontent.com/ramitasingh/Final-Project/master/project-3.jpg)
![part4](https://raw.githubusercontent.com/ramitasingh/Final-Project/master/project-4.jpg)



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

# Part 2
Upon doing quite a bit of research, I had to modify bits of Part 1 and change the flow of my story. I noticed Pennsylvania had a good trend in terms of health insurance rates ( or here I'm talking in terms of uninsured rates) so this would not give the audience a sense of alarm about wanting to change the trend. I transitioned into stating facts that show that uninsurance is still a problem in the country

I showed a first draft of my [shorthand storyboard](<script src="https://embed.shorthand.com/embed_6.js"></script>
<div data-shorthand-embed="carnegiemellon.shorthandstories.com/health_insurance/"><h1>Health Insurance 101</h1><p>Why increase health insurance literacy in the state? </p></div>) to a few people and received relevant feedback. 

The target audience I want my story to reach is the more underserved population of Pennsylvania. I want to increase awareness about the program and let people know that resources exist that can help with a topic as complicated as health insurance, whether they want to obtain it or if they have questions in general. But this also means I need the general population to be an audience because they are an important medium of spreading this awareness.

I interviewed 4 people to gain more insights and I wanted to use people either in the healthcare community or those affected by it. So I asked an employee at the Healthcare Council of Pennsylvania who oversees the health equity department,  a participant of one the health care insurance sessions , a graduate student and a friend of mine who lost her job and her insurance.
I was able to ask two in person and two through an e-mail.

My questions were as follows

1. What is your first impression of the message this storyboard is trying to potray?
2. Did you think there were too many or too few visualizations?
3. How did you feel about the length of the storyboard?
4. Do you think the story was transitioning in a smooth manner?
5. Did you find it to be intriguing or a little dragggy
6. Were there too many or too few facts?
7. Did you think the colors in the storyboard suited the topic? Did you find them too distracting?
8. Please do provide any other feedback you might feel relevant

The findings from my interviews
 
 1. Employee from the Healthcare Coouncil 
 She definitely was not able to comprehend the clear message of the storyboard. She thought it was a general presentation on insurance statistics in the state. She thought it wasn't clear that there was a need for anything because Pennsylvania seemed to be doing well. Because of that she also suggested I did some further data analysis based on demographics, I had to overlook this because I thought the message would get lost if this became the focus.
 She thought the length of the storyboard was fine and was okay with the number of visualiations.
 In terms of the transitioning of the story, she did think I could improve on it especially on how I try to bring out the benefits of social programs. 
 
 **Implementations** : I incorporated why Pennsylvania is still in danger of a large uninsured population so that general sense of calmness about Pennsylvania does not set in with the audience. I also worked around the data visualizations general positioning in the storyboard so that there was more flow to the story. I felt this had a lot to do with the map visualization and had to play around with it quite a bit.
 
 2. Participant from the health insurance session
 I was really happy because he was able to comprehend the data visualizations really well and differentiate between what was a 'good trend' and what was a 'bad trend'. As somebody who just received health insurance, he wanted to see more resources about these programs. He also thought the ending was not very justified. He also thought I could put in more written information since I seemed to have just graphics
 He seemed to be fine with the layout, length and colours, or didn't really seem to care about it.
 
 **Implementations** I'm still having trouble with my call to action and how to frame it or word it. Since there is no official website for the health insurance training provided by the Healthcare Council, I'm not sure what to link for it. But I might be able to find information for other resources. I did put in more paragraphs, especially to explain the visualizations.
 
 3. Graduate student
 I got a ton of feedback because he seemed to only be looking for mistakes in my storyboard. He pointed out a couple of typos (oops), and a lot of color schemes. There was a sudden abrupt change in background color and the text color was a little off in a couple of places. He seemed satisfied with the length. He also thought that the story needed a better flow. He also did not like the picture I used initally as a background. He also thought I needed to improve upon my call to action..or rather incorporate it.
 
 **Implementations**
 His feedback specifically helped me alter my background. I had to tweak around the colors and images I used to make it more easy on the easy. I fixed my typos as well.Again, I'm still trying to incorporate an appropriate call to action.
 
 4. Friend who lost insurance
 This was a last minute response so I wasn't able to incorporate much of the feedback but I will work on it. The link to my storyboard had been updated so she did get to see the latest version of my storyboard with everyone else's input. She didn't have too much to contribute about the technicalities but she did say that it lacked an emotional appeal to people who are at risk of not having health insurance. This makes a lot of sense to me but I don't know how to shift the tone through the storyboard but I will definitely ponder over it. 
 

