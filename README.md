# graphql-neo4j-openapi3-oidc
Query Neo4J with GraphQL through Swagger-built OpenAPIv3 PetStore example with methods protected by OpenIDConnect and JWT tokens

1. Generated default Python3 swagger_server PetStore example at http://editor.swagger.io/
2. Followed instructions to install https://neo4j.com/developer/graphql/ especially about picking up latest version from here https://github.com/neo4j-graphql/neo4j-graphql/releases and dropping in Neo4j 3.1.x /plugins directory
3. Learn about user-defined queries and mutations you can expose https://medium.freecodecamp.org/using-a-graphql-api-for-database-administration-1a5039b43c8f
4. Generated user-defined queries and mutations using this OpenApi to GraphQ bindings generator component https://github.com/graphql-binding/graphql-binding-openapi 
5. Use this example https://neo4j.com/developer/graphql/ to create basic queries. Post to /graphql/idl/ endpoint and then use /graphql/ endpoint to retrieve actual data. Use Insomnia rest client.
6. Setup Keycloak our API groups and protect OpenApi OIDC rest/graphql methods with access control based on OIDC JWT token group membership.
7. Kubernetes neo4j stable chart allows for automatic plugin installation: https://github.com/helm/charts/blob/master/stable/neo4j/values.yaml#L71-L82
8. Protecting endpoints based on decorators https://flask-jwt-extended.readthedocs.io/en/latest/optional_endpoints.html
9. Flask Graphene Neo4j: https://github.com/elementsinteractive/flask-graphql-neo4j
10. Python OIDC Client: https://pyoidc.readthedocs.io/en/latest/examples/rp.html
11. Py2Neo4j v4 https://medium.com/neo4j/py2neo-v4-2bedc8afef2

I will expand this over next few days. Especially in the context of Kubernetes 
