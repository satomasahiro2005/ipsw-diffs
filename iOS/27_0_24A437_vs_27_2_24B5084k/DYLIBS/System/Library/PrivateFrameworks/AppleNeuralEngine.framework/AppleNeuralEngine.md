## AppleNeuralEngine

> `/System/Library/PrivateFrameworks/AppleNeuralEngine.framework/AppleNeuralEngine`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x59670` | `0x59b64` | **`+0x4f4`** |
| `__TEXT.__oslogstring` | `0xba7b` | `0xbb9b` | **`+0x120`** |
| `__AUTH_CONST.__cfstring` | `0x5060` | `0x5080` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3a7f` | `0x3a9c` | **`+0x1d`** |
| `__AUTH_CONST.__auth_got` | `0x688` | `0x698` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x6b7c` | `0x6b8c` | **`+0x10`** |
| `__DATA.__bss` | `0x190` | `0x198` | **`+0x8`** |
| `__DATA.__data` | `0x720` | `0x728` | **`+0x8`** |

### Other Changes

```diff

-382.15.1.0.0
+382.100.2.0.0

-  Symbols:   2289
-  CStrings:  1487
+  Symbols:   2293
+  CStrings:  1492
Symbols:
+ +[_ANECloneHelper cloneIfWritable:isEncryptedModel:cloneDirectory:useClone:]
+ _cloneIfWritable:isEncryptedModel:cloneDirectory:useClone:.s_tb
+ _kANEFModelMutableClusterIndexKey
+ _mach_timebase_info
+ _proc_pid_rusage
- +[_ANECloneHelper cloneIfWritable:isEncryptedModel:cloneDirectory:]
Functions:
~ -[_ANEVirtualClient transferAssetsToHostAtPath:withUUID:modelType:] : 2788 -> 3004
~ +[_ANECloneHelper cloneIfWritable:isEncryptedModel:cloneDirectory:] -> +[_ANECloneHelper cloneIfWritable:isEncryptedModel:cloneDirectory:useClone:] : 2412 -> 3464
CStrings:
+ "%@: Created shared IOSurface with ioSID=%u (size=%u) for all file transfers at path=%@"
+ "%@: copyfile DONE useClone=%d flags=0x%x elapsed_ms=%llu bytes_written=%llu src=%s"
+ "%@: createDirectoryAtPath ok=%d elapsed_ms=%llu path=%@"
+ "%@: removeItemAtPath existed=%d ok=%d elapsed_ms=%llu path=%@"
+ "ANEFModelMutableClusterIndex"
```
