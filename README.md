# Parsing-Text
Analysing .txt files and extract the relevant information and transforming them into .csv and .json formatted files. In this assessement, the task is to analyse the textual data of grants given for IP patent claims which are in XML format. The given text file contains lot of data about the patents ,from this data we have to extract the following information.

Task is to extract the data and transform the data into the CSV and JSON format with the following elements:
1. grant_id: a unique ID for a patent grant consisting of alphanumeric characters.  
2. patent_kind: a category to which the patent grant belongs.  
3. patent_title: a title given by the inventor to the patent claim.
4. number_of_claims: an integer denoting the number of claims for a given grant.
5. citations_examiner_count:  an  integer  denoting  the  number  of  citations  made  by  the  examiner for a given patent grant (0 if None)
6. citations_applicant_count:  an  integer  denoting  the  number  of  citations  made  by  the  applicant for a given patent grant (0 if None)
7. inventors: a list of the patent inventors’ names ([NA] if the value is Null).
8. claims_text: a list of claim texts for the different patent claims ([NA] if the value is Null).
9. abstract: the patent abstract text (‘NA’ if the value is Null)

