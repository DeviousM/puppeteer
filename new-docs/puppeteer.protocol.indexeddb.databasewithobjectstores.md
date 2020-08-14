<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [IndexedDB](./puppeteer.protocol.indexeddb.md) &gt; [DatabaseWithObjectStores](./puppeteer.protocol.indexeddb.databasewithobjectstores.md)

## Protocol.IndexedDB.DatabaseWithObjectStores interface

Database with an array of object stores.

<b>Signature:</b>

```typescript
export interface DatabaseWithObjectStores 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [name](./puppeteer.protocol.indexeddb.databasewithobjectstores.name.md) | string | Database name. |
|  [objectStores](./puppeteer.protocol.indexeddb.databasewithobjectstores.objectstores.md) | [ObjectStore](./puppeteer.protocol.indexeddb.objectstore.md)<!-- -->\[\] | Object stores in this database. |
|  [version](./puppeteer.protocol.indexeddb.databasewithobjectstores.version.md) | number | Database version (type is not 'integer', as the standard requires the version number to be 'unsigned long long') |
