# Multi-table list application for Service Portal
Custom ServiceNow application for generating list of records from multiple different data sources and displaying that in Service Portal. Display content of each record type can be customized along with linking behaviour and link parameters. The application consists of a Service Portal widget that does most of the heavy lifting and a custom table where data sources are defined.  

You can find widget source code here: https://github.com/eemelikoli/sp-adv-list-source-code

# Installation
To be added

# How to use application

### 1. Create a data source for a list.
![image](https://user-images.githubusercontent.com/34348034/93457590-dac99800-f8e7-11ea-889f-657bad25bf0a.png)

#### Basic details
Source name - name for this data source  
ID - unique id for this data source  
Active - inactive sources won't display in the widget  
Short description - description for the source  

#### Data
Table - table where the data for this source is fetched  
Filter - filter that is applied to the table  
Title Field - field that is used as title for the list record  
Primary display fields - fields to be displayed in the list record  
Secondary display fields - fields to be displayed in the list record  

#### Behaviour
Type - Service Portal page or URL  
Page - Service Portal page to link to  
URL - Base URL to link to  
Link Parameter Fields - fields in the source table that can be used as URL parameters  
Link Parameters - Name/value pairs of URL parameters that will be added to the URL when user clicks a record from this source  

#### Presentation
Item icon - FontAwesome icon that is displayed at the left side of the record on the list  
Item template - How the data on the record is displayed in the list      
    
## 2. Add multi-table list widget to Service Portal page
![image](https://user-images.githubusercontent.com/34348034/93462700-65fa5c00-f8ef-11ea-8761-f69689fdac86.png)

Include the multi-table list widget to a Service Portal page  

## 3. In the widget instance options add the list sources you want to use in your list.  
![image](https://user-images.githubusercontent.com/34348034/93463277-3566f200-f8f0-11ea-8b19-e829788b2cbc.png)

Add the list sources you want to display in the widget instance options.

# Upcoming features
Upcoming features will be tracked in issues linked to this repository.
