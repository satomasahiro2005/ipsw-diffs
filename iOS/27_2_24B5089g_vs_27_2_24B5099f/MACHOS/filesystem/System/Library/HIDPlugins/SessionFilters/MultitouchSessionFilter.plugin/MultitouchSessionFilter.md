## MultitouchSessionFilter

> `/System/Library/HIDPlugins/SessionFilters/MultitouchSessionFilter.plugin/MultitouchSessionFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0xd20` | `0xd00` | **`-0x20`** |
| `__TEXT.__text` | `0xf7f4` | `0xf7dc` | **`-0x18`** |
| `__DATA.__objc_selrefs` | `0x498` | `0x490` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methname`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-10100.44.0.0.0
+10110.3.0.0.0

-  Symbols:   586
-  CStrings:  331
+  Symbols:   585
+  CStrings:  330
Symbols:
- _objc_msgSend$suspend
Functions:
~ -[MTRemoteFilterManager dealloc] : 148 -> 124
CStrings:
- "suspend"
```
