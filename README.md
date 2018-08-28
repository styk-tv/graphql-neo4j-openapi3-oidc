# graphql-neo4j-openapi3-oidc
Query Neo4J with GraphQL through Swagger-built OpenAPIv3 PetStore example with methods protected by OpenIDConnect and JWT tokens

1. Generated default Python3 swagger_server PetStore example at http://editor.swagger.io/
2. Followed instructions to install https://neo4j.com/developer/graphql/ especially about picking up latest version from here https://github.com/neo4j-graphql/neo4j-graphql/releases and dropping in Neo4j 3.1.x /plugins directory
3. Learn about user-defined queries and mutations you can expose https://medium.freecodecamp.org/using-a-graphql-api-for-database-administration-1a5039b43c8f
4. Generated user-defined queries and mutations using this OpenApi to GraphQ bindings generator component https://github.com/graphql-binding/graphql-binding-openapi 
Setup Keycloak our API groups and protect OpenApi OIDC rest/graphql methods with access control based on OIDC JWT token group membership.
Kubernetes neo4j stable chart allows for automatic plugin installation: https://github.com/helm/charts/blob/master/stable/neo4j/values.yaml#L71-L82

I will expand this over next few days. Especially in the context of Kubernetes 
