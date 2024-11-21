# How to Check Your Website’s Color Contrast

Making sure your text is readable for everyone is important, especially for users with visual impairments. Skipping contrast checks might result in unreadable text, frustrating users, and putting your website at risk of failing accessibility audits.

In this quick guide, you will learn how to check and fix color contrast issues to comply with accessibility standards like WCAG (Web Content Accessibility Guidelines).

<!-- General Comments
   ## Audience
   Your audience analysis doc takes a widespread across experienced and new developers, so consider how that makes it difficult to make decisions about what information and steps to include and exclude. See my comments on audience throughout.

   ## User Goal
   I'm wondering: What tool is being used? I see that you suggest that this tutorial is tool agnostic. But, you are using WebAIM's tool. I agree that this can be translated pretty easily across other tools, but I think you should specify how this tutorial uses WebAIM's tool. In the prereq section, you can refer people to other tools, if you would like.

   ## Structure
   Your current structure of "1. **Major Step Language Here**
      - I appreciated you larger order steps in bold. But, note how the substeps are not numbered and difficult to parse in the paragraph format. Additionally, I think some of those substeps require elaboration. For example, the current steps 4 and 5 would benefit with some more concrete guidance. (See my comments.)
   
   ## Screenshots
   - I think you need to create and use more screenshots that break up the interface into the parts relevant to the step.

   ## Other Comments
   - I appended "color" to "contrast checker," since that is the more accurate description.
   - Language consistency:
     - "text color" should be "foreground color" since that is the language used in the tool.
     - "hex code" should be noted at its first use to be synonymous with hexadecimal color code.
   - Errors?
     - What about alerting moves that help guide users' action when something goes wrong? For example, what happens when an incorrect color code is entered in one of the inputs?
-->

## Prerequisites

<!-- On Prereqs
   - Add a return carriage after headings for consistency in your Markdown
   - Renamed as "Prerequisites" based on the professional context
   - AUDIENCE: Should we expect new folks to know what a "hex code" is? To complicate matters, the full term is hexadecimal color code.
   - Rather than asking them to have design files, I think it is more appropriate to ask a user to have those two color codes ready to go. The user goal is to check color contrast, not how to locate a hexadecmial color code in their respective project.
-->
- [WebAIM Color Contrast Checker](#add-url-here)
- Basic understanding of color codes and color contrast ratios
  - Refer to WebAIM's article on "[Color Contrast and Accessibility](https://webaim.org/articles/contrast/#defining)."
- Your project's background color and foreground color.

## Checking Color Contrast

1. **Open Your Design File**
   
   Access your design file and identify the text and background colors on the page or screen you want to check.
   **Note**: Write down the hex codes for both the text and the background. These codes are essential for the next step.

2. **Use a Contrast Checker Tool**
   
   Go to a color contrast checker tool like [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) or use a plugin like Stark if you're working in Figma or Adobe XD. These tools will help you see if your colors meet the accessibility standards.

3. **Enter Hex Codes**

   1. Enter the hex code for your text color and background color into the contrast checker. The tool will calculate a ratio that shows how well your colors contrast against each other.
   ![A screenshot showing how to input hex codes in the contrast checker](/adepojua/assets/images/screenshots/hex%20code.png)
   <!-- This screenshot includes too much information. If the step is about simply entering the codes, then you should only use that part of the interface. Otherwise, people may not understand what part of the image the step relates to. -->
   <!-- There's an extra return carriage here, where I placed this comment. -->

4. **Evaluate the Contrast Ratio**
<!-- This seems like an important area that needs more description; esp. if your audience is new to color contrast checking. Specfically, normal vs large text require explanation. You could simply write a short preface paragraph, "Contrast ratio scores take into account the size of text. Below are the minimum scores that can guide your evaluation of your color contrast:" Then, you'd revise the bulleted points in keeping with the concepts of "Normal Text" and "Large Text" You can then also provide links to an extended description of these terms and concepts. -->
   - If the ratio is 4.5:1 or higher for regular text, you’re good to go. For large text (18pt or larger), the minimum ratio is 3:1.
   - If your ratio is below the required threshold, don’t worry—that’s what we’ll fix next!

5. **Adjust Colors**
   
   If the contrast ratio is too low, try lightening the background or darkening the text color. <!-- Use screenshots and language from the interface to orient your readers. Consider how you could reference the "Lightness" adjustment bar and have a screen capture of that portion of the screen, but this one could have a simple square around the area of note. Also, consider how your direction assumes a light mode contrast with a light background only. I wonder if you might provide a note that if these two colors pass the test, their inverse could yield an opposite "mode". --> Your goal is to adjust them enough to improve readability while maintaining your design’s overall look.
 
   **Note:** To see the ratio improve, it is advisable to use the contrast checker in real-time as you tweak colors.

6. **Test Again**
   
   Once you’ve made adjustments, test the colors again by entering the new hex codes into the contrast checker. Keep tweaking until you reach the required ratio.

7. **Save Your Design**
   
   Once everything passes, save your design. Congratulations, your website is now more accessible for all users! 