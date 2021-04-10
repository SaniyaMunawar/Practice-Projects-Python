# Practice-Projects-Python
Weather Data
Your friend, a rising star in the field of meterology, has called on you to write a script to perform some analysis on weather station data. Given below is a file "resources/ex4.csv", which contains some precipiation data for the month of June. Each line in the file has the format - Date,Precipation (upto two decimal places). Note how the data is seperated using ','. The first row of the file contains headers and should be ignored.

Your task is to complete the getNAvg function that computes a simple moving average for N days for the precipiation data, where N is a parameter. Your function should return a list of moving averages for the given data.

The formula for a k day moving average over a series -  𝑛0,𝑛1,𝑛2,𝑛3....𝑛𝑚 is:
for i = k to m where 𝑀𝑖 is the moving average
 
The skeleton code has been provided below. Edit only the required function.





\begin{align}
M_{i} = M_{i-1} + \frac{n_{i} - n_{i-k}}{k}, \text{for i = k to m }
\\ \text{where $M_{i}$ is the moving average}
\end{align}
