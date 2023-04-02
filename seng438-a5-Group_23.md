**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  | Hamza Niaz |
|                 | Bilal Pasha |
|                 | Yousef Hammad |
|                 | Issam Akthar |

# Introduction

In this lab assignment, students were introduced to the fundamental concepts of reliability assessment and failure data analysis in software testing. The goal was to understand the importance of tools such as C-SFRAT and the Reliability Demonstration Chart with the help of Excel and to explore the reliability growth testing that helps identify the changes in the product over time. Additionally, the lab introduced the concept of failure data analysis and its significance in preventing future failures. The lab also focused on the use of two new software systems, C-SFRAT and RDC-11, for software failure data analysis and provided a comparison of their results. Through these activities, students gained a better understanding of the role of reliability testing in software development.

# Assessment Using Reliability Growth Testing 

For this part of the lab, we use the C-SFRAT software. C-SFRAT stands for "Software Failure Reporting and Analysis Tool," and it is a software system used for analyzing and reporting software failures. C-SFRAT is designed to help identify, document, track, and manage software issues and defects that arise during software development and testing.

C-SFRAT works by allowing software testers to enter information about each software failure or issue that occurs, including details such as the date, time, location, and severity of the problem. This information is then stored in a centralized database, which allows developers and testers to analyze the data to identify patterns and trends in software failures.

C-SFRAT also provides reporting and analysis tools that allow testers to generate charts and graphs to visualize the data and identify potential areas for improvement in the software development process. By using C-SFRAT, software development teams can more effectively identify and address software defects and issues, leading to more reliable and higher quality software products.

The image below shows all the models for this set of failure data.

![](./media/7.png)

The image below shows all the best models that the predicted the failure rate.

![](./media/6.png)

The system's data was studied up to and including error 16, to remove the decline after this peak and enable better consistency in subsequent tests. The failure intensity peaked at about the 16th error, and the failure rate played a role in removing specific data points from subsequent analyses. Without knowing the number of components in the system being tested, including both the total number of components and the number that failed, a reliability graph could not be produced. However, the software failure analysis approach using diverse graph data was helpful in evaluating the system's genuine reliability and dealing with numerous considerations and circumstances that may be causing the reliability or lack thereof.

Below are some graphs that helped us visualize the failure intensity and time intervals that they were happeing at.

![](./media/1.png)

![](./media/2.png)

By demonstrating how these significant variations in the MTTF lead to abrupt graph shifts that frequently place the data in the failure region or well outside the bounds of the graph. These domain boundaries were chosen in order to guarantee the best fit, and when they were altered, they were further narrowed depending on graph behaviour. As a result, an MTTF was chosen as the best-fit MTTF for this data set since it permits the most data points to fall into the passing zone without stretching the graph. This approach to software analysis is very helpful for better understanding how different software parameters affect the system's reliability. This method clearly has a significant benefit over certain others because it requires significantly less graphed data to collect the statistics needed for the reliability study. Nevertheless, this is limited by the need for a user to manually find the MTTF of best fit, even if it is theoretically possible to have the system generate it based on calculations and patterns data to anticipate the best fit line for the data set.

# Assessment Using Reliability Demonstration Chart 

In this analysis, three plots were created to visualize the reliability of the system using the provided failure data as input. The first plot shows the MTTFmin, which suggests an acceptable trend for the FIO without heavily diving into the reject range. The second plot shows the half MTTF, where the parameters were adjusted accordingly, resulting in a trend that dives more within the reject range. The third plot shows the twice MTTF, where the parameters were adjusted for twice the initial MTTF, resulting in a trend that dives more within the acceptable range. The changes made in the plots correspond to the number of acceptable failures, which affects the data points in the accept or reject region.

![](./media/5.png)

![](./media/4.png)

![](./media/3.png)

The article discusses the significance of the variations in the MTTF and how it affects the reliability of a software system. The domain boundaries were narrowed down depending on the behavior of the graph to ensure the best fit. An MTTF value was selected as the best fit for the data set to enable most data points to fall into the passing zone without stretching the graph. This approach requires less graphed data, making it beneficial for understanding how different software parameters affect the system's reliability. However, it is limited by the need for a user to manually find the MTTF of best fit, even though it is possible to have the system generate it based on calculations and pattern data.

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
