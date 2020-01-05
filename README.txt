A script which can be used to approximate error propagation through a function. In other words, when some data with a known uncertainty is put through a (mathematical) function,
this code allows you to calculate the uncertainty on the output of that function. It uses the multi-variable linear appoximation method where all partial derivatives of the function
are calculated (with respect to the input variables).

Data can be provided manually or read from an excel file. 