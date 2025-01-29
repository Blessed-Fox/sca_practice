
notes <- path to anova data
analysis <- aov(wordcount ~ condition, data = notes)
summary(analysis)