---
lang: en
title: 'API docs: openapi-v3.schemaref'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
permalink: /doc/en/lb4/apidocs.openapi-v3.schemaref.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/openapi-v3](./openapi-v3.md) &gt; [SchemaRef](./openapi-v3.schemaref.md)

## SchemaRef type

Custom LoopBack extension: a reference to Schema object that's bundled inside `definitions` property.

<b>Signature:</b>

```typescript
export declare type SchemaRef = ReferenceObject & {
    definitions: SchemasObject;
};
```

## Example


```ts
const spec: SchemaRef = {
  $ref: '/components/schemas/Product',
  definitions: {
    Product: {
      title: 'Product',
      properties: {
        // etc.
      }
    }
  }
}

```

