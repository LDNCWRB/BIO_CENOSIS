# Biocenosis

### Phylo

`... under construction`

Web app to allow scientists and art practitionners to visualize the shapes of genetic evolution on earth. 

##### Features being implemented: 
  - indexing of large data sets for tree reconstruction / potential conflicts resolution
  - D3 interface theming for visualisations
  - 3D Force directed trees
 
### Features

Phylo allows  phylogenetic / genetic / genomic scientists to upload phylogenetic and genetic files of multiple formats ( NEXUS, NEWICK, PHYLOXML, FATA ) from samples to large data sets. The Data is then converted, parsed, flatten, checked, and stored-indexed in db prior to be sent back to client in JSON. Trees is reconstructed on user device with D3 through multiple layout such as Linear, Radial, Force Directed.


### Tech Stack

A combination of Angular with RxJS has been used to build the user interface. On the backend, the app leverages GraphQL with ApolloClient through NESTJS to keep queries lightweight, while securing large data upload through decoupling the server thanks to presigned AWS urls and download (REST). 

##### Front end

Typescript
D3
Angular
RxJs
GraphQL
Apollo Client
Auth0

##### Back end

Typescript
GraphQL
NestJS
REST
AWS
Python 
BioPython Lib
Prisma
PostGress

### Preview
https://user-images.githubusercontent.com/77355721/118704069-a4457380-b80e-11eb-880b-2fbdc2ce3374.mp4

