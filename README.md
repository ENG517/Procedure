# Procedure

Repo for the Procedure assignment in ENG 517 at NCSU.

## Setting Up Your Assignment

1. Copy the `TOCOPY` folder.
2. Rename the `TOCOPY` folder with the following scheme in all lowercase letters: `lastnamefirstnameinitial`.
     * **Example**: Chris Lindgren --> `lindgrenc`
3. Rename each task markdown file with the following naming scheme in all lowercase letters: `p-product/feature/process-taskname.md`
     * **Example**: How to make an espresso with the Exzprezzo 5000 --> `p-exzprezzo5000-make-espresso.md`.
     * **Tip**: Keep it as concise as possible. Note how I did not repeat the title verbatim. Instead, I used the main task action (verb) and what is being modified by that action (verb object).
4. Be sure to read the directions, where provided, about what each folder should contain and organize.


## Editorial Workflow Expectations

1. You develop your project in branches, rather than pushing to the main branch. Each branch should involve your work for each procedure, i.e., 1 branch per procedure.
     * **WARNING**: Be sure that you are working on the correct branch by using Github Desktop and VS Code. If you are not on the correct branch, you will be making commits to the wrong version of the project.
2. Each work session that you conduct includes an appropriate number of commits on the correct branch.
3. Each commit message tries to concisely summarize what has been changed in that commit.
4. During week 5, you conduct and participate in peer review sessions for each procedure via pull requests for each procedure.
5. Once each procedure is complete, merge each procedure via its respective pull request.


## Helpful Tips &amp; Resources

### Images

Currently, Markdown does not support image resizing. If you would like to resize your images consistently, you will need to use the HTML `<img>` element.

```html
<!-- Example Image Element in HTML -->
<img src="assets/path/to/image.jpg" alt="Alt text" style="width: 300px">
```

In the example above, you will need to revise the **values** for the element's **attributes**. The values are written between the double-quotes for the following attributes: 

- `src=""`: Synonomous with parantheses `[](assets/path/to/image.jpg)`
- `alt=""`: Synonomous with square brackets `[Alt text here]()`
- `style="width: 300px"`: Write CSS styles for this attribute. Here, we only need to change the width value, and your browser will keep the aspect ratio of the image.


<!-- IGNORE: CUSTOM CSS STYLES -->
<!-- Don't worry about these custom styles below. I just included them here to spice up the markdown. -->
<style>
  @import 'https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,opsz,wght@0,6..12,200..1000;1,6..12,200..1000&family=Titillium+Web:ital,wght@0,200;0,300;0,400;0,600;0,700;0,900;1,200;1,300;1,400;1,600;1,700&display=swap';
  :root {
  --headingFonts:"Titillium Web";
  --copyFonts:"Nunito Sans";
  }
  body {
    font-family: var(--copyFonts);
    line-height: 1.75rem;
  }
  h1,h2,h3,h4,h5,h6 {
    font-family: var(--headingFonts);
  }
</style>
