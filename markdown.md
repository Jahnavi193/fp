# Introduction to my package

This is the package that I created by my own

# To run the summaries of the dataset, execute

{Dataset}

data(Dataset) summary(Dataset)

summary(Dataset\$mt)

# To get the rows use head command

head(Dataset)

# To list the dataset, use list comand

list(Dataset,7)

# To plot the dataset, use plot command

plot(Dataset)

# To set the generic function for the dataset, use SetGeneric command

setGeneric("myDataset", function(object) 
standardGeneric("myDataset"))

