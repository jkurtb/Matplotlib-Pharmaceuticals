# Matplotlib-Pymaceuticals
Using Python Matplotlib to Analyze & Generate Results of a Pharmaceutical Study

# Final Report

![scientist-in-laboratory-3735709](https://user-images.githubusercontent.com/65078870/84731367-a6e87a80-af66-11ea-85a6-43f1ccf26b5c.jpg)
Photo credits: Polina Tankilevitch via Pexels 

# Observations and Insights

* The comparative study of Capomulin treatment for squamous cell carcinoma (SCC) involves eight other drugs and a placebo regimen. Each were conducted to an average population of 189 mice. The sample size was not normally distributed. Capomulin drug had the maximum sample size of 230, while Propriva had the smallest sample of 161.
  <div align="center">
  <img width="292" alt="HistoStat" src="https://user-images.githubusercontent.com/65078870/84745653-e1f8a700-af82-11ea-84d0-3af05dd87c54.PNG">
  </div>

* The overall results of the tumor volume (mm3) showed a slightly left-skewed distribution.

  <div align="center">
  <img width="296" alt="HistoTumorVol" src="https://user-images.githubusercontent.com/65078870/84777295-682ae280-afaf-11ea-91ef-42d340ff2df0.PNG">
  </div>

* A total number of 249 mice were tested but this analysis considers only 248, after Mouse ID g989 was dropped due to duplicate time points in the dataset.

* Gender distribution consists of nearly equal number of female and male mice.
  <div align="center">
  <img width="207" alt="PieChart" src="https://user-images.githubusercontent.com/65078870/84745831-2126f800-af83-11ea-856e-27fe22e9a75e.PNG">
  </div>

* Among the four drugs of interest (Capomulin, Ramicane, Infubinol, and Ceftamin), only Infubinol had one outlier data point based on the average final tumor volume.
  <div align="center">
  <img width="476" alt="BoxPlot" src="https://user-images.githubusercontent.com/65078870/84745886-369c2200-af83-11ea-9736-a5a6c4c9074b.PNG">
  </div>
  
* The Mouse Weight and Average Tumor Volume indicators of Capomulin drug had a strong positive correlation with a Pearson's R Value of 0.84, demonstrated by a firm or straight-line of regression.
  <div align="center">
  <img width="302" alt="LinearRegression" src="https://user-images.githubusercontent.com/65078870/84745961-4fa4d300-af83-11ea-8135-8ba3304535ad.PNG">
  </div>

* A randomly selected mouse ID s185, manifested decreasing tumor volume levels as the time point increases while on Capomulin regimen.
  <div align="center">
  <img width="285" alt="LineChart" src="https://user-images.githubusercontent.com/65078870/84746017-5f241c00-af83-11ea-9fda-d7435843773b.PNG">
  </div>

