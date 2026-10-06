## ReportCrash

> `/System/Library/CoreServices/ReportCrash`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4e048` | `0x4e154` | **`+0x10c`** |
| `__TEXT.__objc_methname` | `0x4710` | `0x4760` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x7dc0` | `0x7de0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x4020` | `0x4040` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5bfb` | `0x5c0b` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1160` | `0x1168` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0xfb8` | `0xfc0` | **`+0x8`** |

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
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1056.0.17.0.0
+1056.0.22.0.0

-  Functions: 1078
+  Functions: 1079

-  CStrings:  2286
+  CStrings:  2288
CStrings:
+ "Namespace %@, Code 0x%llx"
+ "initWithMetaData:applicationVersion:signpostData:reportedStateData:pid:terminationReason:applicationSpecificInfo:virtualMemoryRegionInfo:exceptionType:exceptionCode:exceptionReason:signal:terminationNamespace:terminationCode:stackTrace:"
+ "terminationReasonApprovedForExternalReports"
- "initWithMetaData:applicationVersion:signpostData:reportedStateData:pid:terminationReason:applicationSpecificInfo:virtualMemoryRegionInfo:exceptionType:exceptionCode:exceptionReason:signal:stackTrace:"
```
