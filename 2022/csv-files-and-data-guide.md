# Guide to Using the CSV Files and Data

The creative commons license that governs use of this content can be found here: https://cdla.dev/permissive-2-0/

 

## Survey Reference Model

The survey reference model (SRM) contains the survey instrument and instructions for programming the survey. Column Headings in this tab are defined as follows.

 

- **Page or Section.** The Page within Survey Monkey that contains the content defined by the SRM.

- **Q #. Question Number.** A sequential integer value that aligns with how Survey Monkey assigns question numbers during programming.

- **R #. Response Number.** Values (generally numeric integers) that conform to how Survey Monkey will encode response values.

- **Questions and Responses.** Each question and allowable responses to each question. Also can contain contextual information such as the introduction to the survey or instructions to the respondent.

- **Show/Hide Rules and Logic.** Business rules for screening/disqualifying respondents and navigation through survey questions based on responses.

- **Survey Review/Coding Notes.** Commentary on how to addressing survey programming.

- **Other Column Headings.** Other column heading may be included, primarily to reference past surveys or contributions by survey partners.

 

## Filtering and Screening Criteria

The questions and responses that were used by Linux Foundation Research to define what responses to "Keep" and which responses to "Filter Out" for the purpose of our analysis and reporting.

 

# Raw Data Spreadsheet

The Raw Data Spreadsheet (RDS) contains the a numeric encoding of the raw survey data. Basic data quality analysis to remove auto-generated and inappropriate responses has already been performed. However, this dataset does include partial completes from respondents who were later disqualified. For more information on screening and disqualifications, see the tab on Filtering Criteria. Row/Column heading conventions in this tab are as follows. All personal or private information has been removed from this dataset.

 

- **Row 1.** Columns contain the first occurrence of the question number (Q#) that corresponds to the survey question asked as defined in the SRM. Multiple response variables have multiple cells and underscores denoting each of the response options.

- **Row 2.** Columns contain the first occurrence of the name of the survey variable or the survey question asked. Unlabeled row 2 blank "child" cells belong to the "parent" question cell to their left.

- **Row 3.** The response description to the question that was asked. The number of columns per variable (Q#) varies depending upon the type of variable and responses defined for the variable. Single response variables (SRVs) require the respondent to select just one response and the response values are typically shown in one column. Multiple response variables (MRVs) allow the user to select one or more responses so each response for an MRV has its own column.

- **Row 3 SRVs.** Single response variable (SRV) responses contain the word "Response" in row 3 under the question # and question description and are numerically rendered in a single column following the encoding defined in the SRM. If the SRV includes an "Other (please specify)", "None of the above (NoTA)", or "Don't know or not sure (DKNS)" a "0" is shown. In the case of an "Other (please specify)" response that requires a user input, a second column labeled in row 3 as "Other (please specify)" is provided that contains an alphanumeric input.

- **Row 3 MRVs.** Multiple response variable (MRV) responses each have their own column as do any MRV "Other (please specify)" and "None of the above" or "Don't know or not sure" responses. "None of the above" or "Don't know or not sure" responses are encoded with a "0".
