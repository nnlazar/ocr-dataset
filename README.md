# ocr-dataset

**Instructions for annotating images:**

  The content of each image needs to be labeled as:

  Text: please draw a bounding box around individual paragraphs, figure & table caption; table footnote;
  Title: please draw a bounding box around each standalone title, section and subsection title;
  List: please draw a bounding box around nested lists;
  Table: please draw a bounding box around each table;
  Figure: please draw a bounding box around each figure.

Here are some examples of correctly annotated images:
  - [Screenshot 2023-04-07 at 11.18.26.png](https://github.com/nnlazar/ocr-dataset/blob/main/Screenshot%202023-04-07%20at%2011.18.26.png)
  - https://github.com/nnlazar/ocr-dataset/blob/main/Screenshot%202023-04-07%20at%2011.23.58.png
  
  

**Please check the /corect_wrong_images folder for more examples.**

In /corect_wrong_image the following examples are incorectly annotated. In the folder we have provided the correct version of the image.

colors = {title: blue,
          text: green,
          list: red,
          table: yelow,
          figure: turquoise,}

 
3_wrong : The bounding box for the “Profit from recurring operations” should be only one bounding box that encompasses the word “operations”

3_wrong: The list under the first label should be annotated as a list and not text

4_wrong_1: The bounding box of the title should be only one bounding box that encompasses the whole title

4_wrong_2: The text that is under the figures that start with “a)”, “b)” or “1)”, “1.” Should be labeled as list and not text

4_wrong_2: The figures are labeled as table when they should be labeled as figure

7_wrong: The figure legend that is shown under the figure should be one with the bounding box of the figure and not a separate bounding box

10_wrong: Lists should be labeled as one bounding box like at the bottom of the page and they should also include the the mark that shows that in the bounding box there is a list, in this case the mark is the “-“ symbol

22_wrong: Table of contents should be labeled as a list and not a table

29_wrong: Lists are mislabelled

30_wrong: The “”Other operating income and expenses" comprises income statement items, which - due to their nature, amount or frequency - may not be considered inherent to the Groups recurring….” Text should be labeled as one text bounding box

44_wrong: The list under the second and third table should be labeled as list and should be included in one bounding box

46_wrong: The list under the first and second table  should be labeled as list and should be included in one bounding box

48_wrong: The text under the third table is not labeled as list

55_wrong: The text under the second table is not labeled as list and is labeled in multiple bounding boxes that should be replaced by one bounding box that includes all the elements

58_wrong: The bounding box includes the whole text when is should include only one paragraph at a time

63_wrong: The text at the bottom of the page should be broken in paragraphs

65_wrong: The title is labeled as text when is should be labeled as title
