[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [utilities/reuploadDuplicateCheck](../README.md) / reuploadDuplicateCheck

# Function: reuploadDuplicateCheck()

> **reuploadDuplicateCheck**(`oldImagePath`, `newImagePath`): `Promise`\<`boolean`\>

Checks if a user or organization is attempting to re-upload the same image.

## Parameters

• **oldImagePath**: `null` \| [`TypeImagePath`](../type-aliases/TypeImagePath.md)

Path of the current image (could be a string, URL request object, or buffer object).

• **newImagePath**: [`TypeImagePath`](../type-aliases/TypeImagePath.md)

Path of the new image being uploaded (could be a string, URL request object, or buffer object).

## Returns

`Promise`\<`boolean`\>

Promise that resolves to true if the images are identical, false otherwise.

## Remarks

This is a utility method.

## Defined in

[src/utilities/reuploadDuplicateCheck.ts:48](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/utilities/reuploadDuplicateCheck.ts#L48)
