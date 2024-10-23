<!-- COMMENTS:
  - I provide lots of in situ comments below that you can extrapolate across your other files.
  - Style & Substance: I like your playfulness and experimentation with Markdown. Yet, MD's formatting made the procedure a bit lengthy in places to complete a more simple procedure like installation. No rub there, but I provided a simplified structure that tries to address a data science audiences needs to quickly scan for dependencies and installation needs.
  - Audience and length requirements for practice. 
  - Alt Text: While we didn't conver alt text in detail, I did mentioned that it should describe the image, rather than a meta-description of what step is refers to. That won't help folks who use assisted tech to perceive parts of your docs.
  - Code Formatting: To format code in MD, you use the backtick character: `.
    - single line: `import matplotlib`
    - multiline: 
    ```python
    import matplotlib
    print(matplotlib.__version__)
    ```
  - Review spelling throughout. There are VSC extensions you can add for this feature.
-->

<!-- # How to Install Matplotlib -->
<!-- COMMENT: 
  - Note that your other titles did not use the "How to" convention. Try to stay consistent with titles, such as maintaining the imperative mood option, as you have done in the prior files.
  - I believe matplotlib is all lowercase
-->
# Install Matplotlib

<!-- In this section, you will learn how to install the "matplotlib" library in Python, which is necessary for creating data visualizations.  -->
Matplotlib does not come standard with the Python programming language, so you must install the `matplotlib` library before you can use its features in your project.
<!-- COMMENT: Since you're coding, you often provide the full file/project too -->

## Prerequisites

<!-- COMMENT: 
  - I like the help here, but I would also listify the requirements.
  - Since you're using the pip and the Terminal, you should also list these here too.
  - ALso, when dealing with coding, be sure to note the environment: For example, are you assuming the use of a Jupyter Notebook environment? Code editor? 
-->
- Python 3.xx.xx <!-- Note Python version -->
- matplotlib xx.xx.xx <!-- Note matplotlib version used in tutorial, since the functions and methods and classes may change over time. -->
- [Any other dependencies?]

<!-- I would add a step for the installation of anything necessary, which is standard in coding tutorials. -->

<!-- 1. **Verify Your Dependencies** -->
<!-- Before installing "matplotlib", ensure you have Python and "pip" installed on your computer. You can check if Python is installed by running the following command in your terminal: -->
1. **Verify Dependencies**: Before installing `matplotlib`, verify if you have installed a compatible version of the following dependencies with your Terminal:
    - Python: `python3 --version`
    ![Python1](assets/images/screenshots/Step1.png)
    - `pip`: `pip --version`
    ![Python2](assets/images/screenshots/Python2.png)

<!-- 2. **Install Matplotlib** -->
<!-- Note the use of a conditional step to help guide people through troublepoints. -->
2. **Install Missing Dependencies**: If a dependency is missing, complete the appropriate installation before proceeding to the next step: [Python](#) or [pip](#).
3. **Install Matplotlib**: In your terminal, install Matplotlib with the following command: `pip install matplotlib`
  ![Python3](assets/images/screenshots/Python3.png)
4. **Verify Installation**: In your IDE, verify `matplotlib` has been installed with the following code:
    ```python
    import matplotlib
    print(matplotlib.__version__)
    ```
    <!-- The code image isn't necessary -->
    **Output**: ![Python5](assets/images/screenshots/Python5.png)
    <!-- ![Python4](assets/images/screenshots/Python4.png) -->

<!-- 3. **Verifying Matplotlib is installed**

To verify Matplotlib is installed, navigate to your IDE and type the following.
"import matplotlib
print(matplotlib.__version__)"

![Python4](assets/images/screenshots/Python4.png) -->

<!-- After running the two lines of code in your IDE, you should see the matplotlib version in your terminal: -->

<!-- ![Python5](assets/images/screenshots/Python5.png) -->

