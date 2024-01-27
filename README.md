# Analyzing-Amazon-Sales-Data

## About
This repository contains code and the data set information for a data analysis project focused on analyzing Amazon sales data.The project aims to gain insights into sales trends, key matrics and meanigfull relationship between attributes.

## Purpose of the project 
Sales management has gained importance to meet increasing competition and the need for improved methods of distribution to reduce cost and to increase profits. Sales management today is the most important function in a commercial and business enterprise.

## About Data
The dataset was obtained from [Amazon-Sales-Data](https://drive.google.com/file/d/1tvNcSh1Ayfkv7NIE2oKqIMOLlfedNJvM/view). This dataset contains sales transaction with two sales channel are present online and offline.The data contains 14 columns and 100 columns.

This is a table:

| Column                                           | Description Data                               | Type                         | 
|---                                               | ---                                            |  ---                         |
| Region                                           | Geographical region of sales made              | VARCHAR(50)                  |
| Country                                          | Location of the sales                          | VARCHAR(30)                  |
| Item Type                                        | Type of Item Sold                              | VARCHAR(30)                  |
| Sales Channel                                    | Mode of sales                                  | VARCHAR(30)                  |
| Order Priority                                   | Level of Urgency                               | VARCHAR(10)                  |
| Order Date                                       | Date of order placed                           | DATE                         |
| Order ID                                         | unique id of order placed                      | VARCHAR(50)                  |
| Ship Date                                        | Date of order shiped                           | DATE                         |
| Unit Sold                                        | Number of unit sold                            | FLOAT                        |
| Unit Price                                       | Price of each unit                             | FLOAT                        |
| Unit Cost                                        | Cost required for each unit                    | FLOAT                        |
| Total Revenue                                    | Total revenue generated                        | FLOAT                        |
| Total Cost                                       | Total Cost required                            | FLOAT                        |
| Total Profit                                     | Total profit made                              | FLOAT                        |


# ETL
* In excel file there are two date format columns which have text datatype and having error while imorting that csv file to mysql database
* To solve this issue I have use python to transform that column to datetime format which was not able in excel sheet.After that load data in mysql database with python script.









