# Getting started with Illustrator

## Starting out
- You can save yourself time by seeking out lessons on the basics of Illustrator. At first glance, Illustrator looks like a lot of software such as powerpoint. However, moderate use will reveal some of the complexity inherent to powerful graphics software. Good options for introductions include many options among YouTube videos. It's a good idea to play along with an instructional video by making your own graphics in the program.
- There is a vast set of functions in Illustrator that you may never need to use, so don't feel like you have to read a book or watch hours of YouTube before you get started. 
- General layout. You'll first want to orient yourself with respect to where to find the key tools and properties for your graphics. You can make items appear or disappear by selection in the "Window" menu (at least in MacOS).

## Essential concepts
Here are some concepts that you will want to keep an eye on as you start to experiment with Illustrator:
- Stroke vs. Fill. Each vector graphic may have a Stroke and a Fill. The stroke has a weight and color and the fill has a color or pattern. Both may be made transparent.
- Anchor points and bezier curves. Vector graphics consist of these items. You'll want to figure out how to create them with the Pen tool and then manipulate them with the Anchor Point tool.
- Grouping items. You can group by selecting multiple items and then selecting Object:Group from the pulldown menu (or right-click). Double-clicking on grouped items allow you to edit items within a group. Grouping is helpful to isolate some items from the rest. Quite often, items will be imported in groups, so I often select everything and then ungroup items to make them easier to edit.
- Layers. All elements in your graphics reside on a layer. By default, all graphics reside in a single layer, but you can add more layers as your graphics become more complicated. 
- Align and distribute. Selecting multiple items will bring up these functions for arranging items relative to one-another.

## Toolbar items
Toolbar items (on the left, by default). Here are the ones you will need to use a lot. The other may prove useful down the road, but skip them for now.
- The Selection vs the Direct Selection tools. You'll want to understand the key differences between these.
- The Pen Tool. What happens when you click on the graphic or click and drag with this tool? Figure out what the Anchor Point Tool (long click on the Pen Tool icon) can do.
- The Type Tool. You generally want to drag-click this tool to generate a text box, rather than just clicking to create a line of text.
- Scaling. Select an item and then click on this icon to interactively scale an item. Try also double-clicking on the Scaling icon to set a numerical scaling value. Note the options to scale the Strokes and Effects. 
- Rectangle tool. Draws a rectangle with a click and drag gesture (hold down Shift to make it a square shape). Hold down the Rectangle icon to access the ellipse tool and other shapes. 
- Rotate tool (grouped with the Scaling tool). Like the scaling tool, this has both interactive functionality or can be double-clicked on to specify a numerical value for degrees of rotation.
- Artboard. Although you can specify the size of your graphic when you create a document, you can adjust that size with the Artboard tool. 
- Zoom. Does what you might think. Note that you can drag the tool to zoom into a specific area. Holding the Option key (on Mac) turns it into a unzoom tool. 


## Panels
Panels allow you to browse and edit the properties of items in your figure. Most are contextual and so change with items that you select. They are on the right of your Artboard, by default. 
- Layers. Another way to isolate items, layers in Illustrator operate similar to Powerpoint and other software, but the Layers panel allows you to vary the order of layers and their visibility. It is additionally helpful to be able to lock layers when you want to work on other items.
- Stroke. This panel will primarily be used to adjust the weight. Next most useful is the ability to specify how a stroke is dashed. Finally, you can add arrowheads to either end (or both) of a stroke.
- Character. Adjust font and text size. Note that Illustrator has a quirk where the spacing between lines of text (i.e., "leading") does not automatically change when you adjust the font size, so you'll usually want to change the leading when you adjust the font size. 
- Paragraph. To change the justification.
- Transparency. Does what you'd expect. Note that when you apply transparency in MATLAB (and some other sources), Illustrator recognizes those items as having 100% opacity. So, it's a good idea to export your graphics with no transparency so you can control that property entirely within Illustrator.
- Color. You select whether you are working with the stroke or fill and then you can adjust the color. Clicking on the 3 horizontal lines on the right allows you to change the color scheme. I generally prefer to work in HSB. 
- Swatches. You can select pre-designed colors here. Another quirk of Illustrator is the appearance of colors here. When there are no colors (or not what you want), you can click on the "Swatch Libraries Menu" icon on the lower left of the panel and then choose a group of swatches. I most often use Default Swatches > Print.
		

## Helpful tips and tricks

It will not take long before the following prove to be useful.

- Paste in place (under the Edit menu). By default, a pasted item appears in the center of your workspace, whereas Paste in place puts the item exactly from where it was copied or cut. If you are moving items between layers, then you should use this.
- Select>Same. Menu item that allows you to select items based on a selected item. This can be a huge timesaver when you've got graphs with lots of symbols and lines.
- Object>Transform>Transform Each . . . This is the tool to use when you want to scale or adjust the shape of numerous symbols at the same time. Note that it does not work if the items are grouped, so ungroup them first.
- You can use one shape as a mask for another using "Make Clipping Mask" by selecting both items and then right-clicking on them.