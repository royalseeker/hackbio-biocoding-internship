# Drug Discovery

## Overview
What chemical properties determine if a small molecule will bind to a protein target? 

### Study this data
It is a chemical descriptor matrix of over 10,000 compounds.

## Tasks
Using the data above, pick any of the tasks below:

1. **Using PCA and K-means clustering**: Represent the chemical space of all the compounds represented here.
   - A chemical space representation can be extremely diverse, but you will definitely find some interesting chemical clusters. Read about chemical space [here](https://en.wikipedia.org/wiki/Chemical_space).
   
2. **Color the chemical spaces by the docking score**.
   - Is there a sub-cluster that preferentially has a lower docking score? What are they and how do you interpret this special cluster?

3. **Docking Information**:
   - These compounds were docked against adenosine deaminase (ADA), a protein associated with a lot of diseases.
   - The docking score is in the score column. Note that in docking, the lower the binding energy, the better.

4. **Regression Analysis**:
   - Using regression algorithms, can you predict the docking score using the chemical features alone?
