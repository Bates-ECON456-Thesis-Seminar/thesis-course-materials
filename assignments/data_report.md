# ECON 456: Senior Thesis Seminar

This assignment has two parts. The first part is a data report. The second part is documentation. 

## 1. Data: Raw & Importable Files

The raw data files you initially obtain for your project and from which you clean the data for
analysis are critical. In some cases (although rare), all the data used for a study
come from a single original data file; in other cases, data are taken from multiple original data
files.

Ideally, you will write code that not only reads and cleans the data, but also downloads it from where you got it.

### a. Save a copy of every raw data file, add the file to your .gitignore

You may give the file a new name when you save it in the raw data folder, but other than that the copy you save should be identical to the original version of the data file. The contents and format should not be modified in any way.

Where possible, write code that automates this process. 

You do not want to push your raw data file to GitHub. This is because GitHub is for lightweight code only and raw data files are often very large. Write the name of your data file into your .gitignore file or use a wildcard to ignore all files of a certain type.

_e.g. *.csv means ignore all files that end in .csv_

### b. Enter information about the original data file in your documentation file. (See Data Documention below.)

### c. Create a version of your data in a format that you can can open in a statistical software program like Stata or R.

Occasionally, an original data file is in a format that cannot be read by your statistical software. In those cases,
you need to create a modified version of the original data file that is in a format that can be
read. This modified version of the original data file is called an importable data file.

When you create an importable data file, you should make only the minimal changes necessary
to make it possible for your software to read the data. You should not modify the data in the
file in any way. For example, you should not create new variables, delete variables or
observations, or reshape the data. Although the format in which the data are saved will be
different, **the data in an importable data file should be identical to the data in the original data file.**

This is important to ensure that your work can be completely replicated. You need to write
program files (_.do, .R, .py, etc._) that execute all the processing and analysis of your data
required to generate the results you report in your paper – from the point at which you first
open your original data files, through all the cleaning and processing necessary to prepare them
for analysis, to the procedures that finally generate the results. After you have completed the
project, an interested reader could replicate your study simply by running your command files.
Changes you make to the data when you create an importable version of an original data file
cannot be executed by commands written in a command file; they therefore cannot be
automatically reproduced.

When you create an importable version of an original data file, keep both the original and the
importable version in the raw data folder. If you have many different original data files
from different sources and many different importable data files you many want to create two
subfolders: Original Data and Importable Data within your raw data folder.

Give the importable version of the file a name that reminds you it is the importable version of
the original data file from which it was created. For example, if the original data file is
called _realgdp.xls_, give the importable version a name like *realgdp_import.xls*.

### d. Create a ReadMe file for your raw data folder

The Read Me file is a document that describes the files included in the replication
documentation, and explains how they can be used to replicate the study and reproduce the
results.

For each importable data file that you create, write an explanation in your Read Me file
describing the steps you took to create the importable version from the original data file. This
may be the first time you enter any information (other than the title) in your Read Me file.

Section 2 of the Read Me file documents the changes you make to your importable data files.
For each original data file that you have to modify, you should give a verbal (step-by-step)
explanation of all the changes you made to create the importable version. That explanation
should be written in complete and grammatically correct sentences; it should give the names
of both the original and importable versions of the data file that was modified; and it should be
precise enough to enable someone else to make the same changes to the original data file and
end up with an importable data file identical to the one you created.

You do not need to submit the Read Me file at this stage of the project, but I strongly encourage
you to write Section 2 as you retrieve original data and create your importable and base data
files.

## 2. Data Documentation

For each of your original data files, the Metadata Guide provides the kind of information typically
found in a codebook accompanying a dataset, such as variable definitions and coding, sampling
methods, and anything else a user would need to know to work with and interpret the data
appropriately. In many cases, some or all of the information about an original data file that should
be included in the Metadata Guide is available in an existing, publicly accessible document, such
as a codebook or user’s guide that is provided with the original data file. In these cases, it is not
necessary to include that information in the Metadata Guide. Instead, you may simply put a note
in the Metadata Guide indicating that the information is available in an existing document.

The Metadata Guide should be organized into one or more sections; each section should provide
information about one of your original data files. For each original data file, the Metadata Guide
should include the following information:

- **A bibliographic citation for the original data file:** This citation should be in a format
consistent with the APA editorial style used in the main paper or report on the study. Be
sure to include the hyperlink so that you can locate the dataset again if necessary.

- **The date on which you first downloaded, or obtained in some other way, the original data file:** 
If a DOI is included in the bibliographic citation, it need not be repeated.

- **A verbal (step-by-step) explanation of how an interested reader can obtain a copy of the original data file:** 
    In many cases, this explanation will give the URL of a webpage from which the data can be accessed, along with 
    instructions for downloading from that webpage a file identical to the original data file used in the study. In all cases, 
    this explanation should be complete and precise enough to allow an independent researcher to locate and obtain an
    exact copy of the original data file without any additional information or assistance. _Note: your code may provide this._

- **Whatever additional information an independent researcher would need to understand and use the data in the original data file:** 
The particular information required can vary a
great deal depending on the nature of the original data file in question. In many cases, the
additional information that should be provided about an original data file is often similar
to the kind of information found in a codebook or users’ guide for a data set, such as
variable names and definitions, coding schemes and units of measurement, details of the
sampling method and weight variables, and descriptions of how any imputed variables
were constructed. In some cases, it is also necessary to include information about the file
structure (e.g., the delimiters used to separate variables, or, in rectangular files without
delimiters, the columns in which the variables are stored). Any other unique or
idiosyncratic aspects of the data that an independent user of the data would need to
understand should be explained as well.

#### Questions to answer

The following will help you think about the information you need to include in your Metadata

1. What dataset do you propose to use?
2. Which of the following describes your chosen dataset: single cross-section, repeated
cross-section, panel, time series, other (specify)?
3. What is the level of observation, i.e. what does each row in the data matrix represent?
4. What is the universe (who are all potential observations)? If your data has both a cross-
sectional and time component, focus on the cross-sectional component for this question.
5. How is the sample selected from the universe?
6. At what level is it representative?
7. If the data has a time element, what time periods are available?
8. Will you need to further limit the observations in your analysis sample so that they are
appropriate for your question? Explain.
9. Do you anticipate changing the unit of analysis, for example, by aggregating up (e.g.
people to households, firms to industries, people to geographic areas)? Explain.
10. Are both the dependent and independent variables from your research question available
in the dataset, or can they be built from the dataset? Explain.

### Submission guidelines

Push all code, readme, and documentation files to the appropriate folders in your GitHub repository. Give all file's descriptive names.