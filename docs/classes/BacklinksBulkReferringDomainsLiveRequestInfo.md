[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / BacklinksBulkReferringDomainsLiveRequestInfo

# Class: BacklinksBulkReferringDomainsLiveRequestInfo

## Implements

- [`IBacklinksBulkReferringDomainsLiveRequestInfo`](../interfaces/IBacklinksBulkReferringDomainsLiveRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](BacklinksBulkReferringDomainsLiveRequestInfo.md#constructor)

### Properties

- [tag](BacklinksBulkReferringDomainsLiveRequestInfo.md#tag)
- [targets](BacklinksBulkReferringDomainsLiveRequestInfo.md#targets)

### Methods

- [init](BacklinksBulkReferringDomainsLiveRequestInfo.md#init)
- [toJSON](BacklinksBulkReferringDomainsLiveRequestInfo.md#tojson)
- [fromJS](BacklinksBulkReferringDomainsLiveRequestInfo.md#fromjs)

## Constructors

### constructor

• **new BacklinksBulkReferringDomainsLiveRequestInfo**(`data?`): [`BacklinksBulkReferringDomainsLiveRequestInfo`](BacklinksBulkReferringDomainsLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IBacklinksBulkReferringDomainsLiveRequestInfo`](../interfaces/IBacklinksBulkReferringDomainsLiveRequestInfo.md) |

#### Returns

[`BacklinksBulkReferringDomainsLiveRequestInfo`](BacklinksBulkReferringDomainsLiveRequestInfo.md)

#### Defined in

[main.ts:140346](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140346)

## Properties

### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Implementation of

[IBacklinksBulkReferringDomainsLiveRequestInfo](../interfaces/IBacklinksBulkReferringDomainsLiveRequestInfo.md).[tag](../interfaces/IBacklinksBulkReferringDomainsLiveRequestInfo.md#tag)

#### Defined in

[main.ts:140342](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140342)

___


### targets

• `Optional` **targets**: `string`[]

domains, subdomains or webpages to get the number of referring domains for
required field
you can set up to 1000 domains, subdomains or webpages
the domain or subdomain should be specified without https:// and www.
the page should be specified with absolute URL (including http:// or https://)
example:
"targets": [
"forbes.com",
"cnn.com",
"bbc.com",
"yelp.com",
"https://www.apple.com/iphone/",
"https://ahrefs.com/blog/",
"ibm.com",
"https://variety.com/",
"https://stackoverflow.com/",
"www.trustpilot.com"
]

#### Implementation of

[IBacklinksBulkReferringDomainsLiveRequestInfo](../interfaces/IBacklinksBulkReferringDomainsLiveRequestInfo.md).[targets](../interfaces/IBacklinksBulkReferringDomainsLiveRequestInfo.md#targets)

#### Defined in

[main.ts:140336](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140336)

## Methods

### init

▸ **init**(`_data?`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `_data?` | `any` |

#### Returns

`void`

#### Defined in

[main.ts:140355](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140355)

___


### toJSON

▸ **toJSON**(`data?`): `any`

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | `any` |

#### Returns

`any`

#### Defined in

[main.ts:140377](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140377)

___


### fromJS

▸ **fromJS**(`data`): [`BacklinksBulkReferringDomainsLiveRequestInfo`](BacklinksBulkReferringDomainsLiveRequestInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`BacklinksBulkReferringDomainsLiveRequestInfo`](BacklinksBulkReferringDomainsLiveRequestInfo.md)

#### Defined in

[main.ts:140370](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L140370)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")