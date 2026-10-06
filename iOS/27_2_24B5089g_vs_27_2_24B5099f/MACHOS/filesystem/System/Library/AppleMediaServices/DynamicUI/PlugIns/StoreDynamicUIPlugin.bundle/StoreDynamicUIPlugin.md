## StoreDynamicUIPlugin

> `/System/Library/AppleMediaServices/DynamicUI/PlugIns/StoreDynamicUIPlugin.bundle/StoreDynamicUIPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1296a0` | `0x12a0e0` | **`+0xa40`** |
| `__TEXT.__objc_methname` | `0x3e4d` | `0x3f53` | **`+0x106`** |
| `__DATA_CONST.__const` | `0xc200` | `0xc100` | **`-0x100`** |
| `__DATA.__data` | `0x89d0` | `0x8aa0` | **`+0xd0`** |
| `__DATA.__objc_data` | `0x4338` | `0x4408` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x5b7f` | `0x5c4f` | **`+0xd0`** |
| `__DATA.__objc_const` | `0x4e80` | `0x4f40` | **`+0xc0`** |
| `__TEXT.__constg_swiftt` | `0x536c` | `0x5418` | **`+0xac`** |
| `__TEXT.__unwind_info` | `0x4ba0` | `0x4bf8` | **`+0x58`** |
| `__TEXT.__swift5_fieldmd` | `0x5b10` | `0x5b64` | **`+0x54`** |
| `__TEXT.__swift5_capture` | `0x1948` | `0x1910` | **`-0x38`** |
| `__TEXT.__eh_frame` | `0x2fb4` | `0x2fdc` | **`+0x28`** |
| `__TEXT.__const` | `0xfdd4` | `0xfdf4` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x36f0` | `0x3700` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x1924` | `0x1934` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1b80` | `0x1b88` | **`+0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1490` | `0x1498` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xc72e` | `0xc736` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__cstring`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-8.1.15.0.0
+8.1.20.0.0

-  Functions: 7827
-  Symbols:   364
-  CStrings:  1130
+  Functions: 7856
+  Symbols:   365
+  CStrings:  1136
Symbols:
+ _swift_dynamicCastObjCProtocolConditional
CStrings:
+ "bleedReferenceView"
+ "convertRect:fromCoordinateSpace:"
+ "delegateContent"
+ "delegateContentSize"
+ "delegateContentView"
+ "delegateImpressionsCalculator"
+ "didObserveDelegateImpressionItems"
+ "effectiveContentSize"
- "backItem"
- "leftBarButtonItems"
```
