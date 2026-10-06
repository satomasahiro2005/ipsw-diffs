## GenerationalStorage

> `/System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x169f4` | `0x16e0c` | **`+0x418`** |
| `__TEXT.__oslogstring` | `0x7b1` | `0x7f6` | **`+0x45`** |
| `__DATA_CONST.__const` | `0x628` | `0x658` | **`+0x30`** |
| `__TEXT.__cstring` | `0x1294` | `0x12ba` | **`+0x26`** |
| `__AUTH_CONST.__cfstring` | `0x1140` | `0x1160` | **`+0x20`** |
| `__AUTH_CONST.__objc_arrayobj` | `0x60` | `0x78` | **`+0x18`** |
| `__DATA_CONST.__objc_arraydata` | `0x60` | `0x78` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0xd8c` | `0xd9c` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x920` | `0x928` | **`+0x8`** |
| `__TEXT.__const` | `0x140` | `0x148` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x650` | `0x658` | **`+0x8`** |

### Other Changes

```diff

-403.0.0.0.0
+405.0.0.0.1

-  Functions: 455
-  Symbols:   876
-  CStrings:  234
+  Functions: 459
+  Symbols:   882
+  CStrings:  236
Symbols:
+ -[GSStorageManager _listAdditionsInNamespace:underPath:error:]
+ GCC_except_table30
+ GCC_except_table40
+ _GSAdditionProviderContentVersionPreviousBaseKey
+ ___62-[GSStorageManager _listAdditionsInNamespace:underPath:error:]_block_invoke
+ ___block_descriptor_40_e8_32s_e32_v32?0"NSArray"816"NSError"24ls32l8
+ _makeGSProviderContentVersion
- GCC_except_table28
CStrings:
+ "[ERROR] Provider-content-version V2 build failed, falling back to V1"
+ "kGSProviderContentVersionPreviousBase"
```
