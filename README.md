# liquibase-cosmosdb-demo
Requirements: Download dynamodb-liquibase-<version>.jar Pro extension from here: https://github.com/liquibase/liquibase-commercial-dynamodb/releases and place it in your liquibase/lib directory.

Configure your AWS keys as local environment variables or in your AWS configuration files. You can use these secure credentials instead of a traditional username and password. You must set the following keys:

```
AWS_REGION
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY
AWS_SESSION_TOKEN (optional)
```