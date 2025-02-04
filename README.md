# Pecuniary Scripts Library

![Logo](/inputs/logo.png)

A collection of financial scripts to speed up the process of batch processing input lists through screeners and visualizer output generators.

The sequence of steps that these scripts adhere to is as follows:

-Retrieve a list of stock tickers.  
-Iterate them through screening functions.  
-Update list with output from screening functions to generate charts.  

Check back later as material for this project is released.

```mermaid
stateDiagram-v2
Inputs --> Screeners
Screeners --> Charts
Charts --> Inputs

```
