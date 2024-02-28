## Methods & Data

For this phase of your project, you will complete the following assignments.
1. Presentation: Methods & Data due 3/14
2. Thesis: Methods & Data due 3/7 and 3/14

1. Presentation: Methods & Data. You will prepare a brief presentation summarizing your
methods and data. The presentation should be 2-5 minutes and no more than 3 presentation
slides (not including a “works cited” slide). The presentation will be followed by 5-10
minutes of questions and discussion with the class. You will be assigned a presentation date
on Oct 30. Please share your slides with Prof Bird before the start of class on your
presentation date either as Google Slides or as a PDF via email.
2. Thesis: Methods & Data . This assignment entails the completion and submission of three
components:
    1. Methods & Data [Documents];
    2. Data Appendix [Documents];
    3. Data summary command file (summary.do) [Command].
    where [brackets] denote where this file(s) should be saved in your folder in Etna.

1. Methods & Data. The Methods & Data section should include subsections that describe
your model specification as well as data and summary statistics.
- The Methods subsection should specify your regression equation; classify explanatory
variables as variables of interest or controls; and indicate the expected sign of the
coefficients of the variables of interest. This section should be brief, but provide all
relevant information (2-3 pages).
- Precisely define the dependent variable and specify (write out) your regression
equation. Use the Word equation editor to produce a presentable equation.
Provide justification for your functional form and motivation for any interacted or
quadratic terms.
- Give each variable a transparent name that is clear, but not too long. This should
be the same variable name used in your programming language/R.
- Define all the explanatory variables included in your regression equation. Devote
most of this section to your variables of interest. For all dummy variables, state
the omitted condition. Refer the reader back to variable definitions or summary
statistics table when necessary. Avoid redundancies.
- Indicate the expected sign for each regression coefficient -- positive, negative, or
ambiguous -- and provide a brief explanation supporting your expectation. Focus
primarily on your variables of interest and on the most critical (in terms of
avoiding omitted variable bias) control variables. You do not need to discuss
expectations for all control variables.

- The Data subsection provides a description of your analysis data. This subsection should be
concise (1-4 pages, including tables; tables should be placed after the text that describes the
table) and provide the reader with all the relevant information needed to understand your
methodology and interpret your empirical results. Avoid overuse of first-person narrative.
Once you have completed your Data Appendix, the details to include in this section should
become clear. In general, it should include:
- Data Description. You should provide the source(s) of the data you are using and the period
it covers. Describe whether you have a panel, cross-sectional or time series; what the unit
of analysis is (individual, state, county, province, nation, etc.); and how many observations
you have. Provide only the most relevant information here and direct the reader to the
Metadata Guide or supplementary data information if necessary.
- Variable Descriptions Table. A table providing variables names, their descriptions, and
units of measurement. Do not copy and paste this table from your programming language (for example, from a
codebook command). It should be formatted in Word or Excel to be easily readable.
- Summary Statistics.
- Provide a table of summary statistics (mean, standard deviation, max, min, etc) of
the dependent variable and all other explanatory variables.
- Again, do not copy and paste this table from your programming language. It should be formatted and easy
to read.
- Report the value in the summary that is the most difficult to believe – that makes
you wonder if it is correct. The maximum value might look too big, or the minimum
too small, or the mean too big or too small. It may in fact be wrong, so you might
want to confirm that it is correct. If the value is correct, then briefly explain why.
- Report any dummy variables that are “turned on” (a value of 1) or “turned off” (a
value of 0) for only a very few observations, say, 5 or less. Does this suggest
limitations for you analysis?
- Report any quantitative variables that have little variation – their values do not
change much. This should be clear after completing the Data Appendix. If you find
a variable with very little variation, how will it affect your analysis?
- Are any of your variables very highly correlated? If so, why? How will this high
degree of correlation impact your ability to estimate causal effects?
- Discuss any limitations of the data discovered during the completion of your Data
Appendix or the above exercises, such as missing variables, missing observations, small
number of observations, etc. Report other obvious shortcomings (i.e. no income data; no
men interviewed, only people attending school interviewed, etc.). You may want to
highlight the important limitations (e.g. those that you might address in the discussion of
results section of your final paper) in the body of the paper and put the rest in a footnote.
It is useful to think about what the ideal dataset would be for the hypothesis you want to
test and compare your data to it.
- Remember to include only the information most relevant to your analysis in the body of
the text and direct the reader to the Data Appendix for additional information if needed or
relegate some additional information to a footnote. This means that you should only include
detailed discussions of variables that you intend to be the focus of your analysis.
Bates College Econ 456C Senior Thesis Seminar Fall 2023

Methods & Data Formatting Guidelines:
Your completed Methods & Data document must meet the following requirements:
- The Methods & Data section must be submitted as a Microsoft Word document prior to the
deadline.
- Please title the document “Methods & Data – Last Name” (where “Last Name” is replaced
with your last name).
- The Methods & Data section should be about 3 to 7 pages, including tables.
- The document should be formatted as follows:
- 12 pt. Garamond or Times New Roman font
- 1-inch margins
- Double spacing
- Page numbers in right-hand corner
- Title and name on first page (or title page)
- Chicago style citations

2. Data Appendix. The Data Appendix is a document that serves as a codebook for the
analysis data files. It should be saved in the Documents folder. The Data Appendix
should provide information about every variable in your analysis data file, including
definitions and coding (for all variables), summary statistics and histograms (for
quantitative variables), and relative frequency tables and charts (for categorical
variables). When you construct your Data Appendix, you are likely to learn things about
your data that you should know before you begin your analysis. So you should not begin
the analysis until after you have constructed your Data Appendix. The Data Appendix
should be divided into sections, each of which provides information about one of the
variables in the analysis data file. Some of the information is the same for all variables;
other parts of the information depend on whether the variable is quantitative or
categorical. See below for more details.
- For every variable
- The name of the variable and a complete definition (including as
appropriate, for example, coding and/or units of measurement, the wording
of a survey question the variable is based on, or adjustments made for
inflation or PPP).
- The name(s) of the original data file from which the variable was extracted,
or from which the variables used to construct it were extracted, and the
names of the variables extracted from the original data files.
- The number of observations with valid values for the variable, and the
number of observations with missing values.
- For quantitative variables
- Basic summary statistics, including the mean, standard deviation, minimum,
25th percentile, median, 75th percentile, and maximum.
- A histogram and/or a box plot.
- For categorical variables
- A frequency table.
- A bar chart illustrating the frequency distribution.
- For every variable: After completing the above tasks, provide a brief (2-5 sentence)
reflection. What stands out? Is there anything hard to believe?
- The Data Appendix must be submitted on Lyceum as a PDF prior to the deadline
(Nov 9 at 12pm). Please title the document “Data Appendix – Last Name” (where
“Last Name” is replaced with your last name).
3. Summary.do command file. Write a .do file to generate all the descriptive statistics,
tables and figures needed for the Data Appendix. These should be created using your
analysis data. Give this command file the name Summary.do and save it in your
Command Files folder. Remember, for full credit all command files should be fully
commented and easily readable