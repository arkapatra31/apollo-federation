# repo ~ apollo-federation

### Migrating to Apollo Federation

Apollo Federation Managed Workflow

1. Build separate subgraphs
2. Create Supergraph in Apollo Studio
3. Create the router and update the .env with Apollo key and Apollo Graph Reference
4. Install the Rover CLI and authneticate the Rover
5. Using Rover, publish the subgraphs to the schema registry in Apollo Studio
6. The subgraphs from the schema registry will be composed into a single supergraph schema.
7. The router automatically polls uplink to check changes in supergraph.
8. Understanding Entity and Entity Representation
9. Understanding Reference Resolver
10. Configuring the router and run the router
11. Connecting the router with Apollo studio with the hosted URL
12. Associate 2 subgraphs using Entities :-
    1. Referencing Entity
    2. Contributing Fields to Entities
