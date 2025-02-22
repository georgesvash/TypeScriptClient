[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IOnPageWaterfallItem

# Interface: IOnPageWaterfallItem

## Implemented by

- [`OnPageWaterfallItem`](../classes/OnPageWaterfallItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [connection\_time](IOnPageWaterfallItem.md#connection_time)
- [dom\_complete](IOnPageWaterfallItem.md#dom_complete)
- [download\_time](IOnPageWaterfallItem.md#download_time)
- [duration\_time](IOnPageWaterfallItem.md#duration_time)
- [fetch\_end](IOnPageWaterfallItem.md#fetch_end)
- [fetch\_start](IOnPageWaterfallItem.md#fetch_start)
- [page\_url](IOnPageWaterfallItem.md#page_url)
- [request\_sent\_time](IOnPageWaterfallItem.md#request_sent_time)
- [resources](IOnPageWaterfallItem.md#resources)
- [time\_to\_interactive](IOnPageWaterfallItem.md#time_to_interactive)
- [time\_to\_secure\_connection](IOnPageWaterfallItem.md#time_to_secure_connection)
- [waiting\_time](IOnPageWaterfallItem.md#waiting_time)

## Properties

### connection\_time

• `Optional` **connection\_time**: `number`

time to connect to a server
the time it takes until the connection with a server is established (in milliseconds)

#### Defined in

[main.ts:149825](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149825)

___


### dom\_complete

• `Optional` **dom\_complete**: `number`

time to load resources
the time it takes until the page and all of its subresources are downloaded (in milliseconds)

#### Defined in

[main.ts:149822](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149822)

___


### download\_time

• `Optional` **download\_time**: `number`

time it takes for a browser to receive a response (in milliseconds)

#### Defined in

[main.ts:149835](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149835)

___


### duration\_time

• `Optional` **duration\_time**: `number`

total time it takes until a browser receives a complete response from a server (in milliseconds)

#### Defined in

[main.ts:149837](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149837)

___


### fetch\_end

• `Optional` **fetch\_end**: `number`

time to complete downloading the HTML resource
the amount of time the browser needs to complete downloading a page

#### Defined in

[main.ts:149843](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149843)

___


### fetch\_start

• `Optional` **fetch\_start**: `number`

time to start downloading the HTML resource
the amount of time the browser needs to start downloading a page

#### Defined in

[main.ts:149840](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149840)

___


### page\_url

• `Optional` **page\_url**: `string`

URL of the page

#### Defined in

[main.ts:149816](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149816)

___


### request\_sent\_time

• `Optional` **request\_sent\_time**: `number`

time to send a request to a server
the time it takes until the request to a server is sent (in milliseconds)

#### Defined in

[main.ts:149831](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149831)

___


### resources

• `Optional` **resources**: [`BaseOnPageResourceItemInfo`](../classes/BaseOnPageResourceItemInfo.md)[]

resource-specific timing
contains separate arrays with timing for each resource found on the page

#### Defined in

[main.ts:149846](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149846)

___


### time\_to\_interactive

• `Optional` **time\_to\_interactive**: `number`

Time To Interactive (TTI) metric
the time it takes until the user can interact with a page (in milliseconds)

#### Defined in

[main.ts:149819](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149819)

___


### time\_to\_secure\_connection

• `Optional` **time\_to\_secure\_connection**: `number`

time to establish a secure connection
the time it takes until the secure connection with a server is established (in milliseconds)

#### Defined in

[main.ts:149828](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149828)

___


### waiting\_time

• `Optional` **waiting\_time**: `number`

time to first byte (TTFB) in milliseconds

#### Defined in

[main.ts:149833](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L149833)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")