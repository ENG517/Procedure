<!-- GENERAL COMMENTS
   - Audience: See note in color contrast. Same feedback.
   - User Goal Consistency: Be clear about what tools you're using in the user goal. In this case, you move across HTML into a Wordpress interface. Choose one and use it as your guide, because if someone is writing HTML, they'll want that tutorial, while someone useing WP will want that tutorial. Remember that user docs should always practice consistency, whenever possible.
   - Seems like this tutorial needs more info in its introduction to establish the criteria to use through examples. For instance, those imperative statements in #2. Those and other guidelines should perhaps be introduced and then use an example that uses those guidelines to ultimately write the alt text.
   - The informational vs. decorative step would also benefit from a table of definitions and comparisons for the user, regardless of technical experience.
   - Each step could benefit from a little inline bolded summary goal statement, so people can scan the steps more quickly. For example, under "Writing Alt Text" you could do the following for the first step:
     - **Decide what type of alt text**: ...
   - Terminology: Alt is shorthand for alternative text. Any first use of an important term should explain this matter. From there, you can use the abbreviated version.
-->

# How to Write Great Alt Texts for Images

Alt texts enable everyone, including people with visual impairments who use screen readers, to understand what your images represent—even if they can’t see them. Use this short guide to learn how to write functional alt texts for your website. <!-- they also render when an image path breaks or the image fails to load. -->

## What You’ll Need to Get Started
- Access to your content management system (CMS) or HTML code
- The images you’ll be describing

## Writing Alt Text

1. First, decide whether the image is **informational** (i.e., it conveys important content) or **decorative** (i.e., it’s just for aesthetics). This will dictate how you handle the alt text.

2. For informational images, write descriptive alt text that explains what someone would need to know if they couldn’t see the image.

   ![Example of an informational alt text](/adepojua/assets/images/screenshots/Informational-alt-texts.png)

   **Note:**  
   > - Don’t say “image of” or “picture of”—screen readers already know it’s an image.  
   > - Don’t use too many words. It’s okay to write only what’s important for understanding the image.

3. If the image doesn’t add to the understanding of the content, leave the alt attribute blank.  
   - Use `alt=""` in the HTML or leave the alt text field empty in your CMS. This tells screen readers to skip over the image without confusing users with unnecessary information.

![Empty alt text fields for decorative images](/adepojua/assets/images/screenshots/decorative-alt-texts.png)

4. Run a quick test with a screen reader to make sure the alt text sounds natural and informative. You can use free tools like [NVDA](https://www.nvaccess.org/) or VoiceOver on Mac. <!-- Provide a link to an official VO tutorial; same for NVDA, since you're not doing that work here. -->

5. Save your work and double-check to ensure you didn’t miss any images.

<!-- what's this sign here -->
> ⚠ 
