## GPUToolsCaptureCoreAI

> `/System/Library/PrivateFrameworks/GPUToolsCaptureCoreAI.framework/GPUToolsCaptureCoreAI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9220` | `0x9e4c` | **`+0xc2c`** |
| `__TEXT.__oslogstring` | `0x731` | `0x882` | **`+0x151`** |
| `__TEXT.__cstring` | `0xb20` | `0xa5e` | **`-0xc2`** |
| `__AUTH_CONST.__auth_got` | `0x540` | `0x5a8` | **`+0x68`** |
| `__AUTH_CONST.__const` | `0xa0` | `0xc8` | **`+0x28`** |
| `__DATA.__bss` | `0x10` | `0x30` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x338` | `0x348` | **`+0x10`** |
| `__TEXT.__const` | `0x1d0` | `0x1e0` | **`+0x10`** |
| `__TEXT.__swift5_typeref` | `0xe1` | `0xd7` | **`-0xa`** |
| `__DATA.__data` | `0x440` | `0x438` | **`-0x8`** |
| `__DATA_CONST.__got` | `0x180` | `0x188` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1a8` | `0x1b0` | **`+0x8`** |

### Other Changes

```diff

-2027.0.28.0.0
+2027.0.31.0.0

+  - /usr/lib/swift/libswiftOSLog.dylib

-  Functions: 91
-  Symbols:   253
-  CStrings:  80
+  - /usr/lib/swift/libswiftos.dylib
+  Functions: 100
+  Symbols:   267
+  CStrings:  81
Symbols:
+ ___swift_allocate_value_buffer
+ ___swift_project_value_buffer
+ __os_log_impl
+ __swiftImmortalRefCount
+ __swift_FORCE_LOAD_$_swiftOSLog
+ __swift_FORCE_LOAD_$_swiftOSLog_$_GPUToolsCaptureCoreAI
+ __swift_FORCE_LOAD_$_swiftos
+ __swift_FORCE_LOAD_$_swiftos_$_GPUToolsCaptureCoreAI
+ _memcpy
+ _swift_bridgeObjectRelease_n
+ _swift_errorRetain
+ _swift_getObjectType
+ _swift_release_x23
+ _swift_slowAlloc
+ _swift_slowDealloc
+ _swift_unknownObjectRetain
- _swift_release_x24
- _symbolic _____yypG s23_ContiguousArrayStorageC
CStrings:
+ "Capture not active, skipping inference begin (%{public}s)"
+ "Failed to Copy Model: %{public}s"
+ "inference begin with id: %{public}llu"
+ "inference capture write failed for id: %{public}llu"
+ "inference end with id: %{public}llu"
+ "inference end with id: %{public}llu doesn't match previous begin, ignoring."
- " doesn't match previous begin, ignoring."
- "CoreAICapture: Capture not active, skipping inference begin ("
- "Failed to Copy Model: "
- "inference begin with id: "
- "inference end with id: "
```
