---
Course:Dashboards, Scorecards & Visualizations
Title: ""Self-Study-Project - Part-1"
Author: "Sonal Agrawal"
Date: "4/12/2019"
Output: github_document
---

## Why is data visualization important?

Data Visualization is important not only to explore and analyze data in order to identify hidden patterns. But also to present and communicate these findings and insights to the intended audience. In other words, data visualization helps in putting across an important point which can be an insight, an observation, awareness or a call to action to make a decision. 

When a data visualization is designed, it is done so keeping the audience in mind. However, for the same creator, the objectives can be different based on the audiences. For example, a climate scientist can design a visualization of historical temperature data for both disseminating scientific knowledge within the climate science community or communicating to policymakers about key indicators and impacts. In the first case, the goal is exploratory analysis, while in the second case, the goal is presentation of results. Owing to these differences in who creates a visualization and who the audience is, the scenarios can involve very different approaches and techniques(Ref-https://research.tableau.com/sites/default/files/Kosara-C4PGV-2016.pdf).

## How to evaluate a visualization?
In today’s world where data really matters, it is important to create charts that communicate with the intended audience effectively and clearly. But, it isn’t always the case. From cluttering the charts with excessive information to communicating a completely inaccurate idea, there are many ways a visualization can fail to serve its intended purpose. These articles(Ref-https://www.perceptualedge.com/articles/visual_business_intelligence/data_visualization_effectiveness_profile.pdf) & (Ref-https://research.tableau.com/sites/default/files/Kosara-C4PGV-2016.pdf), discuss various criteria to gauge the effectiveness of a data visualization. Key parameters that can help us  understand the same are following:

* **Usefulness**: Provides the reader with information that is useful, unexpected and invites a different perspective of the data. For eg., a visualization can be eloquent in every way, but if it communicates information that is of no value, it is ineffective.

* **Completeness**: Includes all of the information along with the context, that’s needed to produce the intended level of understanding in the right amounts, but not more. For eg., a chart which showcases comparisons, or conveys the message by giving a historical context will result in a better understanding of the data.

* **Clarity**: Displays information in a manner that is easily understandable by the human eye and brain with minimal effort and appropriate precision. For eg., forcing people to compare the sizes or color intensities of two circles, which is somewhat difficult and imprecise, when the positions or lengths of objects could have been used instead, makes it ambiguous.

* **Emphasis**: Uses proper labelling, grids and annotations if necessary, which help emphasize the intended message. Overdressing the charts with unnecessary information makes the decoding process inefficient, by increasing the non-data ink. For eg., use of excess color, multiple comments and abuse of special effects are some of the key mistakes that lessen the effectiveness of a chart.

* **Truthfulness**: Degree to which it is accurate and valid. Accuracy is a measure of reliability and appropriate precision. Validity indicates how well something represents what it claims. For example, a bar chart which doesn’t start at zero or an overstretched line chart results in an overblown or understated message which might mislead the reader. 

* **Memorability**: Memorable enough to ‘stick,’ at least for a short time to inspire engagement or action to take a decision. For eg., an effective chart will leave an imprint on the reader’s mind of important data values, key trends, overall message or even the unusual visual design used, which might inspire the intended action.

This is how our data visualization evaluation framework looks like:

![figure](https://github.com/agrasonal/Visualizing-Climate-Change/blob/master/Images/Evaluation_Framework.png)

This framework can be used to access the effectiveness of a chart by scoring it across all six parameters and calculating an overall effectiveness score (OES). This score might prove helpful in cases where we are comparing the effectiveness of multiple charts in conveying an interlinked story.

Let’s take a scenario to understand the usefulness of the above mentioned framework in assessing the effectiveness of visualizations.

<h2>**Case Study - Climate Change Caused by Human Activity**</h2>

Earth’s climate is undergoing changes faster than ever. The global average temperature has been constantly rising at an alarming rate having an adverse effect on the earth’s ecosystem. There is unanimous agreement on the fact that climate change has primarily been caused by the human activities like burning of fossil fuels such as oil and coal, which releases CO2 and other greenhouse gases into the atmosphere. These gases when released trap sun’s heat within the atmosphere, resulting in different kinds of effects on our ecosystem like, rising temperatures,  rising sea levels, unpredictable weather events like wildfires, droughts, etc.

These changes have been so obvious that climate change is a topic of constant debate among environmentalists, media, scientists, governments, etc., and is frequently emphasized upon in newspapers, articles, magazines, websites, etc., in the form of various visualizations.  

Here are a few charts emphasizing various causes and effects of global warming that we will evaluate using our framework to understand the effectiveness of these visualizations in conveying the intended message.

**Graph-1: Current CO2 level in the atmosphere**

![figure](https://github.com/agrasonal/Visualizing-Climate-Change/blob/master/Images/Global-CO2-levels.jpeg)
(Image Ref: https://climate.nasa.gov/evidence/)

Usefulness |	Completeness	| Clarity	| Emphasis	| Truthfulness	| Memorability	| Overall Score
-----------|----------------|---------|-----------|---------------|---------------|---------------
1 | 1 |	1 |	1 |	1 |	1 |	**6**

This graph rates extremely well on overall effectiveness with an overall score of - **6**. 

Since CO2 emissions is a major factor causing global warming, it is useful for a reader to understand this change. In fact, by setting a historical context of year 1950 and comparing it with the current level, it gives the reader a good idea of the seriousness of the situation. By using a simple line graph, designer has very easily conveyed this message to the reader. Also, use of gridlines, different colored text labels highlighting current and 1950 levels and clean background is helping in emphasizing the key message of this graph. Also, since it covers a complete timeline starting 400,000 years before today, it seems reliable and accurate. And, it is not just the CO2 levels that capture the reader’s attention, but also the background of outer space setting a context to the graph that is surely going to stick in the reader’s mind for a long time.

**Graph-2: Global levels of greenhouse gas emissions by gas**

![figure](https://github.com/agrasonal/Visualizing-Climate-Change/blob/master/Images/global-ghg-emissions.png)
(Image Ref: (Ref - https://www.epa.gov/climate-indicators/climate-change-indicators-global-greenhouse-gas-emissions)

Usefulness |	Completeness	| Clarity	| Emphasis	| Truthfulness	| Memorability	| Overall Score
-----------|----------------|---------|-----------|---------------|---------------|---------------
1 | 0.5 |	1 |	0.5 |	1 |	0.5 |	**4.5**

This graph rates considerably high on overall effectiveness with an overall score of - **4.5**. 

This graph conveys the underlying message very clearly that global level of greenhouse gas emissions is continuously increasing over the years. By analyzing data every 5 years, it is probably missing out on any unexpected changes that might have occurred between this window of 5 years and hence, is incomplete. With the use of a simple visualization type, it is conveying the message clearly. However, use of stacked bar graphs is making it difficult for the reader to gauge changes in the levels of gases other than CO2. Also, use of a legend distracts the reader to some extent. The y-axis starts at zero and x-axis covers a span of years, making it fairly accurate and reliable. Although, it does portray the key message clearly, it doesn’t however communicate it in a way that is bound to stick in the reader’s mind for a long time.    

**Graph-3: What are the sources of greenhouse gas emissions in USA by sector?**

![figure](https://github.com/agrasonal/Visualizing-Climate-Change/blob/master/Images/greenhouse-gas-sources-in-the-us.jpg)
(Image Ref: https://www.climatecentral.org/gallery/graphics/greenhouse-gas-sources-in-the-us)

Usefulness |	Completeness	| Clarity	| Emphasis	| Truthfulness	| Memorability	| Overall Score
-----------|----------------|---------|-----------|---------------|---------------|---------------
0.5 | 0 |	1 |	1 |	0.5 |	0 |	**3**

This graph rates low on overall effectiveness with an overall score of - **3**.

By just stating the division of sources of greenhouse gas emissions in USA, it is not communicating anything unexpected to the reader. It conveys a message which is pretty much common knowledge and without a context (like change over the years), it doesn’t make sense and looks incomplete. However, since pie charts are very easy for a reader to understand, this chart is pretty intuitive and straightforward. With proper labels, bold color choices, reasonable text sizes and self explanatory titles, it lays emphasis on the message very clearly without any distractions. Also, lack of information on represented year or a range of years, it seems inaccurate and less trustworthy. Also, there is no memorable key takeaway from this chart for the reader that might inspire an action.

**Graph-4: Global Temperature & Carbon Dioxide**

![figure](https://github.com/agrasonal/Visualizing-Climate-Change/blob/master/Images/globaltemp_vs_co2.jpg)
(Image Ref: https://www.climatecentral.org/gallery/graphics/co2-and-rising-global-temperatures)

Usefulness |	Completeness	| Clarity	| Emphasis	| Truthfulness	| Memorability	| Overall Score
-----------|----------------|---------|-----------|---------------|---------------|---------------
1 | 1 |	0.5 |	0.5 |	1 |	0.5 |	**4.5**

This graph rates high on overall effectiveness with an overall score of - **4.5**. 

By informing the reader about the rising global temperature with increasing CO2 levels, it is conveying the underlying message very well. Also, by comparing the change in temperature and CO2 level across a wide range, it is providing a valid context to the chart. However, by combining two messages in the same graph, it is comparatively less intuitive and requires extra attention. This combined with two separate y-axes for temperature and CO2 level, takes the emphasis away from the key message. However, by including a timeline starting way back into past, it draws a pretty reliable comparison. Lack of any comments or labels highlighting the key message of this chart doesn’t leave the reader with any thoughts or inspiration.

**Graph-5: Climate Models vs Observations**

![figure](https://github.com/agrasonal/Visualizing-Climate-Change/blob/master/Images/Humans-vs-climate.jpg)

(Image Ref: https://friendsofscience.org/index.php?id=680)

Usefulness |	Completeness	| Clarity	| Emphasis	| Truthfulness	| Memorability	| Overall Score
-----------|----------------|---------|-----------|---------------|---------------|---------------
1 | 1 |	0.5 |	0 |	1 |	0.5 |	**4**

This graph rates high on overall effectiveness with an overall score of - **4**. 

By comparing the observed vs calculated global temperature, it conveys a very interesting and unexpected message that the panic around climate change due to human activity is probably unjustified. It includes a broader view on the problem by providing a timeline starting 1975 and includes various sources which were used to calculate surface temperatures. However, this chart is pretty cluttered with multiple labels, arrows, irregular use of colors and text sizes, etc., and hence, less effective in drawing the emphasis on the key underlying message. Since it refers to use of credible scientific models which are commonly used to measure surface temperatures, it is fairly reliable. However, since the key message is lost between the clutter, it is not powerful enough to leave a visual imprint in the mind of the reader.

<h2>**Conclusion**</h2>

After analyzing the above five graphs, we can say that effectiveness of a chart depends on multiple parameters where each parameter plays its own role. Since these parameters are subjective, depending on the intended audience and purpose, lower scores for some parameters like ‘Memorability’ and ‘Emphasis’ are still acceptable. However, parameters like ‘Usefulness’ & ‘Context’ are utmost important with no room for negotiation. This is because no matter how beautiful a chart looks, if it isn’t addressing the needs of the intended readers and inspiring an action, it is of no value to them. On the contrary, if it is intelligently designed to speak to a targeted audience, they will be willing to make an extra effort to decipher the chart even if it isn’t scoring well on ‘Clarity’ and ‘Emphasis’. 

So, to sum up:
* Visualizations should be customized to a specific audience and able to address their needs. This is a case where one size does not fit all.
* Context plays a key role in better understanding and building trust, leading to an action.
* Choosing the right chart type depending on the intended audience is important for easy interpretability and acceptance.
* Overdressing leads to confusion and distractions and should be avoided at any cost. It leads to greater simplicity and enhances focus on the underlying message.
* Data should be presented accurately in order to help the reader make informed choices and inspire the right action.
* Visualization should be engaging enough for the reader to retain the key information and recall it later when needed.

