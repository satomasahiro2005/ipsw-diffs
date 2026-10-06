## nanosystemsettingsd

> `/System/Library/PrivateFrameworks/NanoSystemSettings.framework/nanosystemsettingsd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1d470` | `0x1d974` | **`+0x504`** |
| `__TEXT.__oslogstring` | `0x2679` | `0x2787` | **`+0x10e`** |
| `__TEXT.__objc_methname` | `0x658c` | `0x663d` | **`+0xb1`** |
| `__TEXT.__cstring` | `0x1886` | `0x18e6` | **`+0x60`** |
| `__TEXT.__objc_methtype` | `0x141f` | `0x1473` | **`+0x54`** |
| `__TEXT.__objc_stubs` | `0x3dc0` | `0x3e00` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x1c44` | `0x1c7c` | **`+0x38`** |
| `__DATA.__objc_const` | `0x3ae0` | `0x3b08` | **`+0x28`** |
| `__DATA_CONST.__const` | `0x878` | `0x8a0` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x13e0` | `0x1400` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x510` | `0x528` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x17e8` | `0x17f8` | **`+0x10`** |
| `__TEXT.__const` | `0xe2` | `0xea` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-376.2.0.0.0
+383.0.0.0.0

+  - /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices

+  - /System/Library/PrivateFrameworks/RunningBoardServices.framework/RunningBoardServices

-  Functions: 549
+  Functions: 553

-  CStrings:  1538
+  CStrings:  1549
CStrings:
+ "@68@0:8@16B24@28@36d44B52B56^@60"
+ "F47B90E6-F2D5-49D0-A8F2-C880AA3FED19"
+ "Launching; \"NanoSystemSettingsDaemon-383\" \"30\""
+ "[obliterateGizmo] XPC received from Bridge: preserveeSIM=%d overwriteStorage=%d replyBlock=%p"
+ "[obliterateGizmo] entered: preserveeSIM=%d overwriteStorage=%d replyBlock=%p"
+ "[obliterateGizmo] missing entitlement %@, dropping"
+ "[obliterateGizmo] nil replyBlock, dropping request"
+ "kNSSObliterationRequestOverwriteStorageAssociatedObjectKey"
+ "obliterateGizmoPreservingeSIM:overwriteStorage:completionHandler:"
+ "sendRequest:expectsResponse:replyBlock:replyDictionary:sendTimeout:wantsAcknowledgement:bypassDuet:identifier:"
+ "v32@0:8B16B20@?24"
+ "v32@0:8B16B20@?<v@?@\"NSError\">24"
- "Launching; \"NanoSystemSettingsDaemon-376.2\" \"132\""
```
