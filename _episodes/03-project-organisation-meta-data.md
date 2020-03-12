---
title: "Meta-data"
teaching: 20
exercises: 0
questions:
- What is meta-data?
- Why is it useful?
objectives:
- Understand the concept and importance of meta-data
keypoints:
- Files and folders with meta-data are far more useable than without
---

### What is Meta-data?

Meta-data is **data about data**. It is structured information that describes, explains, locates, or otherwise represents something else. Its purpose is to maximise data interpretation and understanding, 
both by humans and by computers. In other words, its aim is to avoid the details of *what the data is* from being lost, to prevent rendering the data useless as time passes.

The simplest approach to meta-data is to create a simple text file (named, for example, 'README.txt') that resides in the same directory as the data. This text file should be named according to the file-name conventions mentioned above. 
This file is particularly important for projects that involve multiple files, and it should cover various aspects, such as,

- Project level: What is the study? Name, instruments, methodologies, etc
- File or database level: What are all the files? How do they relate to one another?
- Variable level: Fully explain each variable in the spreadsheets, etc
- Processing: What, in general terms, has been done with the data?

Think of this README.txt file as an email to your future self. What will you need to know about these files in, say, 18 months?

In all but the most complex of datasets, this file should take <10 minutes to create.


### Data dictionaries

A more formal version of the simple README.txt is something called a data dictionary. These are repositories of meta-data, containing detailed aspects of the associated data, such as the following,

- Explanations of all files or tables (in a database)
- Field/column definitions and explanations
- Example values, default values, allowed value ranges, and units
- Information on the sources of the datasets
- Information of data types, such as numeric or text
- Any relationships between different fields/columns
- The chosen placeholder for missing values, such as 'NA'


### Internal file annotation

In some cases, file types may offer the ability to include meta-data within the main data file. In these cases, a separate meta-data file may be unnecessary, especially if the file is standalone 
and not part of a group of project files. The simplest example are Word and Excel files. When creating such files, any extra information that will aid in the data’s future use should be included. 
Such aspects to keep in mind include,

- With Word files, include the author's name, date of creation, and project description in the header
- With Excel files, ensure columns and tables are labelled. If the file contains plots, label the axes and give the plot a title. If the file contains multiple tabs, label them appropriately

There are no strict rules on any of the above, and attempting to create such rules for everyone to adhere to may do more harm than good (for example, if the process ends up overly complex and 
bureaucratic). Instead, guiding principles should be used, with the key aspect being kept in mind, namely, that your aim is to ensure the long-term usefulness of the data.