## TactSwitchHIDServiceFilter

> `/System/Library/HIDPlugins/ServiceFilters/TactSwitchHIDServiceFilter.plugin/TactSwitchHIDServiceFilter`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x266c` | `0x29cc` | **`+0x360`** |
| `__TEXT.__oslogstring` | `0x36e` | `0x415` | **`+0xa7`** |
| `__DATA_CONST.__const` | `0x1f0` | `0x240` | **`+0x50`** |
| `__TEXT.__gcc_except_tab` | `0x2f8` | `0x334` | **`+0x3c`** |
| `__TEXT.__unwind_info` | `0x188` | `0x1b0` | **`+0x28`** |
| `__DATA.__objc_const` | `0x908` | `0x928` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0x98c` | `0x99c` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x34` | `0x38` | **`+0x4`** |
| `__TEXT.__cstring` | `0x35f` | `0x360` | **`+0x1`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__objc_methlist`
- `__TEXT.__objc_methtype`

### Other Changes

```diff

-9170.34.1.0.0
+10100.39.0.0.0

-  Functions: 67
-  Symbols:   263
-  CStrings:  262
+  Functions: 71
+  Symbols:   275
+  CStrings:  266
Symbols:
+ GCC_except_table11
+ GCC_except_table14
+ GCC_except_table17
+ GCC_except_table18
+ OBJC_IVAR_$_TouchSensitiveButtonHIDService._serviceIOQueue
+ __47-[TouchSensitiveButtonHIDService setHostState:]_block_invoke
+ __53-[TouchSensitiveButtonHIDService handleResetRequest:]_block_invoke
+ __54-[TouchSensitiveButtonHIDService setRecordingEnabled:]_block_invoke
+ ___47-[TouchSensitiveButtonHIDService setHostState:]_block_invoke
+ ___53-[TouchSensitiveButtonHIDService handleResetRequest:]_block_invoke
+ ___54-[TouchSensitiveButtonHIDService setRecordingEnabled:]_block_invoke
+ ___block_descriptor_41_ea8_32s_e5_v8?0ls32l8
+ ___block_descriptor_48_ea8_32s40s_e5_v8?0ls32l8s40l8
- GCC_except_table13
CStrings:
+ "Async dispatching camera active mode state"
+ "Async dispatching reset request"
+ "Cannot support property outside of IOHID queue with async operations for key: %@, value: %@"
+ "_serviceIOQueue"
```
