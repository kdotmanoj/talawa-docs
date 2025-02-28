[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/acceptAdmin

# Module: resolvers/Mutation/acceptAdmin

## Table of contents

### Variables

- [acceptAdmin](resolvers_Mutation_acceptAdmin.md#acceptadmin)

## Variables

### acceptAdmin

• `Const` **acceptAdmin**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"acceptAdmin"``]

This function accepts the admin request sent by a user.

**`Param`**

parent of current request

**`Param`**

payload provided with the request

**`Param`**

context of entire application

**`Remarks`**

The following checks are done:
1. Whether the user exists
2. Whether the user has appProfile or not (if not, then the user is not a superadmin).
3. Whether the user accepting the admin request is a superadmin or not.

#### Defined in

[src/resolvers/Mutation/acceptAdmin.ts:20](https://github.com/PalisadoesFoundation/talawa-api/blob/e5f7a9d/src/resolvers/Mutation/acceptAdmin.ts#L20)
