# Analysis script

The function run_analysis performs the following tasks:

- ## function definitions
at first we define some functions for internal usage. An example is the function to retrieve a the label of an activity given and index
```{r}
        find_label <- function(activity_index) {
                as.vector(activity_labels[which(activity_labels$index == activity_index), "label"])
        }
```
