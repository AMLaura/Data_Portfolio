# Project 9 : Detect fake banknotes 💶
## Language : Python 💻
## Project duration : 140H ⌛
#### You can find my notebook and the presentation I prepared (initially in PPT format)

### I- The main objective 🎯

The objective is to put in place methods for identifying counterfeit euro banknotes. 
<br/> To do this, I have implemented an algorithm capable of automatically differentiating between real and fake tickets.

When a banknote arrives, there is a machine that records all of its geometric characteristics. 
<br/> Differences in dimensions between real and counterfeit banknotes have been observed. 
<br/> These differences are hardly noticeable with the naked eye, but a machine can do it. 
<br/> Thus, it was necessary to build an algorithm which, from the geometric characteristics of a banknote, is able to define whether it is a real or a fake banknote.

### II- Parameterization file

I had an example file with 1500 banknotes to use to parameterize your algorithm. 
<br/> About the 1 500 banknotes : 1 000 are real and 500 are fake
<br/> A column has been added to specify the nature of the ticket.

### III- Geometric dimension information

1- Length: the length of the banknote (in mm)
<br/> 2- Height_left: banknote height (measured on the left side, in mm)
<br/> 3- Height_right: banknote height (measured on the right side, in mm)
<br/> 4- Margin_up: the margin between the upper edge of the banknote and its image (in mm)
<br/> 5- Margin_low: the margin between the bottom edge of the banknote and its image (in mm)
<br/> 6- Diagonal: the diagonal of the note (in mm)

### IV- Duties
<br/> 1- Perform a descriptive analysis of the data, including the distribution of banknote sizes, the number of real / fake banknotes, etc.
<br/> 2- Create an algorithm (competition of 2 prediction methods)
<br/> • A logistic regression
<br/> • A k-means, from which the centroids will be used to make the prediction

### V- Project particularity ‼️
The detection algorithm was tested live (during the orals) with a file provided by the evaluator
