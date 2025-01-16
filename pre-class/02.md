# CMSE 402: Data Visualization Principles and Techniques
## Lowell Monis
## Spring 2025 - Dr. Devin Silvia

***
### Pre-Class Assignment (Day 2 - January 16, 2025)

**Task:** Thoroughly read your assigned materials. For each chapter in Tufte, or for the entire Wickham paper, write a paragraph that summarizes the key points from that reading. What message is the author trying to convey?

**Paper Assigned:** A Layered Grammar of Graphics, by Hadley Wickham

**Prompts:** Make a note of the "grammar" described by the author: What are the components of a plot? What are the implications of this grammar? How is this grammar used to both create and judge plots?

***

The paper provides a systematic framework for creating and understanding statistical graphics. It decomposes graphics into elementary components, what the author calls "grammar": data mappings, geometric objects, transformations, scales, and coordinate systems. This allows for layered composition, enabling users to construct complex visualizations with progressive refinements. The embedding of the grammar in `R` through `ggplot` offers increased flexibility and potential extensibility. This article highlights how grammar can be used to build, extend, and evaluate stories and thus create a foundation for more effective data visualization practices.

**Components/Grammar of a Plot:**

1. Data and Aesthetic Mappings (`aes()` in `ggplot`/`ggplot2`). This is how we link data to visual attributes like the axes, shape, size, color, etc.
2. Geometric Objects. On `ggplot`/`ggplot2`, `geom` functions define the type of plot. These include scatter plots, line plots, bar plots, histograms, etc.
3. Statistical Transformations. A layer that summarizes or transforms given data. An example could be multiplying GDP per capita with the population to find GDP from the given data that does not provide raw GDP data.
4. Scales. This can be color gradients and axes ranges. We map data values to visual representation this way.
5. Coordinate Systems. Here, we define the spatial layout of the visualization. Are we using a Cartesian plane? Or are we using polar coordinates? Will there be a log scale?
6. Faceting. This is a fancy term for multi-panel visualizations and subplots.

**Implications and Usage of this Grammar:**

The grammar creates a sort of framework for plot construction. We can also evaluate graphics based on alignment with established principles and style guides like this one. This ensures a sort of uniformity with specific disciplines or methodologies, as well as global clarity and effectiveness.

The grammar also supports the iterative development of visuals, discovery of new types of visualization, and customization for specific datasets.