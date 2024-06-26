
Digital images for scientific figures may be [vector graphics](https://en.wikipedia.org/wiki/Vector_graphics), [raster graphics](https://en.wikipedia.org/wiki/Raster_graphics), or a combination of the two. Vector graphics are defined with nodes and curves that run through them, whereas raster graphics generate images as a grid of pixels. Graphics software tends to emphasize functionality for manipulating one over the other. For example, Photoshop is primarily designed to manipulate raster graphics. Most of the images used in a scientific paper are vector graphics, with perhaps some photos or heatmaps embedded as raster graphics. So, our workflow here revolves around software intended for vector graphics.

# Software
- [Adobe Illustrator](https://www.adobe.com/products/illustrator.html). Industry standard app for editing vector graphics. However, Adobe's licensing is often prohibitively expensive and can only be acquired through a subscription (at different times, UCI has offered institutional licenses). I
- A much more affordable alternative is [Affinity Designer](https://affinity.serif.com/en-us/designer/#top). Unfortunately, compatibility between these apps is not great and so it mades sense to stick with one or the other for a project.
- Powerpoint or Keynote may be used in a pinch, but their design emphasizes user-friendliness over functionality. It does not take long to hit the limits of their utility when generating scientific graphics.

# Workflow

In our lab, most visuals for a manuscript originate from code that performs data analysis. The code can attempt to make the graphs pretty, but we have yet to publish a figure that did not require manipulating the figures with graphics software. It is tedious to get code to generate publication-graph figures and in some cases there are no commands to generate certain visual elements. Plenty of investigators are less careful about their figures, but we think that figures are at least as important as the writing of a manuscript and that their careful construction pays dividends for communicating your science.

With few exceptions, the file format that you want to export to should be one that supports vector graphics. These include eps, ai, and svg. I have found svg to be the best option from Matlab and it works well from R as well. pdf might also work, but you need to be sure that the software does not rasterize the graphics.

To create a figure, you will want to specify an artboard with the width that is one of the options recommended by your target journal. The height is generally flexible and can be adjusted later. Options usually include full-page or half-page widths. The reason to be specific about the width is that you want to control the scaling of items as they will appear on the page in your final article. This includes the correct font size, line weights, and symbol sizes in your graphs. If you embed a figure in your manuscript as a different scale from your artboard, they it will fail to reflect the desired size of everything. While you are investigating the author's guidelines for the journal, you should also note the recommended font and font sizes by the journal. Not all journals are explicit about these parameters, but you can get a sense of what they want by downloading some recent papers published by the journal. You might as well conform to their formatting early in the figure-making process. When working in Illustrator, I generally save the figure file as a pdf. That makes it so you don't have to export for a Latex, Keynote, or Powerpoint document and that format has good compatibility with Illustrator.

Graphics generated by your code can be opened up in Illustrator and then copy and pasted into your figure document. That process is easier than trying to reformat the exported file into a figure file.


# More
- [Getting Started with Illustrator](Illustrator.md)
- [Formatting figures](formatting.md)