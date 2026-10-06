## deleted

> `/System/Library/PrivateFrameworks/CacheDelete.framework/deleted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5b558` | `0x5b8a0` | **`+0x348`** |
| `__TEXT.__oslogstring` | `0xacf0` | `0xae60` | **`+0x170`** |
| `__TEXT.__gcc_except_tab` | `0x2910` | `0x2934` | **`+0x24`** |
| `__TEXT.__objc_stubs` | `0x6920` | `0x6940` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x7e16` | `0x7e26` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1f08` | `0x1f10` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2ff4` | `0x2ffc` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-904.0.7.0.0
+904.40.2.0.0

-  Functions: 1240
-  Symbols:   3039
-  CStrings:  3165
+  Functions: 1241
+  Symbols:   3041
+  CStrings:  3172
Symbols:
+ +[CacheDeleteAnalytics isInternalBuild]
+ GCC_except_table61
+ GCC_except_table65
+ GCC_except_table68
+ _objc_msgSend$isInternalBuild
- GCC_except_table60
- GCC_except_table64
- GCC_except_table67
CStrings:
+ "Developer type %d for %@, treating as third-party"
+ "Fair Purge Analytics: reporting up to %lu third-party apps individually on a %@ build"
+ "Unable to get LSBundleRecord for %@ : %@"
+ "Unknown developer type for %@, treating as first-party on internal build"
+ "isInternalBuild"
+ "updateFollowup: skipping \"%{public}@\" because it became invalid"
+ "updateFollowup: skipping non-user volume \"%{public}@\""
```
