[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / EventVolunteerGroup

# Type Alias: EventVolunteerGroup

> **EventVolunteerGroup**: `object`

## Type declaration

### \_\_typename?

> `optional` **\_\_typename**: `"EventVolunteerGroup"`

### \_id

> **\_id**: [`Scalars`](Scalars.md)\[`"ID"`\]\[`"output"`\]

### createdAt

> **createdAt**: [`Scalars`](Scalars.md)\[`"DateTime"`\]\[`"output"`\]

### creator?

> `optional` **creator**: [`Maybe`](Maybe.md)\<[`User`](User.md)\>

### event?

> `optional` **event**: [`Maybe`](Maybe.md)\<[`Event`](Event.md)\>

### leader

> **leader**: [`User`](User.md)

### name?

> `optional` **name**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]\>

### updatedAt

> **updatedAt**: [`Scalars`](Scalars.md)\[`"DateTime"`\]\[`"output"`\]

### volunteers?

> `optional` **volunteers**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`EventVolunteer`](EventVolunteer.md)\>[]\>

### volunteersRequired?

> `optional` **volunteersRequired**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"Int"`\]\[`"output"`\]\>

## Defined in

[src/types/generatedGraphQLTypes.ts:815](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/types/generatedGraphQLTypes.ts#L815)
