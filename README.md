# Fish_Toxicity_Problem
Fathead Minnow Toxicity using QSAR Analysis

The approach of quantitatively studying chemical structures & their relationships with other chemical structures as well as carbon-based biological structures or organisms is called QSAR analysis which stands for Quantitative Structure-Activity Relationship.



In this dataset groups of Pimpephales Promelas, commonly known as the Fathead Minnow, were exposed to 908 chemicals to predict acute aquatic toxicity towards the fish. Within the dataset there are 908 observations, six input variables, and one target variable. They are as followed:

CIC0 : Complementary Information Content index (neighborhood symmetry of 0-order)
SM1_Dz(Z) : Spectral moment of order 1 from Barysz matrix weighted by atomic number
GATS1i : Geary autocorrelation of lag 1 weighted by ionization potential
NdsCH : Number of atoms of type dsCH
NdssC : Number of atoms of type dssC
MLOGP : Moriguchi octanol-water partition coeff. (logP)
[Output or Target Variable]

LC50 [-LOG(mol/L)]: The concentration proving lethal to 50% of the test population when exposed to the chemical at a duration of 96 hours
Data was pulled from the UCI repository: https://archive.ics.uci.edu/ml/datasets/QSAR+fish+toxicity



Relevant Papers: M. Cassotti, D. Ballabio, R. Todeschini, V. Consonni. A similarity-based QSAR model for predicting acute toxicity towards the fathead minnow (Pimephales promelas), SAR and QSAR in Environmental Research (2015), 26, 217-243; https://doi.org/10.1080/1062936X.2015.1018938



The purpose of this project is to take note of any statistical observations and variable correlations, provide visualiztions, and use multivariate analysis to predict concentrations of chemicals that would be lethal for the fathead minnow.
