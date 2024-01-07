# Machine Learning and Statistics

by Kenneth Linehan

## About

This repository is for a module called Machine Learning And Statistics, which I studied at ATU at Winter 2023. The module consists of 5 tasks, which were based on 4 of the subjects which we looked at.

These subjects are:
1. Chi-Square Tests
2. t-Tests
3. k Nearest Neighbours
4. Preprocessing

## Project Question

- The project is to create a notebook exploring classification algorithms applied on the iris flower data set associated with Ronald A Fisher.

- In your notebook, you should first explain what supervised learning is and then explain what classification algorithms are.

- Describe at least one common classification algorithm and implement it using the scikit-learn Python library.

- Throughout your notebook, use appropriate plots, mathematical notation, and diagrams to explain the relevant concepts

- This is the link to my project code: https://github.com/KenLin765/machine-learning-and-statistics/blob/main/project.ipynb

## Tasks Questions

1. Square roots are difficult to calculate. In Python, you typically use the power operator (a double asterisk) or a package such as `math`. In this task, 1 you should write a function `sqrt(x)` to approximate the square root of a floating point number x without using the power operator or a package.

Rather, you should use the Newton’s method.  Start with an Square Roots via Newton’s Method. initial guess for the square root called $z_0$. You then repeatedly improve it using the following formula, until the difference between some previous guess $z_i$ and the next $z{i+1}$ is less than some threshold, say 0.01.

2. Consider the below contingency table based on a survey asking respondents whether they prefer coffee or tea and whether they prefer plain or chocolate biscuits. Use scipy.stats to perform a chi-squared test to see whether there is any evidence of an association between drink preference and biscuit preference in this instance.


<table>
  <tr>
    <th style="border: none;"></th>
    <th style="border: none;"></th>
    <th style="border-right;"><em>Biscuit</em></th>
    <th style="border: none;"></th>
  </tr>
  <tr>
    <th style="border: none;"></th>
    <th style="border: none;"></th>
    <td style="border-right;"><strong>Chocolate</strong></td>
    <td><strong>Plain</strong></td>
  </tr>
  <tr>
    <td><em>Drink</em></td>
    <td>Coffee</td>
    <td>43</td>
    <td>57</td>
  </tr>
  <tr>
    <th style="border: none;"></th>
    <td>Tea</td>
    <td>56</td>
    <td>45</td>
  </tr>
</table>

3. Perform a t-test on the famous penguins data set to investigate whether there is evidence of a significant difference in the body mass of male and female gentoo penguins

4. Using the famous iris data set, suggest whether the setosa class is easily separable from the other two classes. Provide evidence for your answer.

5. Perform Principal Component Analysis on the iris data set, reducing the number of dimensions to two. Explain the purpose of the analysis and your results.



## How to use Repository
1. Install Anaconda (Link - https://www.anaconda.com/download)

2. Install Visual Code Studio - Please ensure you also install Python in visual code studio (Link - https://code.visualstudio.com/Download)

3. Clone Repository - I think this is a good guide to clone repository (Link - https://github.com/MicrosoftDocs/azure-dev-docs/blob/main/articles/javascript/how-to/with-visual-studio-code/clone-github-repository.md)

4. Open Repository in Visual Code studio.

5. I would suggest then to run tasks.ipynb as it will show all the tasks that were completed.

6. I would then suggest to run project.ipynb which will show the project and the outputs.