# Excel-Assignment-II
# WorkOrders Dataset Analysis

## Dataset
The dataset for this analysis can be found [here](https://docs.google.com/spreadsheets/d/1N4zHsmIQ3BGR4SZgnZIH2DLbPKvt1_0RaXG6po41Slk/edit#gid=0). Please make a copy of the file to your local machine for analysis.

## Assignment 1

### Pre-requisites
- MS Excel
- WorkOrders.xlsx

### Scenario
You have been given an Excel file containing details for several work orders taken up by a company.

### Tasks
- Create a new table that contains the valid number of technicians allowed for each service type, as shown below:

| Service Type | Valid Technician Count |
|--------------|------------------------|
| Assess       | 1, 2                   |
| Deliver      | 1, 2                   |
| Install      | 1, 2, 3                |
| Repair       | 1, 2                   |
| Replace      | 1, 2                   |

### What I've Done
- Identified the unique service types (Assess, Deliver, Install, Repair, Replace).
- Determined the valid technician counts for each service type based on the dataset.

## Assignment 2

### Pre-requisites
- MS Excel
- WorkOrders.xlsx

### Scenario
You have been given an Excel file containing details for several work orders taken up by a company.

### Tasks
- Using the table created in Assignment 1, create named ranges for each service type such that each range contains the respective technician counts.

### What I've Done
- Created named ranges for each service type to represent the valid technician counts.

## Assignment 3

### Pre-requisites
- MS Excel
- WorkOrders.xlsx

### Scenario
You have been given an Excel file containing details for several work orders taken up by a company.

### Tasks
- Create a data validation over the existing “Techs” column such that the value in each row is as per the structure defined in the table created in Assignment 1.

### What I've Done
- Implemented data validation for the "Techs" column to restrict values to the valid technician counts for each service type.

## Assignment 4

### Pre-requisites
- MS Excel
- WorkOrders.xlsx

### Scenario
You have been given an Excel file containing details for several work orders taken up by a company.

### Tasks
- Create a pivot table that contains the total revenue and count of services done across all service categories for various technician counts.

### What I've Done
- Created a pivot table to summarize the total revenue and count of services for different technician counts across all service categories.
