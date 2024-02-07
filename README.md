# Comparing-Optimized-Pre-Processing-for-Discrimination-Prevention-Across-Different-Models
Supervised learning algorithms, increasingly used for decision making in applications of consequence, may at first be presumed to be fair and devoid of inherent bias, but in fact, inherit any bias or discrimination present in the data on which they are trained
The dataset used in the demonstration is the Adult dataset, which contains demographic and employment information about individuals in the United States. The goal is to use the dataset to predict whether income exceeds $50K/yr based on census data.
The dataset includes several features, including age, education, occupation, race, and gender. The protected attributes in the dataset are race and gender, with "White" and "Male" being the privileged groups, and all other races and genders being the unprivileged groups. The demo illustrates how to preprocess the dataset using the AIF360 toolkit to mitigate potential bias in the data, such as disparate impact in employment outcomes based on race or gender.
