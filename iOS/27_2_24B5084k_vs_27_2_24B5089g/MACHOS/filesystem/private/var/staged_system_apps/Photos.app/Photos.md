## Photos

> `/private/var/staged_system_apps/Photos.app/Photos`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x34fe0` | `0x34e94` | **`-0x14c`** |
| `__TEXT.__cstring` | `0x319c` | `0x31be` | **`+0x22`** |
| `__DATA_CONST.__cfstring` | `0x34c0` | `0x34a0` | **`-0x20`** |
| `__TEXT.__objc_methname` | `0x9188` | `0x9168` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0x6e60` | `0x6e40` | **`-0x20`** |
| `__DATA.__objc_selrefs` | `0x2478` | `0x2470` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0xfd0` | `0xfd8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-916.40.110.0.0
+916.45.110.0.0

-  CStrings:  2129
+  CStrings:  2127
Functions:
~ sub_10000e1b8 : 440 -> 492
~ sub_10000e370 -> sub_10000e3a4 : 976 -> 148
~ sub_10000e740 -> sub_10000e438 : 148 -> 592
CStrings:
+ "Cannot perform edit with root view controller"
+ "adjustments.count"
+ "performBackgroundEditRequestWithAssets:adjustments:completionHandler:"
+ "performEditRequestWithAdjustments:completionHandler:"
- "adjustment"
- "adjustments"
- "assets"
- "canPerformEditRequestWithAssets:adjustments:completionHandler:"
- "canPerformEditsWithAssets:adjustments:error:"
- "performEditRequestWithAssets:adjustments:completionHandler:"
```
