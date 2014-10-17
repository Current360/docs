---
nav-title: "Class ui/core/view"
title: "Class ui/core/view"
description: "Class ui/core/view"
---
# Module: "ui/core/view"

``` JavaScript
// To import the "ui/core/view" module:
var uicoreview = require("ui/core/view");
```

Class | Description
------|------------
[View](../../../ui/core/view/View.md) | 

Object | Description
------|------------
[Options](../../../ui/core/view/Options.md) | 

Namespace | Description
------|------------
[knownEvents](../../../ui/core/view/knownEvents/) | 

##### Variables
 - **isVisibleProperty** - [_Property_](../../../ui/core/dependency-observable/Property.md).

##### Functions
 - **getViewById(** view [_View_](../../../ui/core/view/View.md), id _String_ **)** [_View_](../../../ui/core/view/View.md)
   - **view** - [_View_](../../../ui/core/view/View.md)
   - **id** - _String_
   - _**return**_ - [_View_](../../../ui/core/view/View.md)
 - **eachDescendant(** view [_View_](../../../ui/core/view/View.md), callback _Function_... **)**
   - **view** - [_View_](../../../ui/core/view/View.md)
   - **callback** - _Function_(child [_View_](../../../ui/core/view/View.md)) _Boolean_
 - **getAncestor(** view [_View_](../../../ui/core/view/View.md), typeName _String_ **)** [_View_](../../../ui/core/view/View.md)
   - **view** - [_View_](../../../ui/core/view/View.md)
   - **typeName** - _String_
   - _**return**_ - [_View_](../../../ui/core/view/View.md)