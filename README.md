# This is an example SQL + Javascript + GraphQL interview playground

## Getting Started

#### Initial sever start
```bash
yarn && yarn init-db && yarn start
```

#### If you want to start a server again
```bash
yarn start
```

#### Example GraphQL query
```graphql
{
  users {
    edges {
      node {
        username
      }
    }
  }
}
```