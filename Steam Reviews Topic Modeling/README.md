# Steam Reviews Topic Modeling

## Objective

The purpose of this research is to understand what the players of selected 4X, turn-based strategy games like and dislike about these games (Endless Legend, Battle Tech, Empire of Sin, Age of Wonder: Planet Fall, and Phoenix Point). We'll be running topic modeling on the positive and negative reviews separately to extract topics. In other words, we'll have 2 corpora (positive/negative), and each has 5 documents/game.
We'll then visualize the topics distributions and generate word clouds of the most the top N keywords for each game. 

There's this guy who talks about how gamers use other other games as a point of reference when reviewing a game, and this inspired that...

## Research Question

## Table of Contents
<details open>
 <summary>Show/Hide</summary>
 <ul>
  1. <a href="https://github.com/ckohcm/Projects/blob/main/Steam%20Reviews%20Topic%20Modeling">Steam Reviews Topic Modeling</a>
 <ul>
  <li> nested list 1</li>
  <li> nested list 2</li>
  </ul>
  <li> 2. Technologies Used </li>
  <li> 3. Structure </li>
  <li> 4. Results </li>
  <li> 5. Summary </li>
 </ul> 
</details>

## File Description
- [Data](...):
 - [Raw Data](...): Contains the following game reviews downloaded from the API [steamreviews 0.9.3](https://pypi.org/project/steamreviews/) which were saved as JSON files. The following briefly describes the number of positvie and negative reviews of each game:
    - Endless Legend : 9,859 (Positive : XX, Negative : XX)
    - Battle Tech : 17,968 (Positive : XX, Negative : XX)
    - Empire of Sin : 1,911 (Positive : XX, Negative : XX)
    - Age of Wonders (Planetfall) : 2,546 (Positive : XX, Negative : XX)
    - Phoenix Point : 1,221 (Positive : XX, Negative : XX)
    - Stellaris : 17,968 (Positive : XX, Negative : XX)
 - [Images](...): Contains all images created for this project.
 - [Data_Preprocessing_Notebook.ipynb](...): 
 - [Exploratory_Data_Analysis.ipynb](...): 
 - [LDA_Model_Notbook.ipynb[(...)


## Technical Overview
<details open>
 <summary>Show/Hide</summary>
 <ul>
  1. <a href="https://github.com/ckohcm/Projects/blob/main/Steam%20Reviews%20Topic%20Modeling">Steam Reviews Topic Modeling</a>
 <ul>
  <li> nested list 1</li>
  <li> nested list 2</li>
  </ul>
  <li> Data Cleaning </li>
  <li> Exploratory Data Analysis </li>
  <li> Topic Model </li>
  <li> Metric Evaluation </li>
 </ul> 
</details>

## Requirements
Note to self: Create a requirements.txt

# Results
### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ckohcm/Steam_Reviews_Analysis/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
