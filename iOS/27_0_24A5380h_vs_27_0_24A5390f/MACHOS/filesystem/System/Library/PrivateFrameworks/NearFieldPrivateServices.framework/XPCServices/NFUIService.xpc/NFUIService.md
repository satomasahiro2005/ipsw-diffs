## NFUIService

> `/System/Library/PrivateFrameworks/NearFieldPrivateServices.framework/XPCServices/NFUIService.xpc/NFUIService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4bac` | `0x54e4` | **`+0x938`** |
| `__DATA_CONST.__const` | `0x270` | `0x310` | **`+0xa0`** |
| `__TEXT.__objc_stubs` | `0x620` | `0x6a0` | **`+0x80`** |
| `__TEXT.__objc_methname` | `0x5f7` | `0x661` | **`+0x6a`** |
| `__TEXT.__auth_stubs` | `0x700` | `0x750` | **`+0x50`** |
| `__TEXT.__swift5_capture` | `0x20` | `0x64` | **`+0x44`** |
| `__TEXT.__eh_frame` | `—` | `0x40` | **`+0x40`** |
| `__DATA_CONST.__auth_got` | `0x388` | `0x3b0` | **`+0x28`** |
| `__TEXT.__oslogstring` | `0x33e` | `0x363` | **`+0x25`** |
| `__TEXT.__swift5_typeref` | `0xab` | `0xcf` | **`+0x24`** |
| `__DATA.__objc_selrefs` | `0x250` | `0x270` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x150` | `0x168` | **`+0x18`** |
| `__TEXT.__unwind_info` | `0x138` | `0x150` | **`+0x18`** |
| `__DATA.__data` | `0x250` | `0x258` | **`+0x8`** |
| `__TEXT.__objc_methtype` | `0x277` | `0x276` | **`-0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`

### Other Changes

```diff

-370.38.2.0.0
+370.40.2.0.0

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices
+  - /System/Library/PrivateFrameworks/SEService.framework/SEService

-  Functions: 71
-  Symbols:   199
-  CStrings:  211
+  Functions: 85
+  Symbols:   207
+  CStrings:  216
Symbols:
+ _$s10Foundation22_convertNSErrorToErrorys0E0_pSo0C0CSgF
+ _OBJC_CLASS_$_RBSProcessHandle
+ _OBJC_CLASS_$_RBSProcessPredicate
+ _OBJC_CLASS_$_SECPresentmentAuthorizationStore
+ _objc_retain_x24
+ _swift_getObjCClassFromMetadata
+ _swift_release_x24
+ _swift_release_x25
+ _swift_retain
+ _swift_willThrow
- _swift_release_x21
- _swift_release_x23
CStrings:
+ "Presentment authorization, %@"
+ "auditToken"
+ "handleForPredicate:error:"
+ "notifyAppLaunched:bundleID:error:"
+ "predicateMatchingBundleIdentifier:"
```
