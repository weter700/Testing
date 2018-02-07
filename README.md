# Testing

library(nycflights13)
library(tidyverse)
library(data.table)
library(HardyWeinberg)
library(epitools)
library(readr)

TABELA <- readr::read_csv2_chunked(choose.files())
head(TABELA)
