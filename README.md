# k8s-bookshelf
The goal of this app is to be able to use a web ui to search for and save books to a "bookshelf" that
persists a lists of book that you would like to read in the future.

node-api-depo.yaml
  A express js controller that communicates with the front end and data base
  
node-db-depo.yaml
  A mongodb database for storing data on books 
  
vue-bookshelf-depo.yaml
  A Vue.js front end for viewing and searching for books
  
bookshelf-svc.yaml (WIP)
  A service to connect the three deployments. currently cannot find the right endpoints
