[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")

[dataforseo-client](../README.md) / [Exports](../modules.md) / IDatasetSerpElementItem

# Interface: IDatasetSerpElementItem

## Hierarchy

- [`IBaseSerpElementItem`](IBaseSerpElementItem.md)
  
  ↳ **`IDatasetSerpElementItem`**

## Implemented by

- [`DatasetSerpElementItem`](../classes/DatasetSerpElementItem.md)

## Indexable

▪ [key: `string`]: `any`

## Table of contents

### Properties

- [area\_covered](IDatasetSerpElementItem.md#area_covered)
- [authors](IDatasetSerpElementItem.md#authors)
- [dataset\_description](IDatasetSerpElementItem.md#dataset_description)
- [dataset\_id](IDatasetSerpElementItem.md#dataset_id)
- [dataset\_providers](IDatasetSerpElementItem.md#dataset_providers)
- [formats](IDatasetSerpElementItem.md#formats)
- [image\_url](IDatasetSerpElementItem.md#image_url)
- [licenses](IDatasetSerpElementItem.md#licenses)
- [links](IDatasetSerpElementItem.md#links)
- [period\_covered](IDatasetSerpElementItem.md#period_covered)
- [position](IDatasetSerpElementItem.md#position)
- [rank\_absolute](IDatasetSerpElementItem.md#rank_absolute)
- [rank\_group](IDatasetSerpElementItem.md#rank_group)
- [related\_article](IDatasetSerpElementItem.md#related_article)
- [scholarly\_articles\_url](IDatasetSerpElementItem.md#scholarly_articles_url)
- [scholarly\_citations\_count](IDatasetSerpElementItem.md#scholarly_citations_count)
- [title](IDatasetSerpElementItem.md#title)
- [unique\_identifier](IDatasetSerpElementItem.md#unique_identifier)
- [updated\_date](IDatasetSerpElementItem.md#updated_date)
- [xpath](IDatasetSerpElementItem.md#xpath)

## Properties

### area\_covered

• `Optional` **area\_covered**: `string`[]

the list of areas covered in the dataset
for example: Africa, Global

#### Defined in

[main.ts:51069](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51069)

___


### authors

• `Optional` **authors**: [`AuthorsElement`](../classes/AuthorsElement.md)[]

the list of authors of the dataset

#### Defined in

[main.ts:51059](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51059)

___


### dataset\_description

• `Optional` **dataset\_description**: [`DatasetDescription`](../classes/DatasetDescription.md)

description of the dataset

#### Defined in

[main.ts:51073](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51073)

___


### dataset\_id

• `Optional` **dataset\_id**: `string`

ID of the dataset

#### Defined in

[main.ts:51031](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51031)

___


### dataset\_providers

• `Optional` **dataset\_providers**: [`LicensesElement`](../classes/LicensesElement.md)[]

the list of institutions that provided the dataset

#### Defined in

[main.ts:51055](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51055)

___


### formats

• `Optional` **formats**: [`FormatsElement`](../classes/FormatsElement.md)[]

the list of file formats of the dataset

#### Defined in

[main.ts:51057](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51057)

___


### image\_url

• `Optional` **image\_url**: `string`

URL of the image
the URL leading to the image on the original resource or DataForSEO storage (in case the original source is not available)

#### Defined in

[main.ts:51036](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51036)

___


### licenses

• `Optional` **licenses**: [`LicensesElement`](../classes/LicensesElement.md)[]

the list of licenses issued to the dataset

#### Defined in

[main.ts:51061](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51061)

___


### links

• `Optional` **links**: [`LinkElement`](../classes/LinkElement.md)[]

sitelinks
the links shown below some of Google Dataset’s search results
if there are none, equals null

#### Defined in

[main.ts:51053](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51053)

___


### period\_covered

• `Optional` **period\_covered**: [`PeriodCovered`](../classes/PeriodCovered.md)

period covered in the dataset

#### Defined in

[main.ts:51071](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51071)

___


### position

• `Optional` **position**: `string`

the alignment of the element in SERP
can take the following values:
left, right

#### Defined in

[main.ts:51027](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51027)

___


### rank\_absolute

• `Optional` **rank\_absolute**: `number`

absolute rank in SERP
absolute position among all the elements in SERP

#### Defined in

[main.ts:51023](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51023)

___


### rank\_group

• `Optional` **rank\_group**: `number`

group rank in SERP
position within a group of elements with identical type values
positions of elements with different type values are omitted from rank_group

#### Defined in

[main.ts:51020](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51020)

___


### related\_article

• `Optional` **related\_article**: `string`

link to related article
link to the published article that is related to the dataset

#### Defined in

[main.ts:51049](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51049)

___


### scholarly\_articles\_url

• `Optional` **scholarly\_articles\_url**: `string`

url of scholarly articles
link to the list of scholarly articles on Google Scholar
example: https://scholar.google.com/scholar?q=%2210.6084%20m9%20figshare%207427933%20v1%22

#### Defined in

[main.ts:51042](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51042)

___


### scholarly\_citations\_count

• `Optional` **scholarly\_citations\_count**: `number`

count of articles that refer to the dataset

#### Defined in

[main.ts:51038](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51038)

___


### title

• `Optional` **title**: `string`

title of the result in SERP

#### Defined in

[main.ts:51033](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51033)

___


### unique\_identifier

• `Optional` **unique\_identifier**: `string`

digital identifier of an object
unique digital identifier of the dataset
example: https://doi.org/10.5061/dryad.hmgqnk9m3

#### Defined in

[main.ts:51046](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51046)

___


### updated\_date

• `Optional` **updated\_date**: `string`

date and time when the result was last updated
in the UTC format: “yyyy-mm-dd hh-mm-ss +00:00”
example:
2022-11-27 02:00:00 +00:00

#### Defined in

[main.ts:51066](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51066)

___


### xpath

• `Optional` **xpath**: `string`

the XPath of the element

#### Defined in

[main.ts:51029](https://github.com/dataforseo/TypeScriptClient/blob/7ca1aa4/main.ts#L51029)

[root](./../../ "root") / [docs](./../ "docs") / [interfaces](./ "interfaces")

[[Back to README.md]](./../../README.md "[Back to README.md]")