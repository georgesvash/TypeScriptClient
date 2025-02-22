[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / EventDates

# Class: EventDates

## Implements

- [`IEventDates`](../interfaces/IEventDates.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Constructors

- [constructor](EventDates.md#constructor)

### Properties

- [displayed\_dates](EventDates.md#displayed_dates)
- [end\_datetime](EventDates.md#end_datetime)
- [start\_datetime](EventDates.md#start_datetime)

### Methods

- [init](EventDates.md#init)
- [toJSON](EventDates.md#tojson)
- [fromJS](EventDates.md#fromjs)

## Constructors

### constructor

• **new EventDates**(`data?`): [`EventDates`](EventDates.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data?` | [`IEventDates`](../interfaces/IEventDates.md) |

#### Returns

[`EventDates`](EventDates.md)

#### Defined in

[main.ts:44446](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44446)

## Properties

### displayed\_dates

• `Optional` **displayed\_dates**: `string`

date or date range as it is displayed in SERP

#### Implementation of

[IEventDates](../interfaces/IEventDates.md).[displayed_dates](../interfaces/IEventDates.md#displayed_dates)

#### Defined in

[main.ts:44442](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44442)

___


### end\_datetime

• `Optional` **end\_datetime**: `string`

date and time when the event ends
if time zone is specified in the event, value will be returned in the UTC format:
“yyyy-mm-ddThh-mm-ss+00:00”
example:
2019-11-15T12:57:46+00:00
if time zone is not specified in the event, unspecified local time will be returned in the following format:
“yyyy-mm-ddThh-mm-ss”
example:
2019-11-15T12:57:46

#### Implementation of

[IEventDates](../interfaces/IEventDates.md).[end_datetime](../interfaces/IEventDates.md#end_datetime)

#### Defined in

[main.ts:44440](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44440)

___


### start\_datetime

• `Optional` **start\_datetime**: `string`

date and time when the event starts
if time zone is specified in the event, value will be returned in the UTC format:
“yyyy-mm-ddThh-mm-ss+00:00”
example:
2019-11-15T12:57:46+00:00
if time zone is not specified in the event, unspecified local time will be returned in the following format:
“yyyy-mm-ddThh-mm-ss”
example:
2019-11-15T12:57:46

#### Implementation of

[IEventDates](../interfaces/IEventDates.md).[start_datetime](../interfaces/IEventDates.md#start_datetime)

#### Defined in

[main.ts:44430](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44430)

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

[main.ts:44455](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44455)

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

[main.ts:44474](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44474)

___


### fromJS

▸ **fromJS**(`data`): [`EventDates`](EventDates.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `data` | `any` |

#### Returns

[`EventDates`](EventDates.md)

#### Defined in

[main.ts:44467](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L44467)

[root](./../../ "root") / [docs](./../ "docs") / [classes](./ "classes")

[[Back to README.md]](./../../README.md "[Back to README.md]")