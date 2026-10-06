## CoverSheet

> `/System/Library/PrivateFrameworks/CoverSheet.framework/CoverSheet`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18c5f0` | `0x18c878` | **`+0x288`** |
| `__TEXT.__const` | `0x409c` | `0x40f4` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x3c698` | `0x3c6c0` | **`+0x28`** |
| `__DATA.__data` | `0x56a8` | `0x56d0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1644c` | `0x16474` | **`+0x28`** |
| `__TEXT.__cstring` | `0xca4a` | `0xca68` | **`+0x1e`** |
| `__TEXT.__oslogstring` | `0x8e7c` | `0x8e9a` | **`+0x1e`** |
| `__DATA_CONST.__objc_selrefs` | `0xc628` | `0xc638` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x4840` | `0x4848` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1b94` | `0x1b98` | **`+0x4`** |

### Other Changes

```diff

-152.100.0.0.0
+154.100.0.0.0

-  Functions: 7930
-  Symbols:   14052
-  CStrings:  2655
+  Functions: 7937
+  Symbols:   14069
+  CStrings:  2657
Symbols:
+ -[CSBatteryChargingView presumeCharging]
+ -[CSBatteryChargingView setPresumeCharging:]
+ -[CSCameraQuickAction symbolScaleValue]
+ -[CSCoverSheetViewController _clearChargingStateIfNecessary]
+ -[CSCoverSheetViewController _isShowingChargingSubtitle]
+ GCC_except_table789
+ GCC_except_table800
+ GCC_except_table837
+ _OBJC_IVAR_$_CSBatteryChargingView._presumeCharging
+ ___der_key_last_mesa_auth
+ ___der_key_last_mesa_unlock
+ ___der_key_last_passcode_auth
+ ___der_key_last_passcode_unlock
+ ___der_key_sks_heap_stats
+ _aks_get_convenience_bio_state
+ _aks_get_sks_heap_stats
+ _der_key_last_mesa_auth
+ _der_key_last_mesa_unlock
+ _der_key_last_passcode_auth
+ _der_key_last_passcode_unlock
+ _der_key_sks_heap_stats
- -[CSCoverSheetViewController _clearChargingModalStateIfNecessary]
- GCC_except_table788
- GCC_except_table799
- GCC_except_table836
CStrings:
+ "Dismissing charging subtitle."
+ "aks_get_convenience_bio_state"
```
