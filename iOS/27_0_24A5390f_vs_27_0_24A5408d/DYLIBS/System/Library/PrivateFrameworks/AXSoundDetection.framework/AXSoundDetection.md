## AXSoundDetection

> `/System/Library/PrivateFrameworks/AXSoundDetection.framework/AXSoundDetection`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7964` | `0x7cc4` | **`+0x360`** |
| `__TEXT.__oslogstring` | `0x689` | `0x72e` | **`+0xa5`** |
| `__AUTH_CONST.__objc_const` | `0x818` | `0x850` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x898` | `0x8c8` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x850` | `0x880` | **`+0x30`** |
| `__DATA_CONST.__got` | `0x220` | `0x228` | **`+0x8`** |
| `__TEXT.__const` | `0x80` | `0x88` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a8` | `0x2b0` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x40` | `0x44` | **`+0x4`** |
| `__TEXT.__cstring` | `0x10ad` | `0x10af` | **`+0x2`** |

### Other Changes

```diff

-536.0.0.0.0
+539.1.0.0.0

-  Functions: 198
-  Symbols:   481
-  CStrings:  236
+  Functions: 202
+  Symbols:   488
+  CStrings:  238
Symbols:
+ -[AXSDSettings .cxx_destruct]
+ -[AXSDSettings lastCompanionSyncSnapshot]
+ -[AXSDSettings setLastCompanionSyncSnapshot:]
+ -[AXSDSettings syncAllKeysToCompanion]
+ _OBJC_IVAR_$_AXSDSettings._lastCompanionSyncSnapshot
+ __OBJC_$_INSTANCE_VARIABLES_AXSDSettings
+ _objc_setProperty_nonatomic_copy
Functions:
+ -[AXSDSettings syncAllKeysToCompanion]
CStrings:
+ "syncAllKeysToCompanion: pushing %lu keys to companion (previously %lu): %{public}@"
+ "syncAllKeysToCompanion: values unchanged since last companion sync, skipping push"
```
