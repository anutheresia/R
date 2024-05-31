
# This is a comment
"Hello World!"

name <- "John"
age <- 40

name   # output "John"
age    # output 40

str <- "Hello"
str # print the value of str

# Create a vector of pies
x <- c(10,20,30,40)

# Display the pie chart
pie(x)

2
# Create a vector of labels
mylabel <- c("Apples", "Bananas", "Cherries", "Dates")

# Create a vector of colors
colors <- c("blue", "yellow", "green", "black")

# Create a vector of values
x <- c(10, 20, 30, 40)

# Display the pie chart with colors
pie(x, label = mylabel, main = "Pie Chart", col = colors)

# Display the explanation box
legend("bottomright", mylabel, fill = colors)

3
# Get the library.
library(plotrix)

# Create data for the graph.
x <-  c(21, 62, 10,53)
lbl <-  c("London","New York","Singapore","Mumbai")

# Give the chart file a name.
png(file = "3d_pie_chart.png")

# Plot the chart.
pie3D(x,labels = lbl,explode = 0.1, main = "Pie Chart of Countries ")

# Save the file.
dev.off()

4
# Create the data for the chart
H <- c(7,12,28,3,41)

# Give the chart file a name
png(file = "barchart.png")

# Plot the bar chart 
barplot(H)

# Save the file
dev.off()

5
library(readr,dplyr)
library("ggplot2")
library("corrplot")
library("gridExtra")
library("pROC")
library("MASS")
library("caTools")
library("caret")

data <- read.csv("C:/Users/USER/Documentss/data.csv")

For Bioinfo
if (!require("BiocManager", quietly = TRUE))
install.packages("BiocManager")
BiocManager::install(version = "3.18")

DNA Sequence analysis

library("seqinr")

dengue <- read.fasta(file = "sequence (1).fasta")
dengueseq <- dengue [[1]]
length(dengueseq)
table(dengueseq)
GC(dengueseq)
count(dengueseq, 1)
count(dengueseq, 2)

library("seqinr")
leprae <- read.fasta(file = "Q9CD83.fasta")
ulcerans <- read.fasta(file = "A0PQ23.fasta")
lepraeseq <- leprae[[1]]
ulceransseq <- ulcerans[[1]]
lepraeseq # Display the contents of the vector "lepraeseq"
