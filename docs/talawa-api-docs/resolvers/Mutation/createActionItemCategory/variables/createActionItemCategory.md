[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/Mutation/createActionItemCategory](../README.md) / createActionItemCategory

# Variable: createActionItemCategory

> `const` **createActionItemCategory**: [`MutationResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/MutationResolvers.md)\[`"createActionItemCategory"`\]

Mutation resolver function to create a new ActionItemCategory.

This function performs the following actions:
1. Verifies that the current user, identified by `context.userId`, exists.
2. Ensures that the organization specified by `args.organizationId` exists.
3. Checks if the current user is authorized to perform the operation (must be an admin).
4. Checks if an ActionItemCategory with the provided name already exists for the specified organization.
5. Creates a new ActionItemCategory if no conflicts are found.

## Param

The parent object for the mutation. This parameter is not used in this resolver.

## Param

The arguments for the mutation, including:
  - `name`: The name of the ActionItemCategory to be created.
  - `organizationId`: The ID of the organization where the ActionItemCategory will be created.

## Param

The context for the mutation, including:
  - `userId`: The ID of the current user making the request.

## See

 - ActionItemCategory - The ActionItemCategory model used to interact with the ActionItemCategory collection in the database.
 - Organization - The Organization model used to interact with the organizations collection in the database.
 - User - The User model used to interact with the users collection in the database.
 - MutationResolvers - The type definition for the mutation resolvers.
 - findOrganizationsInCache - Service function to retrieve organizations from cache.
 - cacheOrganizations - Service function to cache updated organization data.
 - findUserInCache - Service function to retrieve users from cache.
 - cacheUsers - Service function to cache updated user data.
 - adminCheck - Utility function to check if a user is an admin of an organization.

## Defined in

[src/resolvers/Mutation/createActionItemCategory.ts:46](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/resolvers/Mutation/createActionItemCategory.ts#L46)
