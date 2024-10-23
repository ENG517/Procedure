
To: Dr. Chris Lundgren

From: Ademola Adepoju

Date: 23-09-2024

Subject: ENG 517 Assignment 1 Reflection

# Procedure Assignment Reflection

For this assignment, I wrote three task-oriented procedures in Markdown and went through the editorial workflow process with members of my group on GitHub. Below is a summary of my reflection, written according to the framework provided by Dr. Lindgren. This reflection covers my summary for all the procedures.


## How do your procedures address the needs of a "reading to learn to do audience"? Provide some specific examples that connect back to Redish's noted features of such an audience.

To meet the needs of a "reading to learn to do" audience, I followed Redish's advice by breaking tasks into simple steps with clear explanations. Each procedure helps users achieve a specific goal while learning.

For example, in **Procedure 1 ("Checking Website’s Color Contrast")**, I start with a short introduction explaining why color contrast matters and what tools the UX designer needs before going into the steps. In **Procedure 2 ("Writing Alt Texts")**, I explain the difference between informational and decorative images. This helps the user understand how to write alt text based on the type of image. This approach matches Redish’s idea that people learn better when new concepts are linked to actions and examples.

## How do your procedures follow the WTGA Staging, Coaching, and Alerting stylistic conventions? Provide some specific examples that connect back to the criteria from Hart-Davidson.

Each procedure uses Hart-Davidson’s Staging, Coaching, and Alerting (SCA) moves to guide the user through the process clearly:

- **Staging**: Each procedure starts with a clear statement of the goal and what’s needed. For example, **Procedure 1** explains why checking color contrast is important and lists what the user will need, like access to design files and a contrast checker tool.
- **Coaching**: The steps use direct phrases, such as "Open your design file" or "Use a contrast checker tool." These clear instructions help the user through each part of the process.
- **Alerting**: Alerting moves are included in all procedures. For instance, in **Procedure 3**, I warned the web developer about potential issues, like making sure keyboard focus is clearly visible. I also shared best practices, such as keeping focus outlines for keyboard navigation, to help avoid common mistakes.

## How do your procedures follow your task orientation work? In other words, based on your audience and their goals, discuss how you oriented your SCA moves to the tasks.

### Procedure 1: Checking Website’s Color Contrast
This procedure is for an intermediate UX designer who needs to follow WCAG guidelines. It focuses on checking and adjusting color contrast, an important part of their work. I introduced tools like the WebAIM Contrast Checker and Stark Plugin, which UX professionals know. The steps guide the user to test and adjust colors until they reach the right contrast ratio. The procedure assumes the user understands design principles but needs help with this specific task.

### Procedure 2: Writing Alt Texts
This procedure is aimed at a junior content creator who might not know much about accessibility standards. I simplified the language and provided clear steps, like deciding if an image is informational or decorative. I included examples of good alt text and explained when to leave the alt attribute blank, which is important for someone with limited technical knowledge.

### Procedure 3: Ensuring Keyboard Accessibility
This procedure is for a web developer who is skilled but may not know much about accessibility. I used some technical terms and code snippets, like `tabindex` and `aria` roles, to give clear steps for making the website keyboard accessible. The procedure helps the developer test and fix keyboard navigation issues while also meeting accessibility standards.

## How did you apply a basic docs-as-code editorial workflow to your assignment? Please provide specific cases with screenshots and/or links that can support your claims.

After writing each of my procedures, I created a pull request (PR) and added my group members as reviewers. I used the PR template to outline what my procedure was about, including the user scenario and goals.

![Pull reuest for one of my procedures](/adepojua/assets/images/screenshots/procedure%20pr.png)

I received reviews on all my procedures, mostly from Sami. As seen in the example below, she made comments about numbering my steps rather than using bullet lists, which I agreed with.

![Sami’s review of my first PR](/adepojua/assets/images/screenshots/pr%20comment%20-%20sami.png)

I took the comments and then reviewed my procedure. I then added a new commit to the PR, as seen below.

![New commit to the PR after making changes based on review](/adepojua/assets/images/screenshots/new%20commit.png)

## How did you apply a consistent use of the Markdown language throughout your project? Please provide specific cases with screenshots and/or links that can support your claims.

I used Markdown consistently across all three procedures to keep things clear and organized for the readers.

- **Headings**: I used `#` for titles and `##` for sections like “What You’ll Need” and “Steps” to break up the content. This made each procedure easy to follow and understand, as seen in **Procedure 1** on checking color contrast.

![Headings written in markdown](/adepojua/assets/images/screenshots/markdown%20headings.png)

- **Lists**: I used numbered lists for steps, like in **Procedure 2 (Writing Alt Texts)**, and bullet points for items needed, like the tools listed in **Procedure 1**.

![Bullet points written in markdown](/adepojua/assets/images/screenshots/markdown%20bullet%20points.png)

- **Links**: I added links to helpful tools, such as the [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/).

![Numbered lists written in markdown](/adepojua/assets/images/screenshots/markdown%20link.png)

- **Images**: I added screenshots using Markdown image syntax to show examples, like in **Procedure 2** where I explained the difference between good and decorative alt text.

![Image inserted within the procedure using markdown](/adepojua/assets/images/screenshots/markdown%20image.png)