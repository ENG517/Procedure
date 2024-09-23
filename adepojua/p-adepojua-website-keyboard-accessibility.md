## How to implement keyboard accessibility on your website

Ensuring keyboard accessibility is essential for users who cannot use a mouse. Follow these steps to make your website navigable by keyboard.

### Making the keyboard accessible on your website

1. Start by using the **Tab** key to move through links, buttons, and form fields. Ensure all elements can be accessed via the **Tab** key. 

    **Note**: If elements are not accessible, users relying on keyboards won't be able to interact with them. Also, make sure the focus indicator (the outline around selected elements) is visible. Without it, users may lose track of which element is active.

    ![An example of css code to make focus state visible](/adepojua/assets/images/screenshots/Screenshot%202024-09-20%20at%2023.54.25.png)

2. For links, use the `<a>` tag with an `href` attribute. For buttons, use the `<button>` element. If you must use a `<div>`, make sure to add `tabindex="0"` and the `aria-role="button"` attribute to make it keyboard-accessible.

3. Ensure the focus state is clearly visible by adding or enhancing your CSS. Choose a focus color that contrasts well with the background for better visibility.

4. Add a **"skip to content"** link to allow keyboard users to bypass repetitive navigation and jump directly to the main content. 

![html code to help keyboard users bypass repetitive navigation](/adepojua/assets/images/screenshots/Screenshot%202024-09-20%20at%2023.54.39.png)

5. Ensure no interactive element traps the keyboard focus. For modal dialogs or popups, ensure pressing the **Esc** key closes them and returns focus to the previous element.

6. After making changes, retest your site to ensure all elements are keyboard-accessible and the focus indicator is clearly visible. Save your changes and document any updates for future reference.

## Common Mistakes to Avoid

- **Don't remove focus outlines**: Removing focus outlines for visual appeal makes navigation difficult for keyboard users. You can customize the outlines, but don't eliminate them entirely.

- **Don't rely on hover effects**: Hover-based interactions won't be triggered by keyboard users, so ensure your design works without them.

