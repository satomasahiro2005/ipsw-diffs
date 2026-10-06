## libsystem_sanitizers.dylib

> `/usr/lib/system/libsystem_sanitizers.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7bb8` | `0x7bc0` | **`+0x8`** |

### Other Changes

```text
Functions:
~ __ZNK4asan19GlobalsRegistryImpl12getGlobalVarEm : 104 -> 100
~ __ZNK10ASanShadow16regionIsPoisonedEmm : 264 -> 268
~ __ZN5trace13AllocationMapILm262144EXadL_ZN4hash7Murmur211hashPointerEmEEE15addDeallocTraceEmNS_2IdE : 208 -> 212
~ __ZN5trace13AllocationMapILm1048576EXadL_ZN4hash7Murmur211hashPointerEmEEE15addDeallocTraceEmNS_2IdE : 208 -> 212
~ _OUTLINED_FUNCTION_6 : 44 -> 28
~ _OUTLINED_FUNCTION_8 : 28 -> 44
```
