[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/deleteAgendaCategory](../README.md) / deleteAgendaCategory

# Variable: deleteAgendaCategory

> `const` **deleteAgendaCategory**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"deleteAgendaCategory"`\]

This is a resolver function for the GraphQL mutation 'deleteAgendaCategory'.

This resolver deletes an agenda category if the user has the necessary permissions.

## Param

The parent object, not used in this resolver.

## Param

The input arguments for the mutation.

## Throws

`NotFoundError` If the user or agenda category is not found.

## Throws

`UnauthorizedError` If the user does not have the required permissions.

## Throws

`InternalServerError` For other potential issues during agenda category deletion.

## Defined in

[src/resolvers/Mutation/deleteAgendaCategory.ts:29](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/deleteAgendaCategory.ts#L29)
