## adc-rheia-d9x.im4p

> `Firmware/isp_bni/adc-rheia-d9x.im4p`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaa48f8` | `0xaa2384` | **`-0x2574`** |
| `__TEXT.__const` | `0x9cbac0` | `0x9cb988` | **`-0x138`** |
| `__TEXT.__cstring` | `0xa7f69` | `0xa7e88` | **`-0xe1`** |
| `__DATA.__const` | `0x55708` | `0x557b0` | **`+0xa8`** |

### Same-size Content Changes

- `__DATA.__chain_starts`
- `__DATA.__data`
- `__DATA.__data_copy`
- `__DATA._rtk_mtab`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA._rtk_smp_main`
- `__TEXT.__eh_frame`

### Other Changes

```diff

-  Functions: 9217
+  Functions: 9219

-  CStrings:  18346
+  CStrings:  18341
CStrings:
+ "!sm3_coredump_data, ignoring....\n"
+ "20:45:16"
+ "AE[%u] set enableDepthflash %d\n"
+ "END FLASH-AEDBG CH[%zu]: flashStatusAE=[%d] flashStatusAWB=[%d]\n"
+ "END FLASH-AWBDBG CH[%zu]: flashStatusAWB=[%d]\n"
+ "SecureM3 coredump out-of-bounds. Ignoring....\n"
+ "[%s] CH = 0x%zu MLVNR Tw Config ctrl=%d,Thres Enter:Exit=%d:%d,RampDownFrames=%d\n"
+ "[%zu]: m=0x%2x fps:%2d.%03d %4us/ %u fr=%d:%02d.%02d x%d.%01d %s %3u"
- "!sm3_coredump_data\n"
- "03:36:26"
- "AE[%u]::%s:%d: CAEAFE Reset initiated\n"
- "CAEAFE"
- "Face => luxLevel=luxLevelTmp(%.1f) * luxOffFact(%.1f) * face_fact(%.2f) + LEDOff.Lux(%.1f) = %.2f"
- "No face=>luxLevel=MAX((luxLevelTmp(%.1f) * luxOffFactor(%.1f) + LEDOff.Lux(%.1f)=%.2f) * 0.3f=%.1f, Preflash.fLux(%.1f)) = %.2f"
- "SecureM3 coredump out-of-bounds\n"
- "TIMEWARP[%zu]: m=0x%2x fps:%2d.%03d %4us/ %u fr=%d:%02d.%02d x%d.%01d %s %3u"
- "[%s] CH = 0x%zu MLVNR TimeWarp Config ctrl=%d,Thres Enter:Exit=%d:%d,RampDownFrames=%d\n"
- "flash AE depth lux %f\n"
- "flash AE lux to ltm %d\n"
- "flash AE old lux %.2f，preflash %.2f\n"
- "set enableDepthflash %d\n"
```
