# Procedure Assignment Reflection

Write a short analysis (~500 words) in which you explain what you did to meet the assignment's criteria. Use the criteria as headings to structure your reflection.

## How do your procedures address the needs of a "reading to learn to do audience"? Provide some specific examples that connect back to Redish's noted features of such an audience.

Features of a R2L2D tutorial, according to Redish, and how my procedures address them:

* Gain a basic understanding of the concepts and structures
of the program
  * My procedures give brief but sufficiently detailed overviews of the materials and components involved, done mainly in the material prep guide. The knowledge gained from that guide is applied in the other two.
* Become comfortable with the program so that they will want to continue to use it and be satisfied with it
  * This ties back to equipping the reader with the knowledge and skills to do this complete this kind of task again *without* the guide. Again, the feature explanations help with that and the wiring diagram exists as a quick reference for returning users. The idea is all they'll need is the wiring diagram, if that.
* Be able to perform basic, relevant tasks with the program after using the tutorial
  * Because the task only needs to be completed once per guitar (or as many times as they want to upgrade _all_ the components), the user will get better and faster at completing the individual tasks in the procedure with each guitar.
* Transfer what they have learned from the examples in the tutorial to other situations that were not directly covered in the tutorial

---

## How do your procedures follow the WTGA Staging, Coaching, and Alerting stylistic conventions? Provide some specific examples that connect back to the criteria from Hart-Davidson.

### Wiring a Single-Humbucker Setup: Preparing Materials

#### Staging Move

* Introduction outlines the purpose (overview of materials), intended audience of the document (budding hobbyists), and success conditions (properly prepared materials).
* Prerequisites section provides comprehensive list of materials, tools, and skills needed for success.

#### Coaching Move

Using **Step 2** as an example:

* Begins with an imperative verb ("Flip")
* Provides clarifying detail of the desired outcome when the step is completed (The flat metal casing and lugs are pointing up)

### Alerting Move

The "Note:" in **Step 1** is an alerting move that,

* Uses the ```>``` element to create visual distinction,
* indicates negative consequences ("Failure to do so will cause major noise bleed and a weak sound")/
* and explains how to avoid the problem (ensure wires are soldered together and taped off).

### Wiring a Single-Humbucker Setup: Connecting Components

#### Staging Move

* Introduction outlines purpose (wiring the circuit), indended audience (beginners and intermediates), and success conditions (properly prepared materials as explained in the previous guide).
* Prerequisites section provides comprehensive list of materials, tools, and skills needed for success. It is almost an exact duplicate of the list in the material prep guide with a few details removed that will either be redundant for true beginners or unecessary for intermediates.

#### Coaching Move

Using **Step 2** of the "Connecting the Hot Wires" section as an example:

* Uses imperative verbs to guide the reader through the steps to be completed ("Solder").
* Desired outcome is represented visually in the diagram.

#### Alerting Move

"Important Details and Warnings for Soldering" section:

* Visually distinct section
* Clear indication of negative consequences (user could fry the carbon track)
* Explanation of how to avoid the problem (hot soldering iron, heat sinks, buffer period)

### Guitar Wiring Troubleshooting

#### Staging Move

* Introduction outlines purpose (common errors and solutions), _implies_ indended audience (someone who has wired a circuit but is encountering problems), and outlines success conditions (user must systematically proceed through each troubleshooting step in their given problem section).
* Prerequisite section tells user they must have completed the previous guides or have a completed but faulty circuit.
  
#### Coaching Move

Using **Step 1** of the "Weak or No Sound" section:

* Uses imperative verbs to guide the reader through the steps to be completed ("de-solder", "disconnect", "re-solder").
* Desired outcome is stated to be fault identification, or what specific component is causing the problem (humbucker, pots, or output jack).

#### Alerting Move

Using **Step 6** of the "Weak or No Sound" section:

* Uses the ```>``` element to create visual distinction
* Indication of negative consequences (user could fry the carbon track again)
* Explanation of how to avoid the problem (limit the amount of time soldering iron is in contact with the pots)

---

## How do your procedures follow your task orientation work? In other words, based on your audience and their goals, discuss how you oriented your SCA moves to the tasks.

I wrote my procedures with a true beginner in mind, but they aren't so bogged down by detail that it makes it a slog for intermediates. This excerpt from my user scenario explains the kinds of things I kept in mind:

> Clay is young and curious. He doesn't just want to learn how to get things wired, he wants to learn how it all works. However, he isn't a super avid reader and doesn't respond well to exceedingly long blurbs of text, preferring visuals instead. He has some experience with electronics work from a summer camp he went to in middle school and is eager to dive back in.

This is a R2L2D document, so it has the dual purpose of guiding the user through a procedure and equiping them with the knowledge and skills to do it again on their own and with more complex circuits (that's why I explained what the lugs of a potentiometer do).

I also avoided long blurbs of text as much as possible, though it's a little unavoidable when explaining some of the component features if I want to explain them sufficiently, and made some wiring diagrams to support the written instructions. The diagrams were designed so the reader might not even need to read the step text once they get the hang of things.

## How did you apply a basic docs-as-code editorial workflow to your assignment? Please provide specific cases with screenshots and/or links that can support your claims.

I made sure to commit frequently with each completed section or major update, including descriptive commit summaries.

---

![Screenshot of GitHub desktop showing commit messages](/hassell/assets/images/reflection-images/docs-as-code-workflow.png)

## How did you apply a consistent use of the Markdown language throughout your project? Please provide specific cases with screenshots and/or links that can support your claims.

I consider myself extremely proficient with Markdown considering I use it daily for work. The big thing for me was keeping the information hierarchies and styles consistent, like using the asterisk for bullets (I got into the habit of using those instead of hyphens for work), heading 3s for step numbers, using horizontal rules to divide major sections, etc.

![Screenshot showing markdown usage](/hassell/assets/images/reflection-images/markdown-usage.png)

---
