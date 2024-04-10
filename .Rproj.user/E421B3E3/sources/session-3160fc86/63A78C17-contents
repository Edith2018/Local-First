
library(tidyverse)
library(here)

#importing data
Penguins_dataset <- read_csv("penguins_data.csv")

#Grouping
Penguins_dataset |> 
  group_by(species) |> 
  count()

#Summarize
Penguins_dataset |> 
  group_by(species) |> 
  summarize(mean_bill_depth = mean(bill_depth_mm, na.rm = TRUE))
