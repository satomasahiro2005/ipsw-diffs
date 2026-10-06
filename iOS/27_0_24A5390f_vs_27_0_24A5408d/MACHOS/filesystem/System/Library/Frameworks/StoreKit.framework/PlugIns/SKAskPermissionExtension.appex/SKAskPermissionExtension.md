## SKAskPermissionExtension

> `/System/Library/Frameworks/StoreKit.framework/PlugIns/SKAskPermissionExtension.appex/SKAskPermissionExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1a00` | `0x1a20` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x13dc` | `0x13f9` | **`+0x1d`** |
| `__TEXT.__objc_methlist` | `0x894` | `0x8a0` | **`+0xc`** |
| `__DATA.__data` | `0xe48` | `0xe50` | **`+0x8`** |
| `__DATA.__objc_const` | `0xd68` | `0xd70` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x538` | `0x540` | **`+0x8`** |
| `__TEXT.__cstring` | `0xb50` | `0xb49` | **`-0x7`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-816.0.41.0.0
+816.0.47.2.2

-  CStrings:  499
+  CStrings:  501
CStrings:
+ "cacheQueryIntervalWithReply:"
+ "developerErrorCode"
+ "developerErrorMessage"
+ "dialog"
- "dialog.developerErrorCode"
- "dialog.developerErrorMessage"
```
