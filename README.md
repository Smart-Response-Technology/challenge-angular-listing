# challenge-angular-listing
Take-home coding challenge for software developers using Angular.

- The challenge is to be completed using Angular
- The Angular project contained within this repo has been updated with Angular Material
- During the technical interview, this coding challenge is to be reviewed. There is no need to check-in any changes to this repo
- We realize that you have other commitments; complete as many of the user stories as possible, it is not required to finish all


## User Stories
### 1 List Organizations
As a user of the website, I want a list of of the all of the organizations, so that I can view all of them.
  
Notes:
- Display all of the organizations on the page; the mock data has only 30 values
- Data available from mock GET endpoint that has no authentication: https://641b800a9b82ded29d534c2d.mockapi.io/organization  
- Only the name, city and state attributes are to be displayed

### 2 Filter By Organization Name
As a user of the website, I want to filter the list of organizations by name, so that I can quickly find the one I'm looking for.
  
Notes:
- Have input box at top of page that allow the user to enter in text which is then to used to filter the list
- Allow the user to clear the search filter to return to displaying all of the organizations
- Only those organizations that satisfy the search filter are to be displayed

### 3 Details of Organization
As a user of the website, I want to view the details of an individual organization within a modal dialog, so that I can view the phone number.

Notes:
- The MatDialog can be used to displayed the details for the individual organization
