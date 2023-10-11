# major-interest
This notebook cleans and processes anonymized student interest data collected from a major/minor fair. 

The inputs are a csv file of Google form responses and a spreadsheet that lists the majors and minors of each department. This script exports a csv file for each department containing all the students who expressed interest in at least one or their majors or minors. It also exports a csv file for each pre-professional advising office containing students who expressed interest. These are sent to their respective offices/departments for further communication.

This notebook covers the data cleaning phase of the data cycle; there were mismatches between the options listed in the Google form and the majors/minors listed in the department sheet that had to be corrected. This notebook covers the data processing phase, where the singular csv file of student responses was processed into a few dozen spreadsheets organized by the interests they selected in the Google form.
