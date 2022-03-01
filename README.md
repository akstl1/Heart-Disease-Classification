# Heart-Disease-Classification

Heart disease is the leading cause of death in the Unites States according to the CDC, killing roughly 660,000 - 700,00 people in the US and approximately 18 million people worldwide annually.

In this analysis, I took a set of patient data and use it to predict a patient's risk for having heart disease so that they can be treated and have better quality of life overall.

To do this, I first analyzed whether the provided data was clean. Luckily, the original data uploader ensured that this data was of high fidelity.

Next, I created a function to fit a given model to provided data and output performance metrics. After splitting the data into test/train sets, I ran three different models on the test/train data to see which performed best.

In the end, the random forest model performed best with accuracy of 96.6% and F1 score of 96.8%. Though not perfect this model catches many cases of heart disease, which in turn can lead to patients getting proper treatment and support.
