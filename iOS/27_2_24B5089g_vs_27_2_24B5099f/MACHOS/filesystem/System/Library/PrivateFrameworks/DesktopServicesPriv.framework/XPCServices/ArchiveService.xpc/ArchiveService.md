## ArchiveService

> `/System/Library/PrivateFrameworks/DesktopServicesPriv.framework/XPCServices/ArchiveService.xpc/ArchiveService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2dde8` | `0x2e0c0` | **`+0x2d8`** |
| `__TEXT.__objc_methname` | `0x2417` | `0x2467` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x4020` | `0x4064` | **`+0x44`** |
| `__TEXT.__objc_stubs` | `0x1da0` | `0x1de0` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x140d` | `0x13d0` | **`-0x3d`** |
| `__TEXT.__objc_methtype` | `0xbaf` | `0xbcf` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1208` | `0x1220` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0x898` | `0x8a8` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x6cc` | `0x6dc` | **`+0x10`** |

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
- `__TEXT.__constg_swiftt`
- `__TEXT.__cstring`
- `__TEXT.__eh_frame`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`

### Other Changes

```diff

-1857.1.4.0.0
+1857.1.7.0.0

-  Functions: 691
-  Symbols:   741
-  CStrings:  822
+  Functions: 695
+  Symbols:   743
+  CStrings:  824
Symbols:
+ __ZN10TCFURLInfo10InitializeERK12cstring_view
+ __ZN10TCFURLInfo20POSIXErrorToOSStatusEi
+ __ZN12cstring_viewC1ERK7TString
- __ZN10TCFURLInfo10InitializeEPKc
CStrings:
+ "B48@0:8@16@24Q32^@40"
+ "_settleQuarantineForUnarchivedFolder:quarantineData:options:error:"
+ "fileExistsAtPath:"
+ "v40@0:8@\"NSData\"16@\"DSSandboxingURLWrapper\"24@?<v@?@\"NSError\">32"
- "Failed to remove unarchive destination folder %{public}@: %@"
- "v40@0:8@\"NSData\"16@\"DSSandboxingURLWrapper\"24@?<v@?>32"
```
