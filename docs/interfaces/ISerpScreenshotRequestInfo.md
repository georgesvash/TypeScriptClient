[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / ISerpScreenshotRequestInfo

# Interface: ISerpScreenshotRequestInfo

## Implemented by

- [`SerpScreenshotRequestInfo`](../classes/SerpScreenshotRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [browser\_preset](ISerpScreenshotRequestInfo.md#browser_preset)
- [browser\_screen\_height](ISerpScreenshotRequestInfo.md#browser_screen_height)
- [browser\_screen\_scale\_factor](ISerpScreenshotRequestInfo.md#browser_screen_scale_factor)
- [browser\_screen\_width](ISerpScreenshotRequestInfo.md#browser_screen_width)
- [task\_id](ISerpScreenshotRequestInfo.md#task_id)

## Properties

### browser\_preset

• `Optional` **browser\_preset**: `string`

browser resolution preset
optional field
browser preset associated with a certain device type
can take the following values: desktop, tablet, mobile
note: by default, browser preset corresponds to the device type specified in the POST request

#### Defined in

[main.ts:23481](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L23481)

___


### browser\_screen\_height

• `Optional` **browser\_screen\_height**: `number`

height of the browser resolution
optional field
can be specified in the following range: 240-9999

#### Defined in

[main.ts:23489](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L23489)

___


### browser\_screen\_scale\_factor

• `Optional` **browser\_screen\_scale\_factor**: `number`

browser scale factor
optional field
can be specified in the following range: 0.5-3

#### Defined in

[main.ts:23493](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L23493)

___


### browser\_screen\_width

• `Optional` **browser\_screen\_width**: `number`

width of the browser resolution
optional field
can be specified in the following range: 240-9999

#### Defined in

[main.ts:23485](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L23485)

___


### task\_id

• `Optional` **task\_id**: `string`

task identifier
required field
unique identifier of the associated task in the UUID format
you will be able to use it within 7 days to request the results of the task at any time

#### Defined in

[main.ts:23475](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L23475)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")