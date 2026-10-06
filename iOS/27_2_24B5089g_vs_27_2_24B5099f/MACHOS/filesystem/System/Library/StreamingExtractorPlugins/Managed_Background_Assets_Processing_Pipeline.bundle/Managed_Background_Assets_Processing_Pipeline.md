## Managed Background Assets Processing Pipeline

> `/System/Library/StreamingExtractorPlugins/Managed Background Assets Processing Pipeline.bundle/Managed Background Assets Processing Pipeline`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4da04` | `0x4dc44` | **`+0x240`** |
| `__TEXT.__oslogstring` | `0x1ad8` | `0x1bf8` | **`+0x120`** |
| `__TEXT.__cstring` | `0x46a` | `0x4ba` | **`+0x50`** |
| `__TEXT.__auth_stubs` | `0x1510` | `0x1550` | **`+0x40`** |
| `__TEXT.__const` | `0x1b98` | `0x1b70` | **`-0x28`** |
| `__DATA_CONST.__auth_got` | `0xa90` | `0xab0` | **`+0x20`** |
| `__DATA.__data` | `0x1058` | `0x1070` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x908` | `0x91c` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x428` | `0x434` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_acfuncs`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2.1.6.0.0
+2.1.9.0.0

-  Functions: 756
-  Symbols:   182
-  CStrings:  258
+  Functions: 755
+  Symbols:   187
+  CStrings:  264
Symbols:
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_getTupleTypeMetadata2
+ _swift_storeEnumTagMultiPayload
- _swift_retain_x25
CStrings:
+ " expected "
+ "Bytes can’t be supplied to the processing pipeline because it isn’t currently active."
+ "The processing pipeline can’t be suspended because it isn’t currently active."
+ "The processing pipeline can’t prepare for extraction because it isn’t currently inactive."
+ "” is unexpected; “"
+ "” was expected."
```
