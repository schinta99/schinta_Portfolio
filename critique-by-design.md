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

1) Effectiveness Summary - 
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



What Stood Out:
1) The Trend: The graph hints at a potential trend, suggesting states with higher population density may have a higher median age for first marriage.
2) Accuracy of Data Points: The data points  specificity seems to accurately represent the relationship between population density and age.
3) Missing State-wise Information: Despite the title suggesting a state-wise analysis, there is no way to identify specific states in the scatter plot.

What Worked:
1) Highlighting a Trend: The scatterplot  indicates a possible correlation between states with higher population density and higher median age, which is valuable.
2) Simplicity: The simplicity of a scatter plot is fitting for conveying  specific and accurate information about population density and median age. It shows clustering of data points and potential correlation between age and population density. 

What Didn't Work:
Lack of State Identification: The absence of state labels makes it difficult to identify specific regions, limiting meaningful state-wise analysis as suggested by the title.
Axes Interpretation:  It’s difficult to read the exact values for both population density and median age, even if it is accurate.  The linear Y-axis for population density is crowded, making it hard to differentiate between closely packed data points.
Clarity and Annotations: The scatter plot lacks a trend line, which could help interpret patterns more clearly and guide viewers toward understanding the relationship directly instead of assuming a potential trend or correlation.
Vague Title: The title fails to clearly describe what the scatter plot represents, as it lacks direct information about which states the data points represent and their corresponding population densities.

What would I Do Differently:
Change the Title: Update the title to focus on the trend related to states with higher population density and higher median age, providing a clearer understanding of the content.
A possible suggestion could be - "States with Higher Population Density Show Higher Median First Marriage Age in the U.S."

Create a Bar Chart: Use a Horizontal bar chart with states on the Y-axis and median age on the X-axis. Add hover interactions to display population density for each state, making the visualization more informative and interactive.

Footnotes: Include footnotes comparing state data with the U.S. median age as a whole to provide a broader context for the data.

Diverging Color Scheme: Implement a grey divergent color scheme to represent different levels of population density visually, highlighting high and low values to make trends more apparent
The primary audience for this tool includes economists, statisticians, government bodies, policymakers, and lawyers. These groups may use the information to inform policy decisions, create laws, and understand demographic trends. For example, a higher median age for first marriage in certain states could have causation for fertility rates, healthcare expenditure, career paths. Understanding these patterns can help drive decisions around healthcare, social programs, and economic planning.

The current visualization is moderately effective for this audience as it does highlight the relationship between median age and population density. However, it fails to directly identify which specific states the audience should focus on. Without labels or identifiers for states, decision-makers cannot derive insights. 

To make this visualization more effective, it needs to include state labels, a more descriptive title, and clearer representation of data points.
The method used here was fairly successful in evaluating the data visualization. It provided more specificity than the "Good Charts" method, helping guide the critique in a clearer and more structured manner. The detailed breakdown into categories like usefulness, completeness, and perceptibility allowed for a more directed analysis and highlighted specific areas for improvement.

However, I found the 1-10 scale too broad, making it harder to distinguish between closely rated elements. A narrower range, such as a 1 to 5 scale, would be more appropriate. This change would allow for clearer judgments on whether the visualization is effective or not, providing a more straightforward answer about what works well and what doesn't.

Recommendations
Color: Implement a diverging color scheme, such as shades of grey  to represent different levels of population density. This would provide a visual cue about density levels and make trends more apparent.

Type of Visualization: Switch to a horizontal bar chart with states on the Y-axis and median age on the X-axis. This approach would make it easier to compare state-wise data and, with hover interactions, reveal population density details effectively.

To summarise the scatter plot suggests a potential trend between population density and average marriage age but lacks key elements like state labels, a clear title, and a trend line, thereby limiting clarity. To enhance effectiveness, a horizontal bar chart with state labels,  density details, and a divergent color scheme is recommended. This approach would make the data more accessible to economists, policymakers, and other stakeholders who rely on this information for decision-making.

## Step three: Sketch a solution

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

