# One of the basic operations that we might want to do on a set of data is find its minimum or maximum. We can even find the minimum or maximum of values that aren't numbers, such as Strings, as long as Python has a way of comparing two strings (Python says that one string is "less than" another if it comes before it alphabetically). This operation is so common that Python has a built-in function to do so.

# max returns the biggest element in a set of data and min returns the minimum.

# For example:

print (min("cat", "dog", "iguana", "anteater", "hedgehog", "fish", "aardvark"))

will print out the minimum based on alphabetical order (so it would print out aardvark).

We can also plot data sets. Python doesn't come on its own with plotting functions, but the simpleplot module in your programming environment does.

# Here is an example of plotting that draw lines between coordinate points.

import simpleplot

dataset1 = [(1, 4), (1, 5), (2, 7), (4, 9)]

dataset2 = [(1, 2), (2, 7), (2, 5), (7, 6)]

simpleplot.plot_lines('Sample', 400, 300, 'x', 'y', [dataset1, dataset2], True, ['dataset1', 'dataset2'])

The first parameter ('Sample') is the title. The second and third are the width (400) and height (300) of the graph. The fourth and fifth label the x and y axes. The next parameter contains our x and y values. The last two are optional. The True in this example says that we want to indicate the points on our graph and the last parameter gives a legend for the graph.

Other Features of Simpleplot

The simpleplot module can do more that just plot lines on a graph.  As you saw in the lesson, you can modify the x- and y-axis labels, change the title of your plot, and make the plot smaller or larger.  However, you can also change the format of the graph and alter how the data is displayed. The document below explains the commands available in the simpleplot module in greater detail. Try rewriting your code to use the simpleplot.plot_bars() command outlined in the document, and see what happens when you run your program!

Simpleplot DocumentationLinks to an external site. https://files.projectstem.org/CSFundamentals/CSFundamentalsCourseResources/CourseDocuments/2.7_Simpleplot_Documentation.pdf
