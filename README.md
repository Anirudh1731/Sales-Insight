# Sales-Insight

## Problem Statement

The case study is based on a computer hardware business which is facing challenges in dynamically changing market. Sales director decides to invest in data analysis project and he would like to build power BI dashboard that can give him real time sales insights. As a picture is worth of 1000 words , building a dashboard will be easy for the sales director to gain insights more efficiently. 

## Defining Aims Grid

This is one of the project management tool used to clarify a task and keep the process simple. This tool presents a project in the most concise way.

<p align="center">
  <img src="Screenshot (191).png" width="350" title="hover text">
</p>

## Database Schema
<p align="center">
  <img src="Screenshot (196).png" width="350" title="hover text">
</p>

## Data Modelling (Star Schema)
<p align="center">
  <img src="Screenshot (197).png" width="350" title="hover text">
</p>

## ETL | Data Transformation | Data Cleaning | Data wrangling

### First Transformation
--> The data here needs to be analyzed only for those in India and not for the ones out of India hence we need to remove all the rows which has the location out of India . Here the market column had locations not in India hence we rempved all those data not in India.

--> The transaction columns have 0 and negative values and hence we need to remove it.

---> The transactions sales are in USD and we need to convert it to INR.

## Dashboard 
<p align="center">
  <img src="Screenshot (198).png" width="550" title="hover text">
</p>








