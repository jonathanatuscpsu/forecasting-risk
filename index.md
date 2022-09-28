Welcome to Forecasting and Risk (BANA 4090)! The main objective of this course is to provide you with the proper foundation to analyze and forecast time series data in the professional setting. This means that in addition to forecasting into the future and evaluating such forecasts we will discuss other topics to prepare you for your journey as an analyst.  A survey of analytical techniques used in forecasting. Techniques include exponential smoothing ARIMA, multiple regression, classification methods and judgement-based methods.  Implementation issues and challenges are discussed.

<!---While covering core concepts like univariate and multivariate forecasting/evaluation of forecasts are critical, I believe we should also cover topics like approaching a forecasting a problem, wrangling with time series data/objects, advanced topics like neural networks for time series, hierarchical data and practical issues when approaching a problem and implementing a solution.--->


<!---This is a course in the analysis of time series data with emphasis on appropriate choice of models for estimation, testing, and forecasting. Topics or methodologies covered include Univariate Box-Jenkins for fitting and forecasting time series; ARIMA models, stationarity and nonstationarity; diagnosing time series models; transformations; forecasting: point and interval forecasts; seasonal time series models; modeling volatility with ARCH, GARCH; modeling time series with trends; and other methods. --->



<!---Many materials are from [Dr. Yan Yu](https://business.uc.edu/faculty-and-research/departments/obais/faculty/yan-yu.html)’s class notes. --->
<!---Thanks for the contribution from previous Ph.D. students. --->
<!---http://jeffgoldsmith.com/IWAFDA/shortcourse_fosr.html --->
 
<!---Framework for approaching forecasting projects --->
<!---Understanding of traditional and modern approaches to forecasting --->
<!---Exposure to common challenges and how to overcome --->
## Class Information
* Name: Zhaohu(Jonathan) Fan 
* Title: PhD Candidate, Department of Operations, Business Analytics and Information Systems 
* Office Information: LCB, Room 3327 
* Email: fanzh@mail.uc.edu
* Office Hours: Monday & Wednesday 11:00 AM to 12:00 PM via WebEx 
(https://ucincinnati.webex.com/meet/fanzh)  and by appointment
 
Communication Policy: Students are encouraged to contact me anytime via email or phone. Please use email as the primary mode of contact.  A response will be given within 36-48 hours.  Please understand that I cannot guarantee an immediate response if you contact me very close to an assignment deadline. 


## Learning Objectives

* Provide students with a foundational knowledge of time series analysis
* Expose students to a number of traditional and contemporary methods in time series and forecasting
* Familiarize students with many of the challenges associated with time series forecasting
* Provide students with practical experience analyzing real-world data and communicating the results


While I will try to focus on the application over the theory to maximize the above objectives, I will provide additional optional reading for those interested in a deeper dive into the theory 🚀. 

## Upon successfully completing this course, you will be able to: 
* have a solid foundation for approaching time series analysis and forecasting projects in the future 
* provide of project for portfolio 
*	practice with R programming language as it relates to time series data 


## Lecture materials (slides) and code demonstrating the relevant methods.

| Module        | Description                                                         |
|:-------------:|:--------------------------------------------------------------------|
| **1**         | **Module 1 – Practical Time Series Analysis (weeks 1-3)**          |
|      [Welcome](Welcome.pdf)                 | •	Why is time series analysis and forecasting important?             |
|       [R lab-I](BANA4090_W1_1_Intro_R.html)             | •	How to approach a forecasting problem 
|          [R lab-II](BANA4090_W2_Visualizing-Time-Series-Data.html)                     | •	Visualization and exploration of time series data |
|         [R lab-III](W3.html)            | •		Wrangling with time series objects|
|                        |•	Decomposition |
|                        |•	Features of time series data
| **2**         | **Module 2 – Forecasting Basics (weeks 4-6)**          |
|     [Forecasting Basics-Part I](Ch3-1.pdf)                    |•	Forecasting process
|      [Forecasting Basics-Part II](Ch3-2.pdf)                     |•	Regression
|        [R lab-IV](BANA4090_Week4_Lab5_Data-Examples_German-Forecasts.html)  |         
|      [R lab-VI](BANA4090_Week5_Lab6_Data-Examples_German-Forecasts.html)   |                 
|   [R lab-VII](BANA4090_Week7_Lab7.html)  |•	Evaluation of model performance
| **3**         | **Module 3 – Forecasting Models (weeks 7-10)**          |
|    [ARIMA-PartI](Ch4-1.pdf)                    |•	AR, MA, ARMA
|     [ARIMA-PartII](Ch4-2.pdf)                   |•	ARIMA
|    [ARIMA-PartIII](Ch4-3.pdf)                      |•	Practical considerations
| **4**         | **Module 4 – Additional Topics   (weeks 11-14)**          |
|     [Additional Topics-Part I](Ch4-2.pdf)                   |•	Hierarchical time series and forecasting many time series
|     [Additional Topics-Part II](Ch5-1.pdf)                    |•	Deep learning for forecasting
|       [Additional Topics-Part III](Ch5-2.pdf)                    |•	Prophet
|                        |•	Anomaly detection
|                        |•	Other R packages for efficient analysis and modeling
|   [Q&A session for Final ](FinalExam.pdf)                         |•	Anomaly detection

## Description of Major Assignments
 
 - **Exam**  – There will be two exams given during class  after we finish module 2 and module 4 to assess grasp of key concepts of time series analysis and forecasting.
 
 - **Assignments**  – 5 take-home assignments will be given throughout the semester. Students will have 2 weeks to complete the assignments. 
 
 - **Discussions**  – The first 14 classes will have in-class labs/discussions. Write-ups from these discussions/labs are to be submitted on Canvas by 11:59pm on the   Sunday after class. If you cannot make the class, these will be posted and submission will be allowed.
 
 - **Project**  – The project is a core component of this course. Students will pick a topic and dataset of their choosing to analyze and forecast with the methods taught in this course (and ideally some additional methods). These topics will be submitted in March and the analyses will be presented during week 15. In lieu of a final exam, students will submit a reproducible markdown/notebook.



<!---http://jeffgoldsmith.com/IWAFDA/shortcourse_fosr.html 
The primary course material is provided via this Jupyter Book resource [:closed_book:](https://bradleyboehmke.github.io/uc-bana-6043/).--->

**Class video, homework and class projects are available in Canvas. Please check homework in Canvas and submit all your homework through Canvas. All announcements are in Canvas.** 





<!---In Class Exercises 
   - Data Sets: data_chicago.csv, data_delta.csv, data_vote.csv
   - Homework:


- Final Project:House prices in Cincinnati.--->

<!---Contributors:  
- Zhaohu (Jonathan) Fan, PhD Candidate in Business Analytics, psujohnny@gmail.com.--->
 

Acknowledgments: I have drawn ideas or readings from the following texts:
 - Rob J Hyndman and George Athanasopoulos, [Forecasting: Principles and Practice (3rd ed)](https://otexts.com/fpp3/)
 - Bradley Boehmke, [UC BANA 6043 Statistical Computing](https://github.com/bradleyboehmke/uc-bana-6043)
 - Ethan Swan, [Python for Data Science](https://github.com/uc-python)
 - And many more.
<!--- Dan Shah, Applied Forecasting--->
<!---Alexander K. Antony,  Forecasting methods--->

