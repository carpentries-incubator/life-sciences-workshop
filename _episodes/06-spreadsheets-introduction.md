---
title: "Spreadsheets: Introduction"
teaching: 10
exercises: 10
questions:
- When should you use a spreadsheet?
objectives:
- Start to understand when spreadsheets are and aren't appropriate
keypoints:
- Spreadsheets can be extremely useful, but they can also cause chaos
---

Professor Daniel Lemire from the University of Quebec, in a popular blog post titled 'You shouldn’t use a spreadsheet for important work (I mean it)', 
states that *"spreadsheets are good for quick and dirty work, but they are not designed for serious and reliable work"*. In his post he cites the
example of Professor Thomas Piketty and his book 'Capital in the 21st Century'. Piketty, aiming for transparency in his work, opening shared the 
underlying datafiles containing his analysis. Unfortunately, he has used Excel to perform tasks such as merging different datasets and interpolating
missing data, and errors were soon found. When corrected, the central thesis of the book was undermined.

So, when are spreadsheets the answer? And in those situations, how best should they be used?

Spreadsheets are excellent at giving you a quick visual picture of your data. Further, they give the ability to change figures and then see the 
immediate effects (so called 'What-if' analysis). They're also simple to use and ubiquitous, used for scientific experiments in schools from an early
age.

The issues created when using spreadsheets for large, complex datasets are obvious. Intuition on what you're looking at breaks down. Connections
between different parts of the data, especially across different tabs, become increasingly difficult to track. Formulae, hidden from view, can
slowly accumulate errors. But that doesn't mean that smaller, easier to handle datasets can't cause problems, or that data under a certain size can
be analysed without any consideration of potential spreadsheets dangers. And the issues range beyond pure analysis. Spreadsheets are often used
as a replacement for lab books, with multiple tabs containing data from different experiments gathered on different days, text annotations used for
ad hoc notes, and entire spreadsheets emailed, opening up all manner of privacy and security issues.

> #### Exercise - Which of the following scenarios are appropriate for spreadsheets?
> 
> 1. A dataset of 100 rows of blood markers for 5 people. The aim is to create a simple plot
> 2. A dataset of 100 rows of blood markers for 5 people. The aim is to fit advanced statistical models and interpolate new values from those models
> 3. A dataset of 1000 rows of blood markers for 20 people. Aim is to create simple plots and create summary statistics (mean, standard deviations, etc)
> 4. A dataset of 10k rows of genetic sequencing data. Aim is to pattern-match and extract key sequences
> 5. The dataset in example 1, but instead of a single file, you have 100 similar files, i.e. you wish to create 100 plots
> 
> > #### Solution
> > 1. Yes
> > 2. Probably not
> > 3. Yes
> > 4. Probably not
> > 5. Probably not
> > 
> {: .solution}
{: .challenge}