## BacklightServices

> `/System/Library/PrivateFrameworks/BacklightServices.framework/BacklightServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x29af4` | `0x2a070` | **`+0x57c`** |
| `__AUTH_CONST.__objc_const` | `0x81b0` | `0x8290` | **`+0xe0`** |
| `__TEXT.__objc_methlist` | `0x3824` | `0x38f4` | **`+0xd0`** |
| `__AUTH.__objc_data` | `0x16d0` | `0x1720` | **`+0x50`** |
| `__TEXT.__cstring` | `0x1b86` | `0x1bc7` | **`+0x41`** |
| `__AUTH_CONST.__cfstring` | `0x23e0` | `0x2420` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1680` | `0x16b8` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x1060` | `0x1090` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x2987` | `0x295e` | **`-0x29`** |
| `__DATA_CONST.__got` | `0x400` | `0x408` | **`+0x8`** |
| `__DATA_CONST.__objc_classlist` | `0x358` | `0x360` | **`+0x8`** |
| `__DATA_CONST.__objc_superrefs` | `0x1b8` | `0x1c0` | **`+0x8`** |
| `__TEXT.__const` | `0x138` | `0x140` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x2e0` | `0x2e4` | **`+0x4`** |

### Other Changes

```diff

-6.0.38.0.0
+6.0.42.1.0

-  Functions: 1336
-  Symbols:   2728
-  CStrings:  525
+  Functions: 1352
+  Symbols:   2752
+  CStrings:  531
Symbols:
+ +[BLSInvalidOnSystemSleepAttribute invalidateOnSystemSleepAfterMinimumActiveInterval:]
+ +[BLSInvalidOnSystemSleepAttribute supportsSecureCoding]
+ +[BLSValidOnSystemSleepAttribute validOnSystemSleep]
+ -[BLSBacklightSceneVisualState flipbookUsesLowPowerRendering]
+ -[BLSBacklightSceneVisualState isEqualAppearanceToVisualState:]
+ -[BLSBacklightSceneVisualState newVisualStateWithFlipbookUsesLowPowerRendering:]
+ -[BLSInvalidOnSystemSleepAttribute copyWithZone:]
+ -[BLSInvalidOnSystemSleepAttribute description]
+ -[BLSInvalidOnSystemSleepAttribute encodeWithCoder:]
+ -[BLSInvalidOnSystemSleepAttribute encodeWithXPCDictionary:]
+ -[BLSInvalidOnSystemSleepAttribute hash]
+ -[BLSInvalidOnSystemSleepAttribute initWithCoder:]
+ -[BLSInvalidOnSystemSleepAttribute initWithMinimumActiveInterval:]
+ -[BLSInvalidOnSystemSleepAttribute initWithXPCDictionary:]
+ -[BLSInvalidOnSystemSleepAttribute isEqual:]
+ -[BLSInvalidOnSystemSleepAttribute minimumActiveInterval]
+ _OBJC_CLASS_$_BLSValidOnSystemSleepAttribute
+ _OBJC_IVAR_$_BLSInvalidOnSystemSleepAttribute._minimumActiveInterval
+ _OBJC_METACLASS_$_BLSValidOnSystemSleepAttribute
+ __OBJC_$_CLASS_METHODS_BLSValidOnSystemSleepAttribute
+ __OBJC_$_INSTANCE_VARIABLES_BLSInvalidOnSystemSleepAttribute
+ __OBJC_$_PROP_LIST_BLSInvalidOnSystemSleepAttribute
+ __OBJC_CLASS_RO_$_BLSValidOnSystemSleepAttribute
+ __OBJC_METACLASS_RO_$_BLSValidOnSystemSleepAttribute
+ ___block_descriptor_104_e8_32s40r48r56r64r72r80r88r96r_e29_v32?0"BLSAttribute"8Q16^B24lr40l8r48l8s32l8r56l8r64l8r72l8r80l8r88l8r96l8
- ___block_descriptor_96_e8_32s40r48r56r64r72r80r88r_e29_v32?0"BLSAttribute"8Q16^B24lr40l8r48l8s32l8r56l8r64l8r72l8r80l8r88l8
CStrings:
+ "(+start) "
+ "FB "
+ "LPR "
+ "LPR-FB "
+ "flipbookUsesLPR"
+ "frameSpecifiersResponse %s%smodel.count:%lu %{public}@ for %{public}@"
+ "minimumActiveInterval"
- "performFrameSpecifiersRequest model.specifierCount:%lu dateSpecifers:%{public}@ for frameSpecifiers:%{public}@"
```
