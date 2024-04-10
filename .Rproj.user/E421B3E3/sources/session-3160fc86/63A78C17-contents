
library(tidyverse)
library(here)

#importing data
Penguins_dataset <- read_csv("penguins_data.csv")

#Grouping
Penguins_dataset |> 
  group_by(species) |> 
  count()
