## MediaExperience

> `/System/Library/PrivateFrameworks/MediaExperience.framework/MediaExperience`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x254540` | `0x2548d8` | **`+0x398`** |
| `__TEXT.__oslogstring` | `0x501a3` | `0x50325` | **`+0x182`** |
| `__DATA_CONST.__objc_selrefs` | `0x54c0` | `0x54c8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x88c8` | `0x88d0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5f90` | `0x5f98` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-360.75.1.2.0
+360.75.1.4.0

-  Functions: 10094
-  Symbols:   13524
-  CStrings:  9897
+  Functions: 10089
+  Symbols:   13525
+  CStrings:  9899
Symbols:
+ -[MXSessionManager(Utilities) isSystemSoundLocalVADOnSamePhysicalDeviceAsDefaultVAD]
+ GCC_except_table143
+ _CMSMUtility_IsJBLSystemSoundAudioCategory
- GCC_except_table142
- _OUTLINED_FUNCTION_162
CStrings:
+ "-MXSessionManagerUtilities- %s: VoiceOver: vsyl is on the same physical device as vdef; moving vsyl as secondary entry for VoiceOver destinations so it routes to vdef for real hardware volume"
+ "-MXSystemSounds- %s: VoiceOver SystemSounds: vsyl is on the same physical device as vdef; moving vsyl as secondary entry for VoiceOver destinations so it routes to vdef for real hardware volume"
+ "21:49:51"
+ "Sep 23 2026"
- "15:48:22"
- "Aug  8 2026"
```
