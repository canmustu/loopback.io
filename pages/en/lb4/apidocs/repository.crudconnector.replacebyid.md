---
lang: en
title: 'API docs: repository.crudconnector.replacebyid'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.repository.crudconnector.replacebyid.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [CrudConnector](./repository.crudconnector.md) &gt; [replaceById](./repository.crudconnector.replacebyid.md)

## CrudConnector.replaceById() method

Replace an entity by id

<b>Signature:</b>

```typescript
replaceById?<IdType>(modelClass: Class<Entity>, id: IdType, data: EntityData, options?: Options): Promise<boolean>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelClass | <code>Class&lt;Entity&gt;</code> | The model class |
|  id | <code>IdType</code> | The entity id value |
|  data | <code>EntityData</code> | The data attributes to be updated |
|  options | <code>Options</code> | Options for the operation |

<b>Returns:</b>

`Promise<boolean>`

Promise<true> if an entity is replaced for the id, otherwise Promise<false>

