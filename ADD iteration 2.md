# Iteration 2: Identifying Structures to Support Primary Functionality 
### Step 1: Review inputs
| Category | Details |
| -------- | ------- |
| Design Purpose | This is a greenfield system from a mature domain. The purpose is to produce a sufficiently detailed design to support the construction of the system. |
| Primary Functional Requirements | UC-2: Fundamental function of the application <br> UC-3: Directly Supports core business |
| Quality Attributes | QA-1: Performance <br> QA-4 Usability |
### Step 2: Establish Iteration Goal by Selecting Drivers
The goal of this iteration is to address the general architecture concern of identifying stucture to support primary functionality. The following are are the system's primary use cases.
- UC-2
- UC-3
### Step 3: Choose one or more element to design
For this iteration we will be refining the modules. The support of functionality in the system depends on the modules working together, so we are refining this aspect.
### Step 4: Choose one or more design concepts
| Design Decisions and Location | Rationale |
| -------- | ------- |
| Create a database to hold product information | Large volumes of product data can be stored in one place while enabling search and sorts<br><br>Product data can be updated in an effective and clean way<br><br>Data will be assessable to the scanner in order to have functionality|
### Step 5: Instantiate Architectural Elements, Allocate Responsibilites, and Define Interfaces
| Design Decisions and Location | Rationale |
| -------- | ------- |
| Remove text file that current holds product information | Only require one means of data storage |
| Connect database to existing modules | UPC scanner will a tell the cash register what product to query for in database<br><br>Cash register will be in contact with the databse in order to fulfill the query<br><br>Display view will show databse results from the query the cash register will make. Notifying the user about the product |
### Step 6: Sketch Views and Record Deisgn Decisions
| ELEMENT                    | RESPONSIBILITY                                                                  |
|----------------------------|---------------------------------------------------------------------------------|
| Database Access module     | Responsible for allowing user to view database results on cash register display |
| Cash Register Workstation  | The cash register system which has the database and application interface       |
### Step 7: Perform analysis of current design and review interation goal and achiecement of design purpose.
| Not Addressed  | Partially Addressed  | Completely Addressed  | Design Decisions Made During the Iteration  |
|----------------|----------------------|-----------------------|---------------------------------------------|
|                |                      | UC-2                  |                                             |
|                |                      | UC-3                  |                                             |
|                |                      | QA-1                  |                                             |
|                |                      | QA-4                  |                                             |
| UC-1           |                      |                       |                                             |
| UC-4           |                      |                       |                                             |
| UC-5           |                      |                       |                                             |
| QA-2           |                      |                       |                                             |
| QA-3           |                      |                       |                                             |
| CON-1          |                      |                       |                                             |
| CON-2          |                      |                       |                                             |
| CON-3          |                      |                       |                                             |
| CON-4          |                      |                       |                                             |
| CON-5          |                      |                       |                                             |
