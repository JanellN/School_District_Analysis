# School_District_Analysis

## Overview

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Results 
- How is the distirct summary affected? - As shown below, there are not many differences between the original data and the updated data. However, the Passing math score degreased from 74.98% to %74.8%, the passing reading decreased from 85.81% to 85.7% and the overall passing score dropped from 65.2% to 64.1%.

Old

![distrcit old](https://user-images.githubusercontent.com/103154070/187093927-240da604-b3ee-456e-8ba7-e37435937c19.png)

New

![districtnew](https://user-images.githubusercontent.com/103154070/187093938-5c23cfba-9bfe-4e38-9d02-2411da8bf837.png)



- How is the school summary affected? - From the summary statistics you can notice the drastice drop in overall passing percentage for Thomas High School- Dropping from (0.95% to 65.08%.

Old

![ssold](https://user-images.githubusercontent.com/103154070/187093946-4d68131a-7f03-4cfc-b395-13947f4b41e3.png)


New

![schoolsumnew](https://user-images.githubusercontent.com/103154070/187093952-4e2fc8d9-b260-46fa-bb39-65e6b65c8435.png)




- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?
  - This results in Thomas High school being removed from the Top 10 performing schools in the disctrict.
  
- How does replacing the ninth-grade scores affect the following:


![math](https://user-images.githubusercontent.com/103154070/187093972-a4162fd0-21de-444a-9df7-4138526b7f32.png)
![reading](https://user-images.githubusercontent.com/103154070/187093976-9805fcf6-0ef9-43ee-bbb4-061312f69610.png)


- Math and reading scores by grade: Thomas High School's math scores were removed from the ninth grade and all other scores remained the same.

- Scores by school spending: This did not change. Orginally, the spending range for Thomas High School was between $638 per student, and this remained the same after the updates.

- Scores by school size: As shown in the images below we can see that there were no changes to these values.

Old

![sizeold](https://user-images.githubusercontent.com/103154070/187094000-46ce8124-9796-49d8-8820-b0a42841443d.png)

New

![size new](https://user-images.githubusercontent.com/103154070/187093996-e148311c-3131-45b3-844f-00d352e3c7cf.png)

- Scores by school type: As shown in the images below we can see that there were no changes to these values.

Old

![typeold](https://user-images.githubusercontent.com/103154070/187094009-8991aa94-5a21-450e-ba9b-b3b482316eaa.png)

New

![type new](https://user-images.githubusercontent.com/103154070/187094016-6883d35b-66df-4b50-944c-f5b5b45574fe.png)


## Summary

In conclusion, we can see from our findings that removing the ninth grade data causes an impact on results in many faucets of the data.
