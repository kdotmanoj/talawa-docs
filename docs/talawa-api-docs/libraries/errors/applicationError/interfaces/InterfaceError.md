[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [libraries/errors/applicationError](../README.md) / InterfaceError

# Interface: InterfaceError

Interface representing the structure of an error.

## Properties

### code

> **code**: `null` \| `string`

The error code, can be null

#### Defined in

[src/libraries/errors/applicationError.ts:8](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/libraries/errors/applicationError.ts#L8)

***

### message

> **message**: `string`

The error message

#### Defined in

[src/libraries/errors/applicationError.ts:6](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/libraries/errors/applicationError.ts#L6)

***

### metadata?

> `optional` **metadata**: `Record`\<`string`, `string`\>

Optional additional metadata associated with the error

#### Defined in

[src/libraries/errors/applicationError.ts:12](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/libraries/errors/applicationError.ts#L12)

***

### param

> **param**: `null` \| `string`

The parameter associated with the error, can be null

#### Defined in

[src/libraries/errors/applicationError.ts:10](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/libraries/errors/applicationError.ts#L10)
