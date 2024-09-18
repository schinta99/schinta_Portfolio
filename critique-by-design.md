| [home page](README.md) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

## Critique by Design: Redesigning Data Visualization for Better Insight
In this project, I selected a data visualization from MakeoverMonday to critique and redesign. The aim is to create a more effective representation of the data for the intended audience.
I created a standard critique mechanism based on Good Charts and Stephen Few's Data Visualization Effectiveness Profile. 

## Step one: the visualization

I chose a  visualization having title "Average Age of Women at First Marriage by State vs. State Population Density [OC]". This scatter plot compares the average age of women at first marriage across different states in the United States with each state's population density.



![Alt Text](Scatter-Plot.png)


Source - https://www.reddit.com/r/dataisbeautiful/comments/wzx70h/average_age_of_women_at_first_marriage_by_state/

The scatter plot aims to depict a relationship between the average age of women at first marriage and state population density. The x-axis represents the average age, while the y-axis shows the population density per square mile. The plot suggests a potential trend where states with higher population densities tend to have a higher median age of first marriage, indicating that women in densely populated areas might marry later.

In the upcoming steps, I will critique this design, propose new ideas and redesigns to improve its effectiveness in conveying the data.


## Step two: the critique


Based on Stephan Few's Data Visualization Effectiveness Profile and Good charts, I have evaluated the visualization as follows - 

1) Visual Effectiveness Summary - 
Usefulness (Rating: 4/10)
The chart provides some insight into the relationship between population density and the average age of women at first marriage across states. However, its usefulness is limited because it lacks clear labels or identifiers for individual states making it difficult to decipher valuable context and make actionable insights.
Completeness (Rating: 3/10)
The scatter plot does not include key information like state labels or a clear description of what the clusters represent. Additionally, the title suggests a comparison across states, but the states themselves are not identifiable on the plot. Including data labels, a legend, and trend lines could enhance the completeness of the visualization.
Perceptibility (Rating: 3/10)
The scatter plot is difficult to interpret. The clustering of points near the lower end of the population density axis makes it hard to see individual data points. The exact values of age and population density are also unclear as we need to tilt our head to view the data, which complicates interpretation. Changing the Y-axis to a logarithmic scale and including state labels could improve clarity.
Truthfulness (Rating: 7/10)
Given the specifcity of the data points, it looks like the scatter plot is accurate. It does, however, imply a correlation between population density and marriage age, which might lead to assumptions about causation. While it truthfully displays the data, the lack of explanatory context can lead to misinterpretation.
Intuitiveness (Rating: 3/10)
The scatter plot format is familiar, but the lack of labels for states and the difficulty in reading exact values makes it less intuitive. Annotations such as hover-over details, would help make the plot easier to understand.
Aesthetics (Rating: 5/10)
The plot is visually clean, but it is quite plain and does not use color effectively to enhance understanding. Using color gradients to represent different regions or clustering could make it more visually appealing and informative.
Engagement (Rating: 4/10)
The scatter plot does show a potential trend between age and population density, which could spark interest. However, the lack of labels and context reduces its overall engagement. Including annotations or a trend line would draw the viewer more into the data and encourage further exploration.


While the scatter plot seems accurate, it lacks in usefulness, completeness, aesthetics and clarity due to the absence of state labels, annotations, and effective use of color.

2) Contextual Summary - 

The scatter plot effectively hints at a potential trend between population density and the average age of first marriage, with data points accurately representing this relationship. However, it lacks key elements such as state labels, a clear title, and a trend line, making it difficult to interpret and limiting its usefulness for state-wise analysis. To improve clarity and accessibility, the visualization could be redesigned as a horizontal bar chart with states on the y-axis and median age on the x-axis, using hover interactions to reveal population density. A divergent color scheme and footnotes comparing state data to the U.S. median would further enhance its contextual effectiveness. This approach would make the data more accessible to economists, policymakers, and other stakeholders who rely on this information for decision-making.

## Step three: Sketch a solution

Based on my critique, I opted for a horizontal bar chart with states on the y-axis and population density on the x-axis. Each state is represented by two bars for different time frames, with hover-over interactions enabled to display the average age on each bar. The chart is sorted from highest to lowest in terms of population density and median age.

I chose this approach because I believe the audience would be most interested in quickly identifying the states with the highest and lowest values. Additionally, a bar chart effectively visualize the trends than a scatter plot. I ensured all the parameters like state labels, time-frame, median age and population density per square mile was covered in one chart. I also modified the chart title as - "State-wise Comparison of Median Age At First Marriage and Population Density"


<div class='tableauPlaceholder' id='viz1726674317614' style='position: relative'><noscript><a href='#'><img alt='State-wise Comparison of Median Age at First Marriage and Population Density ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;State-wiseComparisonofMedianAgeAtFirstMarriageandPopulationDensity&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='State-wiseComparisonofMedianAgeAtFirstMarriageandPopulationDensity&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;St&#47;State-wiseComparisonofMedianAgeAtFirstMarriageandPopulationDensity&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
  var divElement = document.getElementById('viz1726674317614');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>


## Step four: Test the solution

_Before you conduct your interviews, prepare a simple script.  Use this as a guide and as a way to take notes as you go forward. Come up with your own list of questions you want to ask for the selected visualization. Keep the questions broad so you can get the most value out of your feedback. Then, document answers to your questions here._

Questions to ask (modify these for your own interviews): 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Is there anything you find surprising or confusing?

- Who do you think is the intended audience for this?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 | Interview 2 |
|----------|-------------|-------------|
|          |             |             |
|          |             |             |
|          |             |             |

Synthesis: 

_What patterns in the feedback emerge?  What did you learn from the feedback?  Based on this feedback, come up with what design changes you think might make the most sense in your final redesign._

## Step five: build the solution

_Include and describe your final solution here. It's also a good idea to summarize your thoughts on the process overall. When you're done with the assignment, this page should all the items mentioned in the assignment page on Canvas(a link or screenshot of the original data visualization, documentation explaining your process, a summary of your wireframes and user feedback, your final, redesigned data visualization, etc.)._

