[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IBusinessDataTrustpilotSearchTaskPostRequestInfo

# Interface: IBusinessDataTrustpilotSearchTaskPostRequestInfo

## Implemented by

- [`BusinessDataTrustpilotSearchTaskPostRequestInfo`](../classes/BusinessDataTrustpilotSearchTaskPostRequestInfo.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [depth](IBusinessDataTrustpilotSearchTaskPostRequestInfo.md#depth)
- [keyword](IBusinessDataTrustpilotSearchTaskPostRequestInfo.md#keyword)
- [pingback\_url](IBusinessDataTrustpilotSearchTaskPostRequestInfo.md#pingback_url)
- [postback\_url](IBusinessDataTrustpilotSearchTaskPostRequestInfo.md#postback_url)
- [priority](IBusinessDataTrustpilotSearchTaskPostRequestInfo.md#priority)
- [tag](IBusinessDataTrustpilotSearchTaskPostRequestInfo.md#tag)

## Properties

### depth

• `Optional` **depth**: `number`

parsing depth
optional field
number of search results to be returned from the API response
we strongly recommend setting the parsing depth in the multiples of twenty because our systems processes twenty search results in a row;
default value: 10;
maximum value: 140
Note: your account will be charged for every 10 search results returned, e.g. if you specify depth: 11, you will be charged as per 20 search results

#### Defined in

[main.ts:198787](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L198787)

___


### keyword

• `Optional` **keyword**: `string`

keyword
required field
the keyword you specify should indicate a business category or company name;
you can specify up to 700 symbols in the keyword filed;
all %## will be decoded (plus symbol ‘+’ will be decoded to a space character);
if you need to use the “%” symbol for your keyword, please specify it as “%25”

#### Defined in

[main.ts:198771](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L198771)

___


### pingback\_url

• `Optional` **pingback\_url**: `string`

notification URL of a completed task
optional field
when a task is completed we will notify you by GET request sent to the URL you have specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/pingscript?id=$id
http://your-server.com/pingscript?id=$id&tag=$tag
Note: special symbols in pingback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Defined in

[main.ts:198813](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L198813)

___


### postback\_url

• `Optional` **postback\_url**: `string`

return URL for sending task results
optional field
once the task is completed, we will send a POST request with its results compressed in the gzip format to the postback_url you specified
you can use the ‘$id’ string as a $id variable and ‘$tag’ as urlencoded $tag variable. We will set the necessary values before sending the request.
example:
http://your-server.com/postbackscript?id=$id
http://your-server.com/postbackscript?id=$id&tag=$tag
Note: special symbols in postback_url will be urlencoded;
i.a., the # symbol will be encoded into %23

#### Defined in

[main.ts:198803](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L198803)

___


### priority

• `Optional` **priority**: `number`

task priority
optional field
can take the following values:
1 – normal execution priority (set by default)
2 – high execution priority
You will be additionally charged for the tasks with high execution priority.
The cost can be calculated on the Pricing page.

#### Defined in

[main.ts:198779](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L198779)

___


### tag

• `Optional` **tag**: `string`

user-defined task identifier
optional field
the character limit is 255
you can use this parameter to identify the task and match it with the result
you will find the specified tag value in the data object of the response

#### Defined in

[main.ts:198793](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L198793)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")