# resume_search

If you launch the exe, In the UI you can give the,
1)	skill sets in the first entry box, 
2)	select the folder where you have the list of all resumes 
3)	select the check box based on your requirement, 
ex1: if only Python,Django -> select Match all skills(this will , if any skill including Python select -> Match any skill (This will result resumes having if Python is found in the resumes) 
but not Django, if the Match all skills option is selected it will skip the resume from the list 
ex2: If in the input Python, Django, SQL are given as input and “Match all skills” is selected the list will give you the resumes matching all the skill set, that is if for any profiles Python and SQL are mentioned but not Django, here the profile will be skipped.
Whereas if “Match any skill” is selected and given the same input of Python, Django, SQL even though the profiles are not having Django but having Python, SQL the resume will be listed.

 
Note: The CSV file will be saved in "matching_resumes_mmddyy_H-M-S" format so that even though the previous csv file is kept opened we can continue using the executable with different skill set, the csv file saves the ouput in a new document.

The document when opened, the header of the csv file has the below heading to understand the listed profiles skill set.
ex: Matching Resumes - (Python, Django, SQL) - (Match All Skills)
We can understand from the header that the given list of resumes are having skill set of all given three skills Python, Django, SQL.

Please let me know if you face any issues or require any inputs in using the executable.
