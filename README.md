# Pewlett-Hackard-Analysis
## Overview of the analysis
The analysis was done so that the manager would get an understanding of staff retirement and its impact within the coming months and years. The analysis will allow the manager to know how many positions will be impacted as well as the number of non retiring employees that will be eligible to fill those roles i a mentorship program is put in place.
## Results
  * The company currently has 1549 employees eligible for mentorship.
  * There are 72458 current unique employees (with titles).
  * There are only 2 retiring managers. Most of the retirees will be senior engineer's (25916) and senior staff (24926)
  * The company will be unable to replace all retiring employees with the mentorship program, given it's current parameters.
## Summary
There is are 72458 employees retiring with 1549 employees eligible for the proposed mentorship program. THe company will be unable to replace the retiring staff. The company will have to source employees externally if they intend to fill most positions.
* Q1![Retiring Employees Count](https://user-images.githubusercontent.com/99148657/164766717-f680ba4c-6bfc-41fe-ab29-8ef1e26f6bf3.PNG)
          SELECT count(emp_no) as Retiring_Employees
          FROM unique_titles;
 * Q2 ![Mentorship Employees](https://user-images.githubusercontent.com/99148657/164767561-da62b9cc-e270-422e-97ce-bac9de19786c.PNG)
 
          SELECT count(emp_no) as Eligible_Replacements
          FROM mentorship_eligibility;
