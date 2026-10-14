## webbookmarksd

> `/usr/libexec/webbookmarksd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x17a14` | `0x17b4c` | **`+0x138`** |
| `__DATA_CONST.__const` | `0x1230` | `0x1258` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0xb10` | `0xb30` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x4890` | `0x48ad` | **`+0x1d`** |
| `__DATA_CONST.__auth_got` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0xd14` | `0xd24` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1190` | `0x1198` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x8f8` | `0x900` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-7625.2.7.1.0
+7625.2.8.10.4

-  Functions: 501
-  Symbols:   449
-  CStrings:  1004
+  Functions: 503
+  Symbols:   451
+  CStrings:  1005
Symbols:
+ _SFNotifyPebblePreferenceUpdated
+ _SFSeedCloudTabsRestorationUUIDIfAbsent
CStrings:
+ "performInitialFetchIfNeeded:"
```
