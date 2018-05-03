# Documentation

## Schema design:
## project 
  -title

## tasks
  -start date
  -end date
  -status
  -description
  -title
  -documents
  -tasks as dependencies (hasMany)
  -projectId

## comments
  -userId
  -taskId
 
## users
  -name
  -email
  -password
  -googleauth
  -tasks (hasMany)
  
## documents
  -upload date
  -title
  -link
  -taskId
