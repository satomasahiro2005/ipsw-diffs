## ind

> `/System/Library/PrivateFrameworks/iCloudNotification.framework/ind`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x356d4` | `0x357c4` | **`+0xf0`** |
| `__TEXT.__oslogstring` | `0x4dc2` | `0x4e12` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1e3e` | `0x1e7e` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x12ff` | `0x133f` | **`+0x40`** |
| `__DATA_CONST.__cfstring` | `0x1f60` | `0x1f80` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x51b9` | `0x51d9` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x1bfc` | `0x1c14` | **`+0x18`** |
| `__DATA.__objc_const` | `0x47c8` | `0x47d0` | **`+0x8`** |
| `__DATA.__objc_selrefs` | `0x1510` | `0x1518` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-301.24.0.27.0
+301.24.1.3.0

-  Functions: 1288
+  Functions: 1289

-  CStrings:  1753
+  CStrings:  1758
Functions:
~ sub_10001616c : 436 -> 240
+ sub_10001625c
CStrings:
+ "Network request for reportDeleteWithSuccess is not yet implemented."
+ "reportDelete received. success:%@ appId:%{public}@; network not yet implemented."
+ "reportDeleteWithSuccess:forAltDSID:appId:completion:"
+ "urlStringForKey:"
+ "v44@0:8B16@\"NSString\"20@\"NSString\"28@?<v@?@\"NSError\">36"
+ "v44@0:8B16@20@28@?36"
- "_urlStringForKey:"
```
