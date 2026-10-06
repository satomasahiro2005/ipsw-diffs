## CoreDiagnostics

> `/System/Library/PrivateFrameworks/CoreDiagnostics.framework/CoreDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72174` | `0x72634` | **`+0x4c0`** |
| `__TEXT.__cstring` | `0x675a` | `0x68aa` | **`+0x150`** |
| `__AUTH_CONST.__cfstring` | `0x54e0` | `0x55e0` | **`+0x100`** |
| `__TEXT.__unwind_info` | `0x17e8` | `0x17c0` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1150` | `0x1148` | **`-0x8`** |

### Other Changes

```diff

-77.0.0.0.0
+80.0.0.0.0

-  Symbols:   1447
-  CStrings:  1074
+  Symbols:   1446
+  CStrings:  1083
Symbols:
+ _OUTLINED_FUNCTION_14
+ _OUTLINED_FUNCTION_17
- _OUTLINED_FUNCTION_15
- _OUTLINED_FUNCTION_18
- _swift_retain_x28
CStrings:
+ "No heap allocation information available"
+ "blocked memory access for VM object %#llx"
+ "busy VM page %#llx"
+ "busy compressor segment %#llx owned by thread %llu"
+ "mapping-in-progress for VM object %#llx"
+ "page list requests for VM object %#llx"
+ "page-ins throttled for VM object %#llx"
+ "pager ready for VM object %#llx"
+ "paging-in-progress for VM object %#llx"
+ "paging/activity for VM object %#llx"
- "thread %llu in compressor segment %#llx"
```
