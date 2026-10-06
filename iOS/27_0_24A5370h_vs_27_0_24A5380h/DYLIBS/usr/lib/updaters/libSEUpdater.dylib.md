## libSEUpdater.dylib

> `/usr/lib/updaters/libSEUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72774` | `0x72608` | **`-0x16c`** |
| `__TEXT.__gcc_except_tab` | `0x8518` | `0x857c` | **`+0x64`** |
| `__TEXT.__cstring` | `0x8e81` | `0x8eab` | **`+0x2a`** |
| `__DATA_CONST.__const` | `0x5a8` | `0x588` | **`-0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x610` | `0x620` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1d08` | `0x1d18` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x200` | `0x208` | **`+0x8`** |

### Other Changes

```diff

-58.0.41.0.0
+58.0.42.0.0

-  Symbols:   2897
-  CStrings:  1283
+  Symbols:   2902
+  CStrings:  1282
Symbols:
+ GCC_except_table125
+ GCC_except_table142
+ GCC_except_table193
+ GCC_except_table197
+ GCC_except_table201
+ GCC_except_table207
+ GCC_except_table80
+ GCC_except_table88
+ __GLOBAL__sub_I_P73BaseUpdateController.mm
+ __ZNSt3__128__exception_guard_exceptionsIZNS_10shared_ptrIN13SEUpdaterUtil5ErrorEEC1B9fqe220106IS3_ZN3ctu20SharedSynchronizableIS3_E15make_shared_ptrIS3_EENS1_IT_EEPSA_EUlPS3_E_Li0EEESC_T0_EUlvE_ED2B9fqe220106Ev
+ ___block_descriptor_48_ea8_32r_e5_v8?0lr32l8
- GCC_except_table158
- GCC_except_table196
- GCC_except_table198
- GCC_except_table89
- __GLOBAL__sub_I_P73BaseUpdateController.cpp
- __ZNK9SEUpdater20UpdateControllerBase20usesPORSecureElementEj
CStrings:
+ "Existing packageAID %s anyPackageOutOfDate %d wouldDowngrade %d anyModuleMissing %d, migrationTrigger %s"
+ "RSN 0x%X BSN 0x%X, skipSLAM %d forceSLAM %d isDowngrade %d\n"
+ "chipID 0x%X isProd %d expectedBSN 0x%X (has_value %d) deliveryBSN 0x%X isPORUpdate %d\n"
+ "expectedBSN"
- "Krypton Load and install SLAM"
- "RSN 0x%X BSN 0x%X, skipSLAM %d forceSLAM %d\n"
- "SLAMLoadAndInstallKrypton_3_2_4_0H_eosv2"
- "Skip SE-SEP pairing verification due to non-POR SE 0x%02X\n"
- "Skip personalization due to non-POR SE 0x%02X\n"
```
