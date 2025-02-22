[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / DataforseoLabsErrorsResultInfo

# Class: DataforseoLabsErrorsResultInfo

## Implements

- [`IDataforseoLabsErrorsResultInfo`](../interfaces/IDataforseoLabsErrorsResultInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](DataforseoLabsErrorsResultInfo.md#constructor)

### Properties

- [datetime](DataforseoLabsErrorsResultInfo.md#datetime)
- [error\_code](DataforseoLabsErrorsResultInfo.md#error_code)
- [error\_message](DataforseoLabsErrorsResultInfo.md#error_message)
- [function](DataforseoLabsErrorsResultInfo.md#function)
- [http\_code](DataforseoLabsErrorsResultInfo.md#http_code)
- [http\_method](DataforseoLabsErrorsResultInfo.md#http_method)
- [http\_response](DataforseoLabsErrorsResultInfo.md#http_response)
- [http\_time](DataforseoLabsErrorsResultInfo.md#http_time)
- [http\_url](DataforseoLabsErrorsResultInfo.md#http_url)
- [id](DataforseoLabsErrorsResultInfo.md#id)

### Methods

- [init](DataforseoLabsErrorsResultInfo.md#init)
- [toJSON](DataforseoLabsErrorsResultInfo.md#tojson)
- [fromJS](DataforseoLabsErrorsResultInfo.md#fromjs)

## Constructors

### constructor

• **new DataforseoLabsErrorsResultInfo**(`data?`): [`DataforseoLabsErrorsResultInfo`](DataforseoLabsErrorsResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IDataforseoLabsErrorsResultInfo`](../interfaces/IDataforseoLabsErrorsResultInfo.md) |

#### Returns

[`DataforseoLabsErrorsResultInfo`](DataforseoLabsErrorsResultInfo.md)

#### Defined in

[main.ts:77142](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77142)

## Properties

### datetime

• `Optional` **datetime**: `string`

date and time when an error occurred
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2019-11-15 12:57:46 +00:00

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[datetime](../interfaces/IDataforseoLabsErrorsResultInfo.md#datetime)

#### Defined in

[main.ts:77119](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77119)

___


### error\_code

• `Optional` **error\_code**: `number`

error code

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[error_code](../interfaces/IDataforseoLabsErrorsResultInfo.md#error_code)

#### Defined in

[main.ts:77123](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77123)

___


### error\_message

• `Optional` **error\_message**: `string`

error message or error URL
error message (see full list) or URL that caused an error

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[error_message](../interfaces/IDataforseoLabsErrorsResultInfo.md#error_message)

#### Defined in

[main.ts:77126](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77126)

___


### function

• `Optional` **function**: `string`

corresponding API function

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[function](../interfaces/IDataforseoLabsErrorsResultInfo.md#function)

#### Defined in

[main.ts:77121](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77121)

___


### http\_code

• `Optional` **http\_code**: `number`

HTTP status code

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[http_code](../interfaces/IDataforseoLabsErrorsResultInfo.md#http_code)

#### Defined in

[main.ts:77133](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77133)

___


### http\_method

• `Optional` **http\_method**: `string`

HTTP method

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[http_method](../interfaces/IDataforseoLabsErrorsResultInfo.md#http_method)

#### Defined in

[main.ts:77131](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77131)

___


### http\_response

• `Optional` **http\_response**: `string`

HTTP response
server response

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[http_response](../interfaces/IDataforseoLabsErrorsResultInfo.md#http_response)

#### Defined in

[main.ts:77138](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77138)

___


### http\_time

• `Optional` **http\_time**: `number`

time taken by HTTP request

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[http_time](../interfaces/IDataforseoLabsErrorsResultInfo.md#http_time)

#### Defined in

[main.ts:77135](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77135)

___


### http\_url

• `Optional` **http\_url**: `string`

URL that caused an error
URL you used for making an API call

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[http_url](../interfaces/IDataforseoLabsErrorsResultInfo.md#http_url)

#### Defined in

[main.ts:77129](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77129)

___


### id

• `Optional` **id**: `string`

id of the task

#### Implementation of

[IDataforseoLabsErrorsResultInfo](../interfaces/IDataforseoLabsErrorsResultInfo.md).[id](../interfaces/IDataforseoLabsErrorsResultInfo.md#id)

#### Defined in

[main.ts:77114](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77114)

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

[main.ts:77151](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77151)

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

[main.ts:77177](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77177)

___


### fromJS

▸ **fromJS**(`data`): [`DataforseoLabsErrorsResultInfo`](DataforseoLabsErrorsResultInfo.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`DataforseoLabsErrorsResultInfo`](DataforseoLabsErrorsResultInfo.md)

#### Defined in

[main.ts:77170](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L77170)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")