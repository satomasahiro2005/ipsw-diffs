## CarbonCore

> `/System/Library/PrivateFrameworks/CarbonCore.framework/CarbonCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_DIRTY.__bss` | `—` | `0x278` | **`+0x278`** |
| `__DATA.__bss` | `0x11a0` | `0xf34` | **`-0x26c`** |
| `__DATA_DIRTY.__data` | `—` | `0x160` | **`+0x160`** |
| `__DATA.__data` | `0x440` | `0x2e8` | **`-0x158`** |
| `__TEXT.__text` | `0x34238` | `0x342bc` | **`+0x84`** |
| `__DATA_DIRTY.__common` | `—` | `0x18` | **`+0x18`** |
| `__DATA.__common` | `0x48` | `0x38` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0xd00` | `0xd08` | **`+0x8`** |

### Other Changes

```diff

-1402.0.0.0.0
+1404.0.0.0.0

-  Functions: 1100
-  Symbols:   1609
+  Functions: 1099
+  Symbols:   1608
Symbols:
- _OUTLINED_FUNCTION_46
Functions:
~ _FileIDTreeLockVolumeEntry : 136 -> 140
~ __SCUniverseAllocateEntry : 864 -> 940
~ __ZN8MsgDebug6sumOOLEPK17mach_msg_header_tPh : 120 -> 112
~ __ZN15SCServerSession13createServiceEPKcj : 1104 -> 1112
~ _FSNodeSyncVolumesCallback : 484 -> 500
~ _CalculateHashValue : 1140 -> 1112
~ _FileIDTreeGetFileIDFromPath : 532 -> 540
~ _OUTLINED_FUNCTION_33 : 12 -> 20
~ _OUTLINED_FUNCTION_34 : 20 -> 12
~ _OUTLINED_FUNCTION_37 : 12 -> 20
~ _OUTLINED_FUNCTION_39 : 20 -> 12
~ _OUTLINED_FUNCTION_41 : 12 -> 28
~ _OUTLINED_FUNCTION_43 : 28 -> 24
~ _OUTLINED_FUNCTION_44 : 24 -> 20
- _OUTLINED_FUNCTION_46
~ _UCCompareCollationKeys : 1232 -> 1268
~ _pathOf : 144 -> 148
~ _nameOf : 84 -> 76
~ __ZL16GetUTF8ExtensionsPKcPcm : 108 -> 120
~ _ConvertUTF16toCanonicalUTF8 : 180 -> 176
~ _FSNodeEntry_CleanFileIDTree : 332 -> 344
~ _FSNodeEntry_GetByRelativePath : 608 -> 612
~ _FileIDTreeServerGetVRefNumForDeviceInternal : 208 -> 220
```
