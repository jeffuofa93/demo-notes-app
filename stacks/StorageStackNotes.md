# Notes on Storage Stack 

- This is creating a DynamoDB table named Notes 
- The table has two fields userID and noteID 
- We are using a composite key with the userId and the noteID to be able to 
grab a specific note from a specific user 

- We also expose the table so it can be queried by other resources 
