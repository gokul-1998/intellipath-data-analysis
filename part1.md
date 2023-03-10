## Data Analysis
    - it is the process of analyzing raw data with various techniques and processes
    - Raw data will be transformed and made easy to visualize and more human readable
- Why data analytics is significant?
    - business use data analysis to grow their business and to make business decisions
- Descriptive Analysis
    - HIstorical analysis of data
    - Answers what happened?
        - like Return on Investment
    - Does not make predictions or directly inform decisions
    - it focuses on summarizing data in a meaningful and descriptive way
- Advanced Analytics
    - makes use of advanced tools,extract data, make predictions and discover trends
    - these tools include
        - classical statistics and
        - machine learning like
            - Neural networks
            - sentiment analysis
            - Natural language processing
    - this informations provides new information about data
    - it answers the question WHAT IF?

## session 2
- What is data analytics?
    - the pursuit of extracting meaning from raw data using specialized computer systems
    - these systems transform, organize and model the data to draw conclusions and identify pattern
- Need for data analysis?
    - priority of top organizations for effective decision making
    - to develop new revenue for every organization
    - to decrease operation cost
- Who are data analysts?
    - deliver values to their companies by taking data ,using it to answer questions and communicating the result to help make the business decisions
    - common tasks
        - data cleaning(perfect enough to process,remove unwanted data)
        - performing analysis
        - creating data visualizations
    - designations
        - Business Analyst
        - operations analyst
        - business intelligence analyst
        - database analyst
- common Tasks
    - cleaning and organizing raw data
    - analysis of all hidden trends found in data
    - big picture view using descriptive statistics
    - creation of dashboards and visualizations
    - presentation of results to clients and internals
- how data moves around in a firm
    - data engineer
        - get data from all the sources
        - spear head 
    - data scientist
        - uses ML,DL,classification to convert data to valid info
    - data analyst
        - responsible for finding trends
        - presentation of data
- Data analytics Lifecycle
    - we follow a cycle to solve critical problems,that may arise while mining data from large data sets,
    - six phases of life cycle
        - discovery
        - data preparation
        - model planning
        - model building
        - communication results
        - operationalize
    - discovery
        - decide what is the problem
        - decide what you want
        - what is the issue
        - what is the domain we are working
        - what kind of industry it is
        - what resources you need?
    - data preparation
        - after collecting the data,extract and transform the data into acceptable format into a place where the data condition,processing will happen(preparation)
    - model planning
        - methods,workflow,model will be used
        - clustering,rules,regression
    - model building
        - start building the algorithm
        - executing the algo
        - optimize the algo
        - get the result as profitable as possible
        - build and execute model, based on planning
        - use existing tools
    - communication results
        - assess what you have done
        - whether this result is a success or a failure
        - redefine the problem, and go through the process again
        - until we get the best value
    - operationalize
        - document the results, even if it is failure or it is a success
- data analytics key roles
    - users
        - end users
    - stake holders
        - investors of the project
        - like the product owner
    - project manager
        - handles the project
        - makes sure the product is quality
    - business analysts
        - apply techniques,variable models to use
    - data engineers
        - process the raw data,
    - db managers
        - handle the data in the storage

## section 3
    - Data analysis with R (i am skipping it)

## section 4 - microsoft excel
- common usage of microsoft excel
    - analysing data
    - calcualting data
    - creating graphs and charts
    - storing huge data for quick reference
- shortcuts
    - ctrl+right (if you are at first cell of a particular row and want to move to the cell where data is present)
    - again if we do (ctrl+right) it will go to last cell in the row where the data is present
    - ctrl+shift+down - will select the entire column

- Excel formulas and functions
    - DATE AND TIME - https://youtu.be/tgMTfUCUm-U?t=11891
        - DATE : Create a valid date from year,month and day
            - =DATE(year,month,day)
        - DAY:Get the dau as a number(1-31) from a date
            - =DAY(date) {Month and year similar}
        - DAYS
            - =DAYS(end_date,start_date)
        - Net Working Days : Get the number of working days between two dates
            - =NETWORKDAYS(start_date,end_days[holidays])
        - NOW/TODAY :Get the current date and time/date
            -   = NOW()
                = TODAY()
        - YEARFRAC: Get the fraction of a year between two dates
            - =YEARFRAC(start_date,end_date,[basis])
