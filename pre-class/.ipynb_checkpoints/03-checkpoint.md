# CMSE 402: Data Visualization Principles and Techniques
## Lowell Monis
## Spring 2025 - Dr. Devin Silvia

***
### Pre-Class Assignment (Day 3 - January 21, 2025)

**Tasks:**

1. First, read and synthesize the assigned chapters from the two required readings. For each required chapter, (i) summarize the main points and (ii) list any questions that you have after doing the reading. In particular, focus on the key pieces of advice that the authors give about making visualizations that most clearly and accurately reflect the underlying data.
2. Next, compare the viewpoints set forth by Tufte and Cairo. In what ways is the advice that they give about "best practices" in data visualization similar, and in what ways do they differ? What, if any, of their advice seems contradictory?
3. Finally, apply the best practices you have detailed to a "bad" plot. This plot can be one of the ones that you selected for an earlier pre-class assignment, one that was put forward by one of your classmates, or a new one that you have found online. Include that plot in your writeup (either embedded directly in the file or the same directory). Describe how you would change this figure to make it a "good" figure, using the best practices described by Tufte and Cairo (you don’t have to do it, just explain how you would). Make sure to be as specific as possible.


**Assigned Readings:**

1. The Visual Display of Quantitative Information, 2nd Ed., by Edward Tufte, Chapters 4-6.
2. The Truthful Art: Data, Charts, and Maps for Communication, by Alberto Cairo, Chapters 1-2.

***

#### Summary and Further Inquiry

##### Cairo, Chapter 1

In this chapter, the author attempts to define the common terms he uses in this book in his vision. The book is written with these definitions in mind. The focus of this book is said to be on communicative visualizations and not artistic ones. The author defines a chart as a display in which data are encoded with symbols, popularly on a Cartesian plane. Here, "plot" is the synonym of "chart". Following this, the author differentiates between the terms graph and chart/plot. He agrees that both terms can mean the same thing, but he advises against calling a visual chart a graph to distinguish between visualizations and graph theory. He then talks about infographics. While he mentions that these can be colorful and fun the goal of informing the public is paramount. Here, you need not show all gathered information but just relevant bits supporting the point that is being made. The term "news application", as defined by ProPublica, is then explained in excruciating detail. This chapter does not contain much, but the author does emphasize that the most important rule for visualizations is that they must be illuminating, in the words of the author. Decoding the information conveyed through visualizations is as crucial as encoding it. This ties the success of a piece of visualization to how well it is understood by the audience. Questions: What specific design elements improve decoding for general audiences versus technical ones? How do cultural differences in visual perception impact the effectiveness of visualizations?

##### Cairo, Chapter 2

In short, effective visualizations possess five core qualities: truthfulness, functionality, beauty, insight, and an ability to enlighten. The data that one presents must be honest and accurate, while the visualization technique used achieves its purpose effectively. While this initially seemed to be secondary to the author in the first chapter, the author emphasizes that aesthetic appeal contributes to how a viewer engages with the visualization. All of these lack any standing if the visualization does not inform or enlighten the reader. Question: In real projects, how can we juggle between aesthetics, accuracy, and functionality? Can a visualization focus on more than one of these five qualities?

##### Tufte, Chapter 4

Here, Tufte talks about the data-ink ratio. He says that one must strive to maximize data-related elements while minimizing non-essential elements in visualizations. The next point is to avoid "chartjunk,", such as unnecessary decorations or excessive colors, as these detract from clarity. Questions: Is there ever a scenario where chartjunk might positively influence a visualization? How does data-ink ratio apply to interactive visualizations?

##### Tufte, Chapter 5

Once again, Tufte repeats that graphical integrity is paramount: representations must not distort the truth. Chartjunk is defined as the unnecessary, decorative elements in visualization, such as excessive use of colors, 3D effects, or ornamental patterns, that detract from clarity. Tufte emphasizes that the inclusion of chartjunk not only distracts the viewer but can also mislead them by distorting the interpretation of data. Examples of chartjunk include heavy gridlines, redundant labels, and superfluous embellishments like pictograms or icons that don't serve a functional purpose. Instead of adding non-essential design elements, he says that the focus should be on simplicity, where every visual component contributes directly to understanding the data. His key advice is to ensure all visual elements enhance data comprehension rather than detract from it.

##### Tufte, Chapter 6

The data-ink ratio is the proportion of a graphic's ink dedicated to representing data versus non-essential elements. Tufte asks the reader to aim to maximize the data-ink ratio by eliminating redundant or decorative features that do not contribute to data presentation. He emphasizes that graphical design should prioritize simplicity and clarity, allowing viewers to focus on the data itself.
Tufte introduces design principles such as removing unnecessary labels, minimizing gridlines, and avoiding redundant text or symbols through plot examples.

#### Comparing Viewpoints

##### Similarities

Both emphasize the need for sincerity in visualizations. Not being clear is being dishonest to your viewer. They agree that aesthetics should support, not detract from the message. Both agree that what Tufte calls "chartjunk" must be avoided since it reduces interpretability. Cairo encourages experimentation with innovative forms, while Tufte advocates for traditional, proven designs like sparklines and small multiples. Cairo emphasizes the balance of aesthetic beauty with functionality, while Tufte prioritizes function over form. I would say that Tufte's strict adherence to the data-ink ratio may not always align with Cairo's principle of creating visually engaging content.

##### Differences

Cairo integrates storytelling and engagement as key elements, while Tufte maintains a stricter focus on minimalism and the "data-ink ratio." 

#### Application of Concepts

![Plot](03.png)

By Tufte's principles, I believe there is a lot of chartjunk in this plot. I believe the unlabeled points in this plot do not give the viewer any new information. Instead, the following, or a combination of the following, can be done:

Option 1: Get rid of the unlabeled points.
Option 2: Apply a color scheme and use a legend to label instead of messily labeling on the chart itself.
Option 3: Demonstrate the relative change by using a line to compare 2024 and 2019 levels rather than a scatter plot. The regression line is unnecessary here, and if the regression line is the main point of the plot, this method loses efficacy.
