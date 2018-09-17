# R-which-function
About which function

The which() function will return the position of the elements (i.e., row number/column number/array index) in a logical vector 
which are TRUE. Unlike the other base R functions,the which() will accept only the arguments with typeof as logical while the others 
will give an error.


# Syntax: which(x, arr.ind = FALSE, useNames = TRUE)

# arrayInd(ind, .dim, .dimnames = NULL, useNames = FALSE)

which (letters == "g")

x <- c("sha", "anusha", "rasool", "sai")
x

which(x=="sai")

which(x!="sai")

which(x=="sha")

which(x!="anusha")

sha <- matrix (1:27,3,3)
sha

which.max(sha)
which.min(sha)
