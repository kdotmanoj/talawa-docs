[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/createPost

# Module: resolvers/Mutation/createPost

## Table of contents

### Variables

- [createPost](resolvers_Mutation_createPost.md#createpost)

## Variables

### createPost

• `Const` **createPost**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"createPost"``]

This function enables to create a post.

**`Param`**

parent of current request

**`Param`**

payload provided with the request

**`Param`**

context of entire application

**`Remarks`**

The following checks are done:
1. If the user exists
2. If the organization exists
3. If the user has appUserProfile

#### Defined in

[src/resolvers/Mutation/createPost.ts:41](https://github.com/PalisadoesFoundation/talawa-api/blob/9fa6a1c/src/resolvers/Mutation/createPost.ts#L41)
