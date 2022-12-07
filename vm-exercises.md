# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

*Apply the Year over Year growth quick table calculation to a dataset to identify stocks with the highest average closing price*

#### Context

*YoY growth is a common calculation required by business leaders to asses the historical performance at a high level and spot areas for improvement. It is common to include these sort of comparisons in the quarterly and annual reports that listed companies are obliged to publish. The student will master how  to use quick table calculations to identify the best/worse stock from S&P 500 in terms of annual growth.*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

1. Add Date to the Columns pane and Name to the rows pane
2. Add Close to the Columns pane and change the measure type to Average
3. Add the quick table calculation Year over Year growth to AVG(Close) field
4. Order the stocks by % Difference in Avg. Close increasing

#### Exercise question:
* What is the stock with the lowest Year over Year growth of its average close price in 2016?*

#### End goal:

*<img width="1313" alt="Screenshot 2022-12-07 at 22 08 14" src="https://user-images.githubusercontent.com/47775887/206296052-3cd20403-44e1-4187-91ff-214ed06782ff.png">*

## 2nd VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

*Compare the YTD quarterly sales performance and ccompute moving averages across categories *

#### Context

*3 - Comparing YTD and moving averages is critical to assess the status of sales during year and facilitate decision makers to understand the feasability of their targets. *

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

1. Add Year and Quarter of Date to the Columns pane, and 2 Sold Units fields to the Rows pane 
2. Add Country Code to the Color pane
3. Add the YTD total quick table calculation to the (first) Sold Units field
4. Add the Moving Average table calculation to the (second) Sold Units field
5. Edit the table calculation to adjust the Previous periods parameters to 3

#### Exercise question:
*1. How many YTD units have been sold at the end of Q3 2018 in the country with more sales in 2018?*

*2. What is the moving sales average of the last three quarters in Sweden at the end of Q3 2018 ?*


#### End goal:

<img width="625" alt="Screenshot 2022-12-07 at 23 24 38" src="https://user-images.githubusercontent.com/47775887/206309865-42939a2e-fe11-4fad-ac8e-ee2c05197e13.png">

