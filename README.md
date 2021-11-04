# ConstructionProjectManagerAPP
This is a web-APP that help manages a construction project

Coordination between teams can be difficult when managing construction projects, especially when processing invoices and managing inventories of building materials. A construction project can be changed due a variety of factors, such as commodity price levels, local municipal regulations, as well as changing client requests. This app aims to help teams in a construction project to effectively manage their inventory purchasing. 

## Features: 
1. Able to upload and process .xlsx files
    .xlsx files should follow the following format: 
    1. There should not be merged cells
    2. The first row of the file should be 
    `Price, Material, Unit, Amount, Unit Cost, Total Cost`
2. Display differences between and old .xlsx files
3. Access management: 
    1. Viewers - can only view the content
    2. Commenters - can edit the content for approval 
    3. Editors - can edit and approval commenters' edits 

## Frameworks Used: 
1. React
2. AWS S3, Lambda, API Gateway, DynamoDB