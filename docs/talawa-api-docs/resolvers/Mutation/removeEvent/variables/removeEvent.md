[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/removeEvent](../README.md) / removeEvent

# Variable: removeEvent

> `const` **removeEvent**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"removeEvent"`\]

This function enables to remove an event.

## Param

parent of current request

## Param

payload provided with the request

## Param

context of entire application

## Remarks

The following checks are done:
1. If the user exists
2. If the event exists
3. If the user is an admin of the organization.
4. If the user is an admin of the event.
5. If the user has appUserProfile

## Defined in

[src/resolvers/Mutation/removeEvent.ts:39](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/removeEvent.ts#L39)
