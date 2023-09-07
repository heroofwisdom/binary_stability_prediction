
# Binary Compound Stability Prediction

This project was a imaginary scenario with for a materials informatics company. A client is interested in testing our technology's ability to predict a functional property from material composition. The idea behind this proof of concept is to use data to solve a canonical thermodynamics problem: given a pair of elements, predict the stable binary compounds that form on mixing. 

### Data Information

The customer provided roughly 2500 element pairs as training data. 

The in-house data science team has suggested training labels that are a discretization of the 1D binary phase diagram at 10% intervals. 

For example, the label for OsTi ([1.0,0.0,0.0,0.0,0.0,1.0,0.0,0.0,0.0,0.0,1.0]) translates into the following stable compounds:

● Os 1.0 Ti 0.0 aka Os,

● Os 0.5 Ti 0.5 aka OsTi 

● Os 0.0 Ti 1.0 aka Ti

### Business Presentation

There is an additional slide deck containing a short business presentation on the project to an imaginary VP of R&D and CRO.

