## com.apple.driver.AppleT8140PMGR

> `com.apple.driver.AppleT8140PMGR`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__auth_stubs` | `0x0` | `0x440` | **`+0x440`** |
| `__TEXT_EXEC.__text` | `0x80b4` | `0x8124` | **`+0x70`** |

### Other Changes

```diff

-1966.0.0.0.0
+1976.0.0.0.0
Functions:
~ _OUTLINED_FUNCTION_8 : 288 -> 300
~ __ZN14AppleT8140PMGR24_quiesceAxi2afWorkaroundEv : 224 -> 236
~ sub_fffffff0097f0320 -> sub_fffffff00984a788 : 180 -> 184
~ sub_fffffff0097f0528 -> sub_fffffff00984a994 : 260 -> 268
~ sub_fffffff0097f06a0 -> sub_fffffff00984ab14 : 92 -> 96
~ __ZN14AppleT8140PMGR14_getAccMappingEPKNS_10accMappingEjj : 440 -> 516
~ __ZN14AppleT8140PMGR10writeReg32EN9ApplePMGR6RegMapEjjj : 836 -> 840
~ __ZN14AppleT8140PMGR32_checkPwrGateRetentionWorkaroundEN9ApplePMGR6RegMapEjj : 256 -> 248
```
