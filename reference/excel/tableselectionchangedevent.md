# TableSelectionChangedEvent Object (JavaScript API for Excel)

Provides information about the table that raised the SelectionChanged event.

## Properties

| Property	   | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|context|object|Gets the context object that facilitates requests to the Excel application.|[1.7E](../requirement-sets/excel-api-requirement-sets.md)|

_See property access [examples.](#property-access-examples)_

## Relationships
| Relationship | Type	|Description| Req. Set|
|:---------------|:--------|:----------|:----|
|range|[Range](range.md)|Gets the range that represents the selected area of the table on a specific worksheet.|[1.7E](../requirement-sets/excel-api-requirement-sets.md)|
|table|[Table](table.md)|Gets the table in which the selection changed.|[1.7E](../requirement-sets/excel-api-requirement-sets.md)|
|type|string|Gets the type of the event.|[1.7E](../requirement-sets/excel-api-requirement-sets.md)|

## Methods
None
