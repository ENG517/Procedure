# Vectorizing and Tracing Hand-Drawn Images in Figma #
<!-- Comments
  - I needed to change this to a .md Markdown file.
  - Consider simplifying it to 1 action: "# Tracing Bitmap Images into Vectors in Figma"
  - The file should be renamed with the naming scheme.
-->

Have you ever had a sketch you've created and wondered how it would translate to the digital realm? Of course you could always just take a picture, or a *pixelated* image, but there is another type of image, the [***vector***](https://heighton.agency/insights/vector-files/), which provides several distinct benefits.

Vector images are comprised of mathematical formulas defining points, lines and curves, and can be scaled infinitely and to different screen sizes without loss of quality. They are easily translated to other image formats, flexible, and essential to design software of **all stripes**, including *Figma*. 

Currently, the only method for converting an image to a vector in figma is through **tracing**, which is much easier if completed using the help of a third-party plugin. I will walk you through the process of doing so in a few short and easy steps.<!-- Mind your whitespaces. Note the extra return carriage. -->

<!-- Prereqs? -->


## Image Tracing Plug-Ins ##
<!-- Remember you only need the hashes before the text—not after. Change this throughout. -->
There are many image tracing plug-ins available for Figma, both paid and free. For this tutorial we will be using [Vectorizer (Image Tracer)](https://www.figma.com/community/plugin/1526280907441235581/free-vectorizer-image-tracer). I have found the image attained to be noticeably higher quality than many of its counterparts— plus it is compatible with most image formats, including JPEG, PNG, and GIF.

<!-- Question
  Are you writing these tutorials as an employee of Figma or someone external to Figma? The use of "I" suggests the latter. But, if you are writing this suite of tutorials as a Figma user, then it can work. Just be sure to update your scenarios to reflect that positonality.

  However, consider this revision regardless of role:

  > For this tutorial, we will be using [*Vectorizer (Image Tracer)*](https://www.figma.com/community/plugin/1526280907441235581/free-vectorizer-image-tracer), since this plugin achieves higher quality results with no licensing fees. Additionally, *Vectorizer* is compatible with most image formats, such as JPEG, PNG, and GIF. [*Image Tracer*](https://www.figma.com/community/plugin/735707089415755407/image-tracer) requires a one-time licensing fee of $10, but it is another solid option. Compare more plugins to use in the table below.

Note how I combined it as 1 paragraph, since it is covering the same material.
-->

[Image Tracer](https://www.figma.com/community/plugin/735707089415755407/image-tracer) is another solid option, though it does require at one-time licensing fee of $10. Find a comparison of these and a few other viable plug-ins below.

| Plug-In            |   Paid                |   Pros           |  Cons           |
|-------------|---------------------|--------------|-------------|
| Vectorizer (Image Tracer)      |         N            | Supports expansive range of colors, lines are accurate             |    Software occasionally needs restarting        | 
|   Image Tracer          |  Y                   |  Software is updated regularly and lines are accurate           |       Colors can appear overexposed at times     |
|      Trace Image      |          N           | Very accurate with simple images             |      Output is in black and white, only works well with jpegs      |
|    Vector Magic         |  Y                   | Colors are accurate             |    Not updated regularly         |

## Import your Image ##
<!-- Major step/phase
  Procedures should include numbered steps. This heading represents the first major step:

  > ## 1. Import an Image
-->

Before we begin using *Vectorizer*, we will first have to import an image. To do this you'll first have to create a **frame**.

### Creating A Frame ###
<!-- Step
  ### 1.1 Creating a *frame*

  Note the numbering scheme to help people navigate your document. Also note how you can use capitalization to help distinguish levels.
-->

1. Open a new Figma workspace.
2. In the toolbar at the bottom of the page, select the **Frame Tool** (to __do what exactly__?).
    ![Frame Tool](./assets/images/screenshots/Frame_Toolbar.png)
    > *Figure 1: The **Frame Tool** is the primary container for design elements in Figma.*
<!--
2. Navigate to the toolbar located at the bottom of the page.
3. Select the Frame Tool, located in the second dropdown menu from the left.

- Note how your original #2 wasn't quite a user action.
- Also consider if select
- Also, the screenshot doesn't indicate where to click/select.
-->
4. Resize your frame by dragging its corners.
    <!-- Expected a step result figure here. -->
    > **Note**: For bigger images you will want a larger frame.
    <!-- > Note: For bigger images you will want a larger frame. -->

### Filling Your Frame ###
<!-- See above feedback for this section -->
1. Navigate to the properties panel located on the right-hand side.
<!-- I recommend using strong styling for UI controls, such as **Frame Tool** above -->
2. Click the "FFFFFF" button located underneath the "Fill" property.
3. Navigate to the image icon.
4. Click "Upload from Computer."
5. Import your Image.  


Now that we have imported your visual it's time to begin the process of tracing and vectorizing it. Depending on the complexity of your image, you can probably tell from a quick glance how hard manually tracing it might be with Figma's drawing tools.

Luckily, the process is not nearly so difficult with our handy plug-in.

<!-- Comments
- I think you should combine the last subsections into 1 here. You also state "Opening and running ..." in the title
-->
### Opening and running Vectorizer (Image Tracer) in Figma ###
1. To run Vectorizer (Image Tracer) first navigate to the plug-ins home page [here](https://www.figma.com/community/plugin/1526280907441235581/free-vectorizer-image-tracer).
2. Select your workspace from "Recent Files."
<!-- Use consistent Note formatting throughout your docs. -->
    - The symbol in the blue square denotes a standard Figma design space.
    - Your workspace should be first in the list.

<img src="assets/images/screenshots/Open Vectorizer.png" alt="Alt text" style="width: 280px">

> *Figure 2: Feel free to rename your workspace, but it will default to "**untitled**."*


### Running Vectorizer (Image Tracer) ###
Once Vectorizer has successfully run, the following window should appear on your screen.

<img src="./assets/images/screenshots/Vectorizer in Figma.png" alt="Alt text" style="width: 320px">

Complete the following tasks to fully vectorize your raster image.
<!-- Use consistent langauge. So far, "Select" is the most widely used. Also, provide orientation language and use screenshots more consistently. -->
1. Press "fetch image".
2. Select your frame.
3. Adjust image properties in the toolbar to your liking.
<!-- Seems like something to develop here; at least perhaps aspect ratios or common sizing conventions? -->
    - There are many adjustable properties in Vectorizer.
    - Play around until you are satisfied with your image.
> Note: For more detailed images, I'd recommend the **"spline"** curve fitting.
4. Select "Insert Vector."

<!-- Heading? -->
##
And there you have it! You now have a fully vectorized image in Figma in ***SVG*** format. This is great for logos, icons, and illustrations that need to be scaled for different purposes, plus just a cool thing to show your friends. 

Feel free to repeat the process for as many image files as you'd like, either in the same or different workspaces depending on your preferences and needs.


<!-- Integrate these tips throughout. Some  -->

## Tips for Success ##
- Check Vectorizer (Image Tracer) regularly for updates.
    - Make sure to update your software when new patches are released.
    - Don't hesitate to contact the developer if you're experiencing issues.
- Use simple images.
    - Vector images are not entirely as *photorealistic* as raster.
    - Software renders simpler images clearer.
- Keep tinkering!
    - Experiment with other plug-ins if you'd like.
    - Try out different editing techniques.