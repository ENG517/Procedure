# Making Text Accessible: Checking and Fixing Color Contrast

Ensuring your text is readable for everyone is critical, especially for users with visual impairments. Neglecting contrast checks can result in inaccessible designs, frustrated users, and failure to meet accessibility standards.

In this guide, you will learn how to check and fix color contrast issues in compliance with WCAG (Web Content Accessibility Guidelines).

---

## What You Will Need
- Two color codes: foreground (text) and background
- Access to a color contrast checker tool ([WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) or plugins like Stark for Figma/Adobe XD)
- Basic understanding of hexadecimal (hex) color codes (e.g., `#FFFFFF` for white, `#000000` for black)

---

## Prerequisites
Before you start:
1. Make sure you have the **hex codes** for your text (foreground) and background colors. If unsure, tools like [Color Picker](https://htmlcolorcodes.com/color-picker/) can help you find these codes.
2. Familiarize yourself with **contrast ratio** concepts:
   - **Normal Text**: Minimum ratio of **4.5:1**.
   - **Large Text (18pt or larger)**: Minimum ratio of **3:1**.
3. Read WebAIM’s article on [Color Contrast and Accessibility](https://webaim.org/articles/contrast/#defining) for more details.

---

## Steps to Check and Fix Color Contrast

### 1. Open a Contrast Checker Tool
Visit a color contrast tool like the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/) or use a plugin like Stark in Figma/Adobe XD. These tools help evaluate your color choices against WCAG standards.

---


### 2. Input Hex Codes
1. Enter the **hex code** for your foreground (text) color into the "Text Color" field.
2. Enter the **hex code** for your background color into the "Background Color" field.
  
   ![A screenshot showing how to input hex codes in the contrast checker](/adepojua/assets/images/screenshots/hex%20code.png)

> **Tip**: Focus the screenshot on the input fields to help users quickly locate them.

---

### 3. Evaluate the Contrast Ratio
1. Once the codes are entered, the tool calculates the contrast ratio.
2. Compare the ratio to WCAG’s minimum requirements:
   - **Normal Text**: Ratio must be at least **4.5:1**.
   - **Large Text**: Ratio must be at least **3:1**.

   If your ratio meets or exceeds these thresholds, your colors are accessible! Otherwise, proceed to Step 4.

---

### 4. Adjust Colors
1. If the contrast ratio is too low, adjust your colors:
   - Use tools like the “Lightness” slider in WebAIM or Stark to lighten the background or darken the foreground color.
   - Retest the adjusted colors in real-time to ensure they meet the WCAG threshold.
2. Ensure the adjustments maintain your design’s visual consistency.

   > **Note for Dark Mode Designs**: Test inverted color schemes (e.g., light text on dark backgrounds) to confirm accessibility across modes.

---

## Additional Tips
- **Error Handling**: If you input an invalid hex code, most tools will show an error message. Correct the input and retry.
- **Screenshots**: Include clear screenshots highlighting specific steps, such as the input fields and contrast ratio results.
