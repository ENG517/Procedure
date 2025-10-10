# Tracing Bitmap Images into Vectors in Figma 

Have you ever had a sketch you've created and wondered how it would translate to the digital realm? Of course you could always just take a picture, or a *pixelated* image, but there is another type of image, the [***vector***](https://heighton.agency/insights/vector-files/), which provides several distinct benefits.

Vector images are great for logos, icons, and illustrations because they can be scaled infinitely and to different screen sizes without loss of quality. They are also easily translated to other image formats, flexible, and essential to design software of **all stripes**, including *Figma*. 

Currently, the only method for converting an image to a vector in Figma is through **tracing**, which is much easier if completed using the help of a third-party plugin. I will walk you through the process of doing so in a few short and easy steps.

## Prerequisites
- An image to vectorize. Simple images will show up much more clearly.
- An image tracing plug-in.

  > Note: Images not in JPEG, PNG, or GIF form will not render.


### Image Tracing Plug-Ins
For this tutorial, we will be using [*Vectorizer (Image Tracer)*](https://www.figma.com/community/plugin/1526280907441235581/free-vectorizer-image-tracer), since this plugin achieves higher quality results with no licensing fees. Additionally, *Vectorizer* is compatible with most image formats, such as JPEG, PNG, and GIF. [*Image Tracer*](https://www.figma.com/community/plugin/735707089415755407/image-tracer) requires a one-time licensing fee of $10, but it is another solid option. Compare more plugins to use in the table below.

| Plug-In            |   Paid                |   Pros           |  Cons           |
|-------------|---------------------|--------------|-------------|
| Vectorizer (Image Tracer)      |         N            | Supports expansive range of colors, lines are accurate             |    Software occasionally needs restarting        | 
|   Image Tracer          |  Y                   |  Software is updated regularly and lines are accurate           |       Colors can appear overexposed at times     |
|      Trace Image      |          N           | Very accurate with simple images             |      Output is in black and white, only works well with jpegs      |
|    Vector Magic         |  Y                   | Colors are accurate             |    Not updated regularly         |

### 1. Import an Image
Before we begin using *Vectorizer*, we will first have to import an image. To do this you'll first have to create a **frame**, the primary container for design elements in Figma.

#### 1.1 Creating A *frame*
1. Open a new Figma workspace.
2. Navigate to the toolbar located at the bottom of the page.
3. Select the Frame Tool, located in the second dropdown menu from the left.
4. Resize your frame by dragging its corners.

<img src="assets/images/screenshots/Sample Frame.png" alt="Alt text" style="width: 280px">

> *Figure 1: For bigger images you will want a larger frame.*
#### 1.2 Filling A *frame*
1. Navigate to the **properties panel** located on the right-hand side.
2. Click the **FFFFFF** button located underneath the **Fill property**.
3. Navigate to the **image icon**.

<img src="assets/images/screenshots/Image Icon.png" alt="Alt text" style="width: 280px ; height: 450px">

> *Figure 2: The image icon is the fourth button from the right.*
4. Click **Upload from Computer**.
5. Import your Image.  


Now that we have imported your visual it's time to begin the process of tracing and vectorizing it. Depending on the complexity of your image, you can probably tell from a quick glance how hard manually tracing it might be with Figma's drawing tools.

Luckily, the process is not nearly so difficult with our handy plug-in.

### 2. Vectorizing Your Image 
1. Navigate to the plug-ins home page [here](https://www.figma.com/community/plugin/1526280907441235581/free-vectorizer-image-tracer).
2. Select your workspace from "Recent Files."  
    > Note:  The symbol in the blue square denotes a standard Figma design space.

<img src="assets/images/screenshots/Open Vectorizer.png" alt="Alt text" style="width: 280px">

> *Figure 3: Feel free to rename your workspace, but it will default to "**Untitled**."*

After you select your current workspace, the following window should appear on your screen.

<img src="./assets/images/screenshots/Vectorizer in Figma.png" alt="Alt text" style="width: 320px">

> *Figure 4: The home page of Vectorizer (Image Tracer).*

Once Vectorizer (Image Tracer) is successfully running, complete the following tasks to fully vectorize your raster image.

4. Select **fetch image**.
5. Select your frame.
6. Select a **Curve Fitting**.

  <img src="./assets/images/screenshots/Curve Fittings.png" alt="Alt text" style="width: 320px">

> *Figure 5: For more detailed images, I'd recommend the **"spline"** curve fitting, as it will better capture a wide variety of shapes. Pixel and Polygon work better with non-complex images*
7. Select **Insert Vector**.

## Congratulations!
And there you have it! You now have a fully editable, vectorized image in Figma in ***SVG*** format.

Feel free to repeat the process for as many image files as you'd like, either in the same or different workspaces depending on your preferences and needs. Don't hesitate to experiment with other plug-ins as you continue to vectorize images with different properties.

