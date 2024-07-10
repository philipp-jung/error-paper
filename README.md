# Error Paper

In the data cleaning space, errors are
a) either not generated and originate from a static dataset, or
b) are generated, but in a fashion that is not complex enough to be realistic.

## Experiments
We take the datasets flights, beers, hospital and rayyan. We then generate different erroneous version, clean them with `HoloClean` and `Baran`, and demonstrate that the correction performance depends on the distribution and type of erroneous values.
