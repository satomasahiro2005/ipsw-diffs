## cloudphotod

> `/System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/Support/cloudphotod`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__got` | `0xd70` | `0xe78` | **`+0x108`** |
| `__TEXT.__oslogstring` | `0x125eb` | `0x12690` | **`+0xa5`** |
| `__TEXT.__text` | `0x1cc134` | `0x1cc1a0` | **`+0x6c`** |
| `__DATA_CONST.__cfstring` | `0x13440` | `0x13460` | **`+0x20`** |
| `__DATA_CONST.__const` | `0xb030` | `0xb050` | **`+0x20`** |
| `__TEXT.__cstring` | `0x1c0a2` | `0x1c0c2` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x2ace1` | `0x2ad01` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x1cb00` | `0x1cb20` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x1e00` | `0x1e10` | **`+0x10`** |
| `__TEXT.__objc_methtype` | `0x8cda` | `0x8cea` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x8d68` | `0x8d70` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0xf10` | `0xf18` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1091c` | `0x10914` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-910.21.101.0.0
+910.27.103.0.0

-  Functions: 10152
-  Symbols:   1059
-  CStrings:  11458
+  Functions: 10150
+  Symbols:   1061
+  CStrings:  11463
Symbols:
+ _CPLSetRequestEngineBlock
+ _CPLSyncSessionPredictionTypeTurboMode
CStrings:
+ "@32@0:8d16B24B28"
+ "Fetched share metadata %@ for %{public}@"
+ "Fetched share metadata without getting an actual zone or error:\nShare metadata: %@\nPer share error: %@\nOperation error: %@"
+ "No zone in share metadata and no error"
+ "Setting share url in pluginFields for OON participant"
+ "newTaskRequestWithExpectedDuration:requestsImmediateRuntime:turboMode:"
+ "predictedValueForType:"
+ "setICloudLibraryClientNeedsToVerifyTerms:"
+ "shouldBypassBackgroundScheduling"
- "Fetched share metadata root record %@ for %{public}@"
- "addShareURLToPluginFieldsIfNecessary:updatedCPLParticipants:"
- "newTaskRequestWithExpectedDuration:requestsImmediateRuntime:"
- "shouldUseTurboMode"
```
