# AnneLewis_CS
*Data wrangling repo for Anne Lewis Strategies case study*



## people.csv schema
| Column      | Type | Description     | Notes     |
| :---        |    :----:   |          ---: |          ---: |
| email       | string      | Primary email address   | No null values   | 
| code      | string       | Source code   | null values NaN  | 
| is_unsub      | string       | Is the primary email address unsubscribed?   | No null values   |
| created_dt      | datetime       | Person creation datetime   | No null values   |
| updated_dt      | datetime       | Person updated datetime   | No null values   |

## acquisition_facts.csv schema
| Column      | Type | Description     | Notes     |
| :---        |    :----:   |          ---: |          ---: |
| acquisition_date       | date      | Calendar date of acquisition   | No null values   | 
| acquisitions      | int       | Number of constituents acquired on acquisition_date   | No null values   | 


## Requirements
- boto3==1.17.99
- pandas==1.1.3
- numpy==1.19.2

## Installing development requirements
```
pip install -r requirements.txt
```
