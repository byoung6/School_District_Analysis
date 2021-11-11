#### School_District_Analysis

## 1. Overview of the Project

The purpose of the project is to document evidence of academic dishonesty of the reading and math scores for Thomas High School ninth graders through state-testing standards provided in a CSV file. The goal is to replace the math and reading scores for Thomas High School with "NaNs" and maintain the integrety of the rest of the data. Through replacing the Ninth Grade data, the goal is to determine if the overall pass rates remain consistent. If they do, there is evidence of academic dishonesty.

## 2. Results

    -District Results

The replacement of the Ninth Grade data from Thomas HIgh School with NaN dropped the overall district passage rates to 64.9% versus the originally ran passage rate of 65.2%
![district results](https://user-images.githubusercontent.com/76926631/141382591-7d4b6457-56e9-42ca-8e78-9570b707fd00.PNG)

    -Thomas High School results do not differ to a great extent when the Ninth Graders are omitted.

With the omission of the Ninth Graders of Thomas High School, the overall passing percentages of Thomas High School decreased by 0.11%, the average scores of Thomas High School for math and reading *increased* by 0.06, and the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%.

    -Thomas High School ranking does not change, despite the omission of the Ninth Grade scores.

Thomas High School still maintains an overall high passage rate in both math (97%) and reading (90%), remaining at second overall.
    
![Top ranking schools](https://user-images.githubusercontent.com/76926631/141383985-7236088c-0196-4182-b5aa-c4c4edfecb8c.PNG)

     -Scores by school spending

Average Scores and Passing Percentages do not increase as spending per student increases. With the top performing school receiving $68 less per student, there are more varied factors that account for the differences in top performing and bottom performing. 

     -Scores by schoool size

Large schools have the lowest average scores and passing percentages. There is minimal differences between Small and Medium size schools. The only correlation that can be drawn is a higher student body may have a negative correlation to passage score.

      -Scores by school type


![Lowest performing](https://user-images.githubusercontent.com/76926631/141384295-ea255a5f-0082-441b-aaf9-120fdb7bd63f.PNG)

Charter schools performed better than District schools. The top five overall passing percentages came from Charter type schools, as opposed to the bottom five coming from District schools. Further, Charter schools also had a lower student population and District Schools held a higher student population. 


## 3. Summary

The removal of the ninth grade scores, due to possible academic dishonesty only reinforces Thomas High School's standing as among the top of the district. Throughout the analysis we see that Charter schools and low-to-middle population schools typically fare better than District schools and high population student bodies. Additionally, there is no substantial correlation between school spending and passage rate, which implies alternative reasons or a cap in effective school funding from a state/federal level. 
