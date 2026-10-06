## ReportCrashService

> `/System/Library/Frameworks/OSAnalytics.framework/XPCServices/ReportCrashService.xpc/ReportCrashService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5336c` | `0x53478` | **`+0x10c`** |
| `__TEXT.__objc_methname` | `0x47fd` | `0x484d` | **`+0x50`** |
| `__DATA_CONST.__cfstring` | `0x7aa0` | `0x7ac0` | **`+0x20`** |
| `__TEXT.__objc_stubs` | `0x3de0` | `0x3e00` | **`+0x20`** |
| `__TEXT.__cstring` | `0x5ac5` | `0x5ad5` | **`+0x10`** |
| `__DATA.__objc_selrefs` | `0x1148` | `0x1150` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x1034` | `0x103c` | **`+0x8`** |

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
- `__DATA_CONST.__objc_protorefs`
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

-  Functions: 1128
+  Functions: 1129

-  CStrings:  2318
+  CStrings:  2320
CStrings:
+ "Namespace %@, Code 0x%llx"
+ "initWithMetaData:applicationVersion:signpostData:reportedStateData:pid:terminationReason:applicationSpecificInfo:virtualMemoryRegionInfo:exceptionType:exceptionCode:exceptionReason:signal:terminationNamespace:terminationCode:stackTrace:"
+ "terminationReasonApprovedForExternalReports"
- "initWithMetaData:applicationVersion:signpostData:reportedStateData:pid:terminationReason:applicationSpecificInfo:virtualMemoryRegionInfo:exceptionType:exceptionCode:exceptionReason:signal:stackTrace:"
```
