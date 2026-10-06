## ClarityUIMessagesSettings

> `/System/Library/PreferenceBundles/ClarityUIMessagesSettings.bundle/ClarityUIMessagesSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2e08` | `0x2e3c` | **`+0x34`** |
| `__TEXT.__objc_stubs` | `0xf00` | `0xf20` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x1468` | `0x1482` | **`+0x1a`** |
| `__DATA.__objc_selrefs` | `0x5b8` | `0x5c0` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x118` | `0x120` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1851.0.0.0.0
+1854.0.0.0.0

-  Symbols:   337
-  CStrings:  296
+  Symbols:   338
+  CStrings:  297
Symbols:
+ _objc_msgSend$reloadSpecifier:animated:
Functions:
~ -[AXCLFCommunicationLimitController tableView:didSelectRowAtIndexPath:] : 476 -> 468
~ -[AXCLFCommunicationLimitController _updateForOutgoingCommunicationLimit] : 292 -> 352
CStrings:
+ "reloadSpecifier:animated:"
```
