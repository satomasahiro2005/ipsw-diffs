## libBKDM2.dylib

> `/usr/lib/libBKDM2.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x88640` | `0x88800` | **`+0x1c0`** |
| `__TEXT.__cstring` | `0x832a` | `0x83b3` | **`+0x89`** |
| `__AUTH_CONST.__cfstring` | `0x6c40` | `0x6cc0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x61bc` | `0x61d4` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x16d8` | `0x16e8` | **`+0x10`** |
| `__DATA_CONST.__objc_arraydata` | `0x4d8` | `0x4e8` | **`+0x10`** |
| `__TEXT.__const` | `0xd7f8` | `0xd802` | **`+0xa`** |
| `__DATA_CONST.__objc_selrefs` | `0x40b0` | `0x40b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1050` | `0x1058` | **`+0x8`** |
| `__TEXT.__oslogstring` | `0x52f7` | `0x52f6` | **`-0x1`** |

### Other Changes

```diff

-980.0.26.0.0
+980.40.11.0.0

-  Functions: 3153
-  Symbols:   4576
-  CStrings:  1828
+  Functions: 3156
+  Symbols:   4582
+  CStrings:  1833
Symbols:
+ -[BioLog setPurgeableAtPath:directory:]
+ -[BiometricKitXPCServerPearl addDeviceSpecificProperties:]
+ GCC_except_table19
+ GCC_except_table33
+ GCC_except_table48
+ GCC_except_table51
+ GCC_except_table55
+ GCC_except_table70
+ __oidAppleExtendedKeyUsageSWUpdateSigning
+ _oidAppleExtendedKeyUsageSWUpdateSigning
- GCC_except_table45
- GCC_except_table50
- GCC_except_table52
- GCC_except_table69
Functions:
+ -[BiometricKitXPCServerPearl addDeviceSpecificProperties:]
~ -[BioLog init] : 1748 -> 1744
~ -[BioLog createFileAtPath:contents:attributes:purgeable:] : 204 -> 200
+ -[BioLog setPurgeableAtPath:directory:]
~ -[BioLog sequencePathForId:andSubdirectory:] : 256 -> 252
~ -[BioLog logSequenceInfo:withContext:orientation:identities:] : 13328 -> 13392
~ -[BioLog eventPathWithName:date:] : 356 -> 352
~ -[BioLog logSecureFrameMeta:timestamp:frameNumber:fromCameraID:] : 5788 -> 5784
+ -[BiometricKitXPCServerPearl addDeviceSpecificProperties:].cold.1
CStrings:
+ "BKDPHasFaceIDInExclave"
+ "BKDPRequiresFaceIDLatencyMitigation"
+ "BioLogRetention"
+ "Couldn't create OS Log for 'com.apple.BiometricKit.BioLogRetention'!\n"
+ "analytics_biolockout_reason"
+ "bioLogRetentionMarkFilesPurgeable"
+ "deviceProperties"
- "BioLog-Retention"
- "Couldn't create OS Log for 'com.apple.BiometricKit.BioLog-Retention'!\n"
```
