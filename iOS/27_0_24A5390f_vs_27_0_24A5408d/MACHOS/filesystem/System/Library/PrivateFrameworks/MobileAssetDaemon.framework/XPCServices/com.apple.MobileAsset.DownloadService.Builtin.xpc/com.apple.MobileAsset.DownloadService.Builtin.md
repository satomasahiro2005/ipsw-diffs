## com.apple.MobileAsset.DownloadService.Builtin

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/XPCServices/com.apple.MobileAsset.DownloadService.Builtin.xpc/com.apple.MobileAsset.DownloadService.Builtin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x21838` | `0x21b68` | **`+0x330`** |
| `__TEXT.__oslogstring` | `0x60e5` | `0x61e3` | **`+0xfe`** |
| `__DATA_CONST.__cfstring` | `0x2d80` | `0x2dc0` | **`+0x40`** |
| `__TEXT.__objc_stubs` | `0x46a0` | `0x46e0` | **`+0x40`** |
| `__TEXT.__cstring` | `0x43e9` | `0x4421` | **`+0x38`** |
| `__DATA.__objc_const` | `0x31c0` | `0x31f0` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x1e74` | `0x1ea4` | **`+0x30`** |
| `__TEXT.__objc_methname` | `0x5ea7` | `0x5ed2` | **`+0x2b`** |
| `__DATA_CONST.__objc_dictobj` | `0x230` | `0x258` | **`+0x28`** |
| `__TEXT.__objc_methtype` | `0x1254` | `0x1274` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x1560` | `0x1570` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x458` | `0x468` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-2215.0.16.0.0
+2215.0.20.0.0

-  Functions: 685
+  Functions: 687

-  CStrings:  1988
+  CStrings:  1999
CStrings:
+ "@\"NSData\"16@0:8"
+ "AutoControl-SetJobByIdentifier"
+ "AutoControl-SetJobCancel"
+ "Reading ATS context not supported here"
+ "T@\"NSData\",C,N"
+ "Updating ATS context not supported here"
+ "[MADownloadServiceBuiltin]: Attempting to start up builtin service built Aug  4 2026 11:26:10"
+ "[Manager]: Attempting to set ATS policy for content cache | TaskDescriptor:%{public}@"
+ "[Manager]: Failed to construct ATS policy | TaskDescriptor:%{public}@ | Error:%{public}@"
+ "_atsContext"
+ "set_atsContext:"
+ "v24@0:8@\"NSData\"16"
- "[MADownloadServiceBuiltin]: Attempting to start up builtin service built Jul 11 2026 05:37:45"
```
