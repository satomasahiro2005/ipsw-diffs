## Announce

> `/System/Library/PrivateFrameworks/Announce.framework/Announce`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3da18` | `0x3e0c8` | **`+0x6b0`** |
| `__TEXT.__oslogstring` | `0x201a` | `0x2067` | **`+0x4d`** |
| `__DATA_CONST.__const` | `0xfc8` | `0x1010` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x1480` | `0x14c0` | **`+0x40`** |
| `__TEXT.__const` | `0x1ca4` | `0x1ce4` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x12f8` | `0x1338` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1c28` | `0x1c58` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x8d2` | `0x8f7` | **`+0x25`** |
| `__TEXT.__objc_methlist` | `0x3220` | `0x3240` | **`+0x20`** |
| `__AUTH_CONST.__objc_const` | `0x5610` | `0x5628` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x50` | `0x64` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0x830` | `0x840` | **`+0x10`** |
| `__TEXT.__cstring` | `0x4069` | `0x4075` | **`+0xc`** |
| `__TEXT.__swift5_typeref` | `0x90c` | `0x916` | **`+0xa`** |
| `__DATA.__data` | `0x1260` | `0x1258` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x10` | `0x18` | **`+0x8`** |

### Other Changes

```diff

-331.0.0.0.0
+336.0.0.1.1

-  Functions: 1665
-  Symbols:   2435
-  CStrings:  706
+  Functions: 1673
+  Symbols:   2441
+  CStrings:  708
Symbols:
+ ___36-[ANHomeManager(Home) homeWithName:]_block_invoke
+ ___36-[ANHomeManager(Home) homeWithName:]_block_invoke_2
+ ___36-[ANHomeManager(Home) homeWithName:]_block_invoke_3
+ ___block_descriptor_32_e16_B16?0"HMHome"8l
+ ___block_descriptor_40_e8_32s_e16_B16?0"HMHome"8ls32l8
+ ___swift_memcpy25_8
+ _symbolic SS4room_t
- ___swift_memcpy24_8
CStrings:
+ "Announce is DISABLED For Accessory %@ because it does not support Announce"
+ "B16@?0@\"HMHome\"8"
```
