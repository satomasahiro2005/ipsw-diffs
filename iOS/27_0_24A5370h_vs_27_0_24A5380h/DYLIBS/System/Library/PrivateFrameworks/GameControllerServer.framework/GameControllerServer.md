## GameControllerServer

> `/System/Library/PrivateFrameworks/GameControllerServer.framework/GameControllerServer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xde48` | `0xdebc` | **`+0x74`** |
| `__TEXT.__oslogstring` | `0x1114` | `0x1150` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0x118` | `0x120` | **`+0x8`** |

### Other Changes

```diff

-14.0.17.0.0
+14.0.19.0.0

-  Functions: 304
+  Functions: 305

-  CStrings:  187
+  CStrings:  188
Functions:
~ __ZN18HapticSharedMemory11readCommandER13HapticCommand : 420 -> 484
+ __ZN18HapticSharedMemory11readCommandER13HapticCommand.cold.5
CStrings:
+ "Cannot read from shared ring buffer (already deallocated?)!"
```
