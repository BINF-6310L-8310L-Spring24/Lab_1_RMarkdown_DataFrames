# Lab_1_RMarkdown_DataFrames
Instructions for Lab #1 on R Markdown and Data Frames

## Purpose 
The purpose of this lab is to get you accustomed to R Markdown in R studio

## Helpful Materials
R Markdown: The Definitive Guide
<https://bookdown.org/yihui/rmarkdown/>

<https://rmarkdown.rstudio.com/>

R Markdown Cheat sheets
<https://posit.co/resources/cheatsheets/?_page=2/>

Conduct the following steps and show me the final product

### Step 1
Install R-Markdown in R-studio

```install.packages('rmarkdown')```

Optional - you can also create PDF files if you want but you need to install tinytex

```
install.packages('tinytex')
tinytex::install_tinytex()  # install TinyTeX
```

### Step 2
Create a new R-Markdown file

Make sure to save it in a directory where you you can put other files

### Step 3

Create a new r data chunk for importing our sample data

Import the file ```GSE164805_series_matrix_edited.txt``` using the ```read.table()``` command and save it as a new variable

_hint_ Our data has a header, don't forget to set that when you call read.table

This is a modified gene expression dataset that we will use later in the semester.

It has been modified from the following paper: "Inflammation and Antiviral Immune Response Associated With Severe Progression of COVID-19" - Zhang et al 2021. We will use the full dataset in a later lab

### Step 4

Conduct the following analyses 

1. Count the number of NAs in the data
2. Get the mean expression value for the individual "GSM5019819"
3. Column "ID_REF" should be a factor, is it one? If not, convert it to a factor.
4. How many levels does column ID_REF have? 


### Step 5

Create a new data chunk with a different name, then complete the following

1. Create a subset of the data that contains only "GSM5019819" and "GSM5019820"
2. Use the plot() function to create a graph of with your new dataset


### Step 6

Knit your document! 


