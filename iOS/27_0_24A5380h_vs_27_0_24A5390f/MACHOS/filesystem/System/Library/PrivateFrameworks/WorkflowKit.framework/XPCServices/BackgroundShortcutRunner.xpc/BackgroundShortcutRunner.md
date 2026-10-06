## BackgroundShortcutRunner

> `/System/Library/PrivateFrameworks/WorkflowKit.framework/XPCServices/BackgroundShortcutRunner.xpc/BackgroundShortcutRunner`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88484` | `0x876dc` | **`-0xda8`** |
| `__TEXT.__eh_frame` | `0x4760` | `0x46e8` | **`-0x78`** |
| `__TEXT.__auth_stubs` | `0x3260` | `0x32b0` | **`+0x50`** |
| `__TEXT.__objc_methname` | `0x267f` | `0x26cf` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x2020` | `0x2060` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x1118` | `0x114e` | **`+0x36`** |
| `__DATA_CONST.__auth_got` | `0x1940` | `0x1968` | **`+0x28`** |
| `__DATA_CONST.__cfstring` | `0x3e0` | `0x3c0` | **`-0x20`** |
| `__DATA_CONST.__got` | `0xe18` | `0xe38` | **`+0x20`** |
| `__TEXT.__const` | `0x1980` | `0x1998` | **`+0x18`** |
| `__DATA.__objc_selrefs` | `0xa50` | `0xa60` | **`+0x10`** |
| `__DATA_CONST.__auth_ptr` | `0x410` | `0x400` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1480` | `0x1470` | **`-0x10`** |
| `__TEXT.__cstring` | `0x13d6` | `0x13e4` | **`+0xe`** |
| `__DATA.__data` | `0x12f0` | `0x12f8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0xf35` | `0xf36` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-5032.5.0.0.0
+5034.0.12.100.0

-  Functions: 2725
-  Symbols:   366
-  CStrings:  691
+  Functions: 2658
+  Symbols:   370
+  CStrings:  694
Symbols:
+ _WFActionErrorDomain
+ _WFEncodableError
+ _swift_getAssociatedConformanceWitness
+ _swift_getAssociatedTypeWitness
CStrings:
+ "%s runToolWithInvocation: failed to create action: %@"
+ "actionWithUUID:didFinishRunningWithError:result:executionResultMetadata:"
+ "performWithHost:"
+ "v16@?0@\"<WFOutOfProcessWorkflowControllerHost>\"8"
- "Faulty encoded tool invocation: %@"
```
