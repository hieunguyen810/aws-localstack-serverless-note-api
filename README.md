# Example API using Nodejs, Localstack, AWS-SDK, DynamoDB and serverless framework.

### Deploy
``` sls deploy ```

### Create note:
``` serverless invoke local --function noteCreation --data {"title":"monday", "text":"coding"} --raw ```

### List all notes:
``` serverless invoke local --function listNotes ```

### List specific note with id 
``` serverless invoke local --function noteDetails --data 'id' ```
