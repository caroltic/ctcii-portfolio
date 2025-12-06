| [home page](https://caroltic.github.io/ctcii-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Consumer Spending Distribution by Category Across Generations

## Step one: the visualization

https://finance.yahoo.com/news/chart-reveals-huge-difference-millennials-201133732.html?guccounter=1

I selected this particular data visualization because it is directly relevant to everyday consumer behavior, and it presents data that people typically don't have access to for comparison on a daily basis. The chart first caught my attention because it attempts to show how different generations spend across major categories such as groceries, restaurants, and gasoline. Since generational spending habits are often discussed in my own family by my grandparents, parents, and even my older cousins, this dataset would be significant for me to analyze. It’s also the type of chart people might easily come across in social media posts or news articles, so it felt important to evaluate whether it was actually communicating its message effectively or not.

Another reason I chose this visualization is that I immediately saw clear opportunities for improvement. In the article featuring the chart, the authors aimed to highlight the differences in spending behavior between Millennials and older generations, particularly their parents. However, the stacked bar chart they used didn’t emphasize Millennials at all, making it difficult to see the point the article was trying to make. This allowed me to critique a real-world example that discusses a highly relevant and everyday topic, yet still suffers from poor data visualization choices.

## Step two: the critique

The top two categories stood out to me since the red and orange bars are the brightest colors in the graph, and they also happen to be the largest segments overall. The ordering of the generation names from youngest to oldest also caught my attention.

I really liked the percentage labels on each category and the choice of white text, because it made the values stand out clearly against the different colored bars. I also appreciated how the color legend on the side matches the exact order of the categories in the chart, which makes comparison much easier. These two aspects worked really well, in my opinion.

In terms of what didn’t work well, I believe the color scheme for the categories is too similar; there are two reds and two blues, which makes the overall visual feel less pleasant and a bit confusing. On top of that, using stacked 100% bars makes it hard to compare categories across generations. It takes a while to track which color represents what when you jump between generations. For example, comparing Pharmacies and Restaurants across Generation X and Traditionalists requires a lot of eye movement. More broadly, there are simply too many colors in the graph, making it easy to lose track and forcing the audience to repeatedly reference the legend.
The title, axis choices, and labeling also make the visualization less effective. The chart doesn’t label the axes at all, and the title is very broad, without giving the audience a specific focus. Even though the generations are ordered by age, the category percentages are not, where smaller categories end up stacked in the middle while larger ones are scattered at the top and bottom. This makes it easy for viewers to lose track of where the major comparisons should be.

I believe the primary audience for this tool is consumers of financial and market news, or simply people from the four generations mentioned who are curious about their own spending behaviors.

I think this visualization is partially effective, but not entirely. Even though the chart is visually bold and eye-catching, and the percentage labels inside each category make it easier to see the values without having to calculate anything, there isn’t a clear main point the chart is trying to convey. For example, if a viewer wanted to compare the most-spent categories between Generation X and Traditionalists, it would take them a long time to figure out because the stacked 100% bar chart makes comparisons harder, especially given the overwhelming number of colors.

Based on my critique, I will first focus my redesign on the axes. I believe the percentage spent should be on the x-axis, while the y-axis should list the different spending categories, with the generations differentiated by color within each category. Overall, I’m planning to transform the stacked bar chart into grouped horizontal bars so I can create a clearer visualization with better axis labeling and more intentional axis choices.

My second focus for the redesign is color. Since I’m switching to horizontal bars and using color to represent generations, I need four colors that are distinct but not visually overwhelming. My idea is to use green, yellow, blue, and orange to clearly differentiate the generations while still keeping the chart clean and easy to read.

My third focus is changing the title and adding a meaningful subtitle to express the story I want to tell. For example, I can highlight the contrast between Millennials and Traditionalists in the subtitle to guide the viewer toward the generational differences I want to emphasize.

I’m excited to try new things with the axes and color emphasis. Even though I want each of the four generations to have its own distinct color, I’m also curious to try a version where two generations are grayed out so the other two stand out more. I want to see which approach creates the strongest comparison and makes the story clearer.

## Step three: Sketch a solution

First Sketch before in-class critique:

https://public.tableau.com/app/profile/carol.chen8111/viz/GenerationSpendingsFirstVersionSketchBeforeClass/FirstVersion?publish=yes

Second Sketch used for in-class critique:

https://public.tableau.com/app/profile/carol.chen8111/viz/GenerationSpendingsOriginalSketch/Version2?publish=yes

## Step four: Test the solution

Questions to ask: 

1) What did you like about my data visualization at first glance?
   
2) Is there anything you find unclear or needs improvement?
   
3) Does the color coding look overwhelming? Do you think there is anything else that I can try doing?
   
4) Any additional comments in general?


Interviewee 1: Early 20s, MEIM Program student currently studying data visualization.

1) This is a really interesting data!! I liked how I can compare each generation by categories. Yours are much easier to read compared to the original one!
   
2) Some of the bars have percentage labels while others don’t. Since the x-axis already has clear labels, it might look cleaner to show percentages only for the items you really want to emphasize.
   
3) Maybe you could highlight the bar for the generation that spends the most in each category by using a stronger color, and keep the other bars in gray or a more muted tone? That could make it easier to see which generation spends the most for each spending category.
   
4) For the y-axis, the year information for each generation could stay in the legend only — you might not need it on the graph itself.

Interviewee 2: Early 20s, MEIM Program student currently enrolled in a data visualization class.

1) It looks great at first glance.
   
2) Some bars does not have percentage labels, it is unclear why some are not labeled and some are, there isn't a story told by the labels from my understanding.

3) The colors you chose are excellent, the bars are easy to spot and identify; You can color code the generation's names as well.

4) You should remove the color legend because what each color represents is already very clear in your chart.

Synthesis: 

The percentage labeling issue appeared in both interviewees’ observations, so I learned that Tableau was glitching in a way I hadn’t fully noticed before their comments. They also both pointed out that my color coding looked great, but after hearing their suggestions and critiques, I realized that even though my colors were visually appealing, they weren’t actually telling a story. In other words, the colors were clear, but they didn’t add meaning.

Based on this feedback, I believe the most important design change for my final redesign is to adjust the color legend so that it emphasizes the two generations being compared in the article. By highlighting only those two generations and muting the others, the visualization will not only appear cleaner but also better guide the audience toward the main point of the analysis.

## Step five: build the solution

My final solution link: 
https://public.tableau.com/app/profile/carol.chen8111/viz/GenerationSpendingsFinalSolution/Version2?publish=yes

In my final solution, I incorporated both interviewees’ recommendations and made sure that all labels were complete, with no missing percentage signs. I also experimented with changing the color scheme by coloring Millennials and Traditionalists in yellow and blue while turning the other generations gray. This change worked well because it allowed me to clearly emphasize the two generations that the article focused on, without overwhelming the viewer with too many bright colors. By shifting the color emphasis to just two generations, the story becomes much more obvious and the viewer knows exactly where to look. 

One major change I made from the original chart was switching the visualization type entirely. The original article used a stacked 100% bar chart, which made it difficult to compare categories across generations. In my redesign, I changed it to a horizontal grouped bar chart, letting each generation to be compared side by side on a shared baseline. This immediately made the graph more readable and more meaningful. I also added clear axis labels so viewers understand exactly what the x-axis represents (percentage of spending) and what the y-axis represents (the spending categories), which was missing in the original chart. Making this switch helped turn a visually overwhelming chart into one that supports clearer comparisons and easier interpretation.

I also changed the title and added a meaningful subtitle to help guide the audience toward the story I wanted to highlight. The original title in the article was very broad. It didn’t give the viewer a specific point to focus on, so I wrote t to reflect the contrast between younger and older generations. Moreover, I also labeled the birth year ranges for each generation directly in the legend. For example, I listed Millennials next to (1981–1996), so viewers who are not familiar with the generation names don’t have to guess or look it up themselves.

## References
DATA SOURCE: Bank of America Merrill Lynch

## AI acknowledgements
I used AI to search for the birth year range of the different generations.

