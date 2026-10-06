## RemoteiCloudQuotaUI

> `/Applications/RemoteiCloudQuotaUI.app/RemoteiCloudQuotaUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x414c` | `0x4260` | **`+0x114`** |
| `__TEXT.__objc_methname` | `0x1a1b` | `0x1a87` | **`+0x6c`** |
| `__TEXT.__objc_stubs` | `0xe00` | `0xe60` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0x9d3` | `0xa06` | **`+0x33`** |
| `__DATA.__objc_selrefs` | `0x6b8` | `0x6d0` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x6fc` | `0x704` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-301.24.1.3.0
+301.24.1.4.0

-  Functions: 91
+  Functions: 92

-  CStrings:  404
+  CStrings:  408
Functions:
~ sub_100003ae4 : 728 -> 348
+ sub_100003c58
CStrings:
+ "Setting OOP parent/host's app bundleIdentifier: %@"
+ "_configureFlowManagerWithOffer:icqLink:"
+ "presentingSceneBundleIdentifier"
+ "setPresentingSceneBundleIdentifier:"
```
