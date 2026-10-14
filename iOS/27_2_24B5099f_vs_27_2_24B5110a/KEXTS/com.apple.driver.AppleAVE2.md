## com.apple.driver.AppleAVE2

> `com.apple.driver.AppleAVE2`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x1d3bc8` | `0x1d3ef8` | **`+0x330`** |
| `__TEXT.__os_log` | `0x5decc` | `0x5e03a` | **`+0x16e`** |
| `__TEXT.__cstring` | `0x491f4` | `0x49270` | **`+0x7c`** |

### Other Changes

```diff

-913.63.1.0.0
+913.64.1.0.0

-  CStrings:  9946
+  CStrings:  9950
Functions:
~ sub_fffffe0008789780 -> sub_fffffe000878b4d0 : 600 -> 608
~ __Z22AVE_Prop_Cfg_AV1_PrintP19_S_AVE_Prop_Cfg_AV1jiPKci : 37700 -> 37960
~ __Z17AVE_Client_VerifyP13_S_AVE_ClientbP35AVE_SessionSettings_UserKernel_Data : 752 -> 756
~ sub_fffffe000880ad50 -> sub_fffffe000880cbb0 : 588 -> 584
~ __Z22AVE_Prop_Cfg_AVC_PrintP19_S_AVE_Prop_Cfg_AVCjiPKci : 36500 -> 36748
~ __ZN9AVE_PSGen4InitEyPv14_E_AVE_EncTypeii : 5864 -> 5904
~ sub_fffffe00088a3d8c -> sub_fffffe00088a5d08 : 676 -> 668
~ __Z23AVE_Prop_Cfg_HEVC_PrintP20_S_AVE_Prop_Cfg_HEVCjiPKci : 48960 -> 49220
~ sub_fffffe000892ce80 -> sub_fffffe000892eef8 : 48 -> 56
CStrings:
+ "%lld %d AVE %s: %p %lld MachThreadPriorityForThreadEmittingFrames %d"
+ "%lld %d AVE %s: %p %lld MachThreadPriorityForThreadEmittingFrames %d\n"
+ "%p %lld MachThreadPriorityForThreadEmittingFrames %d"
+ "%p %lld MachThreadPriorityForThreadEmittingFrames %d\n"
+ "01:12:54"
+ "913.64.1"
+ "Oct 10 2026"
- "20:37:40"
- "913.63.1"
- "Sep 27 2026"
```
