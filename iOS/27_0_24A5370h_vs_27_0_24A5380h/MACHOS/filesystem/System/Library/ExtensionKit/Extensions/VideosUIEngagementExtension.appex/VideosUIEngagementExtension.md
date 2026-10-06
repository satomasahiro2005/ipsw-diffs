## VideosUIEngagementExtension

> `/System/Library/ExtensionKit/Extensions/VideosUIEngagementExtension.appex/VideosUIEngagementExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa508` | `0xa66c` | **`+0x164`** |
| `__TEXT.__objc_stubs` | `0x1e0` | `0x240` | **`+0x60`** |
| `__TEXT.__auth_stubs` | `0x730` | `0x760` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x2a8` | `0x2cb` | **`+0x23`** |
| `__TEXT.__cstring` | `0x22d` | `0x24d` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x138` | `0x150` | **`+0x18`** |
| `__DATA_CONST.__auth_got` | `0x3a0` | `0x3b8` | **`+0x18`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1143.0.0.0.2
+1145.0.2.0.1

+  - /System/Library/PrivateFrameworks/TVAppServices.framework/TVAppServices

-  Symbols:   103
-  CStrings:  93
+  Symbols:   104
+  CStrings:  97
Symbols:
+ _objc_release_x24
Functions:
~ sub_100005ad0 -> sub_100005b38 : 396 -> 720
~ sub_100005fe4 -> sub_100006190 : 924 -> 956
CStrings:
+ "ams_DSID"
+ "objectForKey:"
+ "previousDSIDUsed"
+ "stringValue"
```
