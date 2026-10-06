## safarifetcherd

> `/usr/libexec/safarifetcherd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_methname` | `0x53d5` | `0x542e` | **`+0x59`** |
| `__TEXT.__objc_methtype` | `0x24a3` | `0x24e4` | **`+0x41`** |
| `__TEXT.__objc_methlist` | `0x137c` | `0x138c` | **`+0x10`** |
| `__DATA.__objc_const` | `0x1620` | `0x1628` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1178` | `0x1180` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7625.1.22.10.3
+7625.1.24.10.1

-  CStrings:  1017
+  CStrings:  1020
CStrings:
+ "readerController:didRequestSummaryFeedbackWithActionType:readerTextUsedForSummarization:"
+ "v40@0:8@\"_SFReaderController\"16q24@\"NSString\"32"
+ "v40@0:8@16q24@32"
```
