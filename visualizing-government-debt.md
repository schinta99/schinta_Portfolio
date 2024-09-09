| [home page](README.md) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt



## Part one: Working with web-based visualization tools and data

### Government Debt Bar Chart
![funny dog picture](export-2024-09-09T04_05_48.684Z.png)



## Part two: Working with Tableau



<div class='tableauPlaceholder' id='viz1725875674202' style='position: relative'><noscript><a href='#'><img alt='Global Government Debt-to-GDP Ratios: Trends and Comparisons by Country ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalGovernmentDebt-to-GDPRatiosTrendsandComparisonsbyCountry&#47;DataVisualizationofGovernmentDebtRatio&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GlobalGovernmentDebt-to-GDPRatiosTrendsandComparisonsbyCountry&#47;DataVisualizationofGovernmentDebtRatio' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gl&#47;GlobalGovernmentDebt-to-GDPRatiosTrendsandComparisonsbyCountry&#47;DataVisualizationofGovernmentDebtRatio&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>
<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1725875674202');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>

Steps in Tableau:
Dataset Loading: I imported the OECD dataset and set the Time column to Date.

Creating the Highlight Table: I placed Time on Columns, Value on Rows, and Location on the Marks card to differentiate by country.

Sorting: I sorted countries by descending average debt-to-GDP ratio to prioritize those with higher debt.

Color Customization: I used the Orange-Blue Diverging palette, setting 100 as the center. This choice effectively highlighted the divide between countries with debt above or below 100% of GDP.

Filtering: I removed countries with missing data (e.g., Colombia) to maintain clarity.

Final Touches: I added a clear title and ensured hover-over interactions for more detailed insights.

After sharing it to Tableau Public, I copied the embedded code from Tableau Public and pasted it in this Markdown file. I ensured the formatting was consistent for correct rendering. 

Observations:
Key Insights: Japan and Greece showed consistently high debt-to-GDP ratios, while countries like Luxembourg had consistently low ratios.

Diverging Colors: The Orange-Blue palette made it easy to distinguish between countries with higher or lower debt. Diverging colors are useful for highlighting critical thresholds like 100%.

Heat Map: It is a comprehenive chart visualization, coupled with diverging colours makes it easier for the audience to view and gain insights from the visualization. 


## Part three: create your own visualization

_Create another data visualization using the same data used earlier. DO NOT submit something that's just a minor modification of one of the visualizations already covered here. So, don't just modify the colors or labels of one of the earlier examples and call it good, or submit a slightly modified bar chart.  Instead, see what you can come up with on your own, and spend some time to try and create something that tells a story about the data._

_Summarize in a paragraph or two about the different methods of visualization, and how they compare / contrast to one another. Make sure you include all source information and explain the data well.  Talk about why you chose the third data visualization.  Be specific - keep your writeup relevant to the assignment, and avoid jargon-filled language that doesn't say anything useful._

_It's a good idea to go back and review your work.  Could someone follow your process and understand what you did?  Do you need to further connect any of the sections with a bit of text?  Is it something you'd be happy to have as an example of your work from the class?_


<div class='tableauPlaceholder' id='viz1725850766722' style='position: relative'><noscript><a href='#'><img alt='Debt-to-GDP Trends in North America ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-GDPTrendsinNorthAmerica&#47;Debt-to-GDPTrendsinNorthAmerica&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Debt-to-GDPTrendsinNorthAmerica&#47;Debt-to-GDPTrendsinNorthAmerica' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;De&#47;Debt-to-GDPTrendsinNorthAmerica&#47;Debt-to-GDPTrendsinNorthAmerica&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /><param name='filter' value='publish=yes' /></object></div>                
<script type='text/javascript'>                    
    var divElement = document.getElementById('viz1725850766722');                    
    var vizElement = divElement.getElementsByTagName('object')[0];                    
    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
    var scriptElement = document.createElement('script');                    
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
    vizElement.parentNode.insertBefore(scriptElement, vizElement);                
</script>





