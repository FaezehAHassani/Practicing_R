# Data visualisation

- a good visualisation helps to expose hidden data structure
- you can choose your visualisation layout based on your variable type
 - continuous variable: histogram, box plot or violin plot
 - bar chart for a few limited number of variables
 - proportional dependence by using stacked bar chart or pie chart
 - tree map, circle packing, or sunburst diagram for hierarchical data. in these plots, each area encoding (e.g. rectangle, circle or arc, respectively) is used to represent a numeric value
- sometimes you need to aggregate your data (i.e. check the number of occurrences of different categories)
 - for comparing between two continuous variables, the best choice is scatterplot. you can also make a scatterplot matrix to present multiple comparisons between pair of variables
 - for showing relation between a categorical variable and a continuous variable you can use violin plot for each pair or use faceting for each categorical variable
 - for assessing the relationship between two categorical variables, a heat map can be used
- representing data visually is called encoding that data. anyone can decode the visual data for interpreting the underlying values. The encoding of data can be based on position, length (e.g. stacked bar chart), area (e.g. bubble chart/ tree map), angle (e.g. pie chart), colour, and volume (e.g. 3D bar chart).
 - remember that your visual encoding should be **expressive**.
 - hue-satuartion-lightness (HSL) can be used to define colour in your visualisation. Hue: describe the colour, saturation: shows colour intensity in the scale of grey (0%) to hue (100%), lightness shows how bright is your colour in the the scale of black (0%) to shite (100%).
 - Cynthia Brewer's ColourBrewer can be accessed in _R_ through `RColorBrewer`.
   - Sequential, diverging, multi-hue, black/white are a few examples of possible ColourBrewer scales.
- leverage the human visual processing system (e.g. including a data point in different shape or colour from other data points)to direct user's attention => This is called preattentive processing
- try to avoid overlapping data bay changing opacity of overlapping data, use aggregating data to use for a better representation
- investing in aesthetics (i.e. beauty) of your graph by reducing the clutter.
 - remove visual effects
 - add a label for chart and useful x- and y-axis labels
