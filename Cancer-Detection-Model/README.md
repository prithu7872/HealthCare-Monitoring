In this project, we will classify the provided gene-variation pair and corresponding medical text data into one of the nine categories. We will be working with the Personalized Medicine: Redefining Cancer Treatment data, which consists of two files:

A file containing information about the genetic mutations, available in the workspace with the /Cancer-Detection-Model/training_variants name.
A file containing the clinical evidence that human experts/pathologists use to classify the genetic mutation, available in the workspace with the /Cancer-Detection-Model/clinical_info.txt name.
These data files share a common column named ID, which will be used to merge them at the start of the project.

Each genetic mutation has a unique ID consisting of two fields: Gene and Variation. Based on these two fields and the available clinical literature (textual data), the genetic mutation can be classified into one of the nine different categories, some of which are malignant, and others are benign or passenger. The presence of any malignant mutation in the tumor cell puts the patient at significant risk of having cancer.

The nine categories and their corresponding class labels (1 to 9) are as follows:

1. Likely loss-of-function
2. Likely gain-of-function
3. Neutral
4. Loss-of-function
5. Likely neutral
6. Inconclusive
7. Gain-of-function
8. Likely switch-of-function
9. Switch-of-function

In this project, we will use Python modules to create an ML model that we will use to predict cancer. 