<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [kibana-plugin-core-server](./kibana-plugin-core-server.md) &gt; [SavedObjectsImporter](./kibana-plugin-core-server.savedobjectsimporter.md) &gt; [import](./kibana-plugin-core-server.savedobjectsimporter.import.md)

## SavedObjectsImporter.import() method

Import saved objects from given stream. See the [options](./kibana-plugin-core-server.savedobjectsimportoptions.md) for more detailed information.

<b>Signature:</b>

```typescript
import({ readStream, createNewCopies, namespace, overwrite, refresh, }: SavedObjectsImportOptions): Promise<SavedObjectsImportResponse>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  { readStream, createNewCopies, namespace, overwrite, refresh, } | SavedObjectsImportOptions |  |

<b>Returns:</b>

Promise&lt;SavedObjectsImportResponse&gt;

## Exceptions

SavedObjectsImportError

