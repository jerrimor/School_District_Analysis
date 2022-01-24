# PyCity Schools Challenge 


## Overview of School District Analysis
The PyCity school board has requested analysis be completed for their school districts and schools and students within those districts.  They have provided a large dataset that includes, standarized test scores, math and reading scores.  They are requesting the analysis to determine trends in school performance based on average scores and budgets. The end goal is to make informed decisions on budgets for the upcoming year. 

The task list for the analysis is as follows:

 - A high-level snapshot of the district's key metrics, presented in a table format
 - An overview of the key metrics for each school, presented in a table format
 - Tables presenting each of the following metrics:
 - Top 5 and bottom 5 performing schools, based on the overall passing rate
 - The average math score received by students in each grade level at each school
 - The average reading score received by students in each grade level at each school
 - School performance based on the budget per student
 - School performance based on the school size 
 - School performance based on the type of school


The Challenge specifically requested additional analysis based off a new discovery with the data.  The school board was made aware that the ninth grade class at Thomas High School had some academic dishonesty.  Based off this information, the school board has requested that all ninth grade math and reading scores be deleted and removed from this dataset and analysis.  

The Challenge task list is detailed below. 

 - Replace ninth-grade reading and math scores 
 - The district summary
 - The school summary
 - The top 5 and bottom 5 performing schools, based on the overall passing rate
 - The average math score for each grade level from each school
 - The average reading score for each grade level from each school
 - The scores by school spending per student, by school size, and by school type


## Results of the school district analysis
After the ninth-grade reading and math scores were removed, the summaries and percentages were re-calculated. Below are further details to illustrate what, if any, impact the removal of the scores had on the overall numbers and averages.    

The __district summary__ was not critically impacted by the updates and removal of the scores.  The averages are nearly the same between the two datasets.  

 __Original district summary

![226FA367-A231-4889-AB59-EA470AB5C286](https://user-images.githubusercontent.com/96222437/150700647-705f1407-c018-4920-934e-89daaf69c7da.jpeg)

__After removal of THS 9th graders

![0E917636-8A0B-4A7D-B3D7-07A9A00F41B2_4_5005_c](https://user-images.githubusercontent.com/96222437/150700551-975841fa-ca9e-4b97-a717-3c4f1f00eb1a.jpeg)

The __school summary__ displays significant differences in the last three reported numbers.  The % Passing Math, % Passing Reading, and % Overall Passing numbers fell drastically for the Thomas High School once the ninth grade scores were removed.  A difference of nearly 30% in each of those numbers.  

__Original school summary

![24CEFB8A-60B9-4AFE-A247-34AAE736499D](https://user-images.githubusercontent.com/96222437/150701002-fee87a94-3fc2-4112-b818-16cb59f893e0.jpeg)


__After removal of THS 9th graders__
![CA836B6F-65F4-4CEE-BE87-CD70E24B689C_4_5005_c](https://user-images.githubusercontent.com/96222437/150700689-126be22d-ebd4-4b7f-be5c-ebf2fe898f0b.jpeg)

Once the Thomas High School numbers were re-ran, Thomas High School remains in the top five schools.  Their overall percentages maintain high as the ninth graders were removed and the other three grades were considered.  

Original school summary

![D7B51DE4-AAB0-43A9-9128-6067E0A36B31_1_105_c](https://user-images.githubusercontent.com/96222437/150702220-a67303c9-d61a-4cb2-9e94-1bd9bb29687a.jpeg)

After removal of THS 9th graders

![2D76EB0F-944D-48E2-8935-E997156D9413_4_5005_c](https://user-images.githubusercontent.com/96222437/150702681-161882c8-4d80-442f-9c74-0fa49e1e9a1c.jpeg)



Replacing ninth grade scores outcome to the following measurements. 

Math and Reading scores show evident differences as the 9th graders have a NaN value in both math and reading for Thomas High School. 

Original school summary
Math scores:
![B3DC1B40-BE7A-43AC-93D5-9F737A3C839F](https://user-images.githubusercontent.com/96222437/150703135-ec2b039f-faed-43e0-805e-b7b514b485ae.jpeg)
Reading scores:

![79B5D609-DF09-446D-8D30-187A51D38DAB](https://user-images.githubusercontent.com/96222437/150703168-fede958d-019c-4c2a-9e16-6020a72aafb6.jpeg)

After removal of the THS 9th graders
Math scores:
![3CA0CF97-FB8C-4A98-A92A-6FFE0BD3ACFD](https://user-images.githubusercontent.com/96222437/150703220-4f214dfd-c4aa-4fb8-963f-82bab8ccc76e.jpeg)

Reading scores:
![A5622C06-E431-4A93-90DE-D6F72780A1A2](https://user-images.githubusercontent.com/96222437/150703258-86a35d79-ab99-4d0e-b424-b22435a813ea.jpeg)


Scores by school spending didn't see much changes between the two analysis. 
Original school summary
![93DF3718-BA50-475E-8BEA-B645DD019451](https://user-images.githubusercontent.com/96222437/150703847-8d4dc07a-956d-4c3d-a10a-ed7b889876e5.jpeg)


After removal of the THS 9th graders
![DEFB84F0-15C5-40A1-9199-91E473B091D6](https://user-images.githubusercontent.com/96222437/150703870-ca2167da-e640-48cc-8357-18a5f0493429.jpeg)


Scores by school size had little to no change between the inital analysis and the removal of the ninth graders. 

Original school summary
![0B95E594-9137-4511-AC69-64918BF24935](https://user-images.githubusercontent.com/96222437/150703941-5ba3c64a-56c9-4f8c-a657-0d6953ecb15c.jpeg)


After removal of the THS 9th graders
![ECF618F9-BF66-4F38-844B-F694686C0456_4_5005_c](https://user-images.githubusercontent.com/96222437/150704015-c8e36427-8595-4558-b072-ee678dbf66dd.jpeg)


Scores by school type had little to no changes.

Original school summary
![229F17C3-55DB-4E3A-A428-0EB8AEBBA035](https://user-images.githubusercontent.com/96222437/150703964-c7b27bd1-932f-40ee-a190-d3865bfcf880.jpeg)


After removal of the THS 9th graders

![951C2E84-99B0-4557-9FA1-0CA2E3FECBA3_4_5005_c](https://user-images.githubusercontent.com/96222437/150704021-cb26698b-7cd2-425d-831f-8cb7fee6808c.jpeg)

## Summary

There were several differences with the new numbers after the ninth graders were removed for Thomas High School.  The quickest view into the differences is within the per school summary dataframe.  The drop in the percentage passing and overall percentage passing is very evident.  
Also the drop in scores is very visible in the scores by grade.  The easy to spot 'Nan' value for the 9th graders for Thomas High School shows the drop in scores for that school and that particular grade.  A third visible difference would be a very slight change in the district summary because there were only just over 400 students removed and the entire dataset is nearly 37,000.  The percentages and averages are minimally impacted.  The same goes for a fourth difference in scores by school type and school size.  

