## MercuryPosterExtension

> `/System/Library/ExtensionKit/Extensions/MercuryPosterExtension.appex/MercuryPosterExtension`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfc0f4` | `0xfcde8` | **`+0xcf4`** |
| `__DATA.__objc_const` | `0x6518` | `0x6718` | **`+0x200`** |
| `__TEXT.__objc_methname` | `0x7fe8` | `0x8188` | **`+0x1a0`** |
| `__TEXT.__swift5_reflstr` | `0x40fe` | `0x427e` | **`+0x180`** |
| `__TEXT.__const` | `0xb1b8` | `0xb2c8` | **`+0x110`** |
| `__DATA.__data` | `0x5538` | `0x55f8` | **`+0xc0`** |
| `__TEXT.__swift5_fieldmd` | `0x42e4` | `0x4350` | **`+0x6c`** |
| `__TEXT.__cstring` | `0x30c1` | `0x30f1` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x2285` | `0x22a7` | **`+0x22`** |
| `__TEXT.__eh_frame` | `0x1fe8` | `0x1ff8` | **`+0x10`** |
| `__TEXT.__oslogstring` | `0x2805` | `0x2815` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x58c` | `0x57c` | **`-0x10`** |
| `__TEXT.__unwind_info` | `0x1bc0` | `0x1bc8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-79.0.0.0.0
+82.0.0.0.0

-  Functions: 2733
-  Symbols:   391
-  CStrings:  2114
+  Functions: 2734
+  Symbols:   390
+  CStrings:  2130
Symbols:
+ _CACurrentMediaTime
- _memset
- _swift_willThrowTypedImpl
CStrings:
+ "adaptCutoff"
+ "currentTallest: %f, upper: %f, lower: %f"
+ "distortFadeY"
+ "distortFadeYVelocity"
+ "distortOrbUnlockY"
+ "editorClockChromePoints"
+ "iOS 27 Hero adaptive-sizing spring"
+ "lastFrameTime"
+ "lastUnlockProgressForFade"
+ "lastUseAdaptiveSizing"
+ "petalDistortAmount"
+ "petalDistortFalloff"
+ "petalOrbCenter"
+ "timeHeightRenderingToken"
+ "timeHeightSpringActive"
+ "timeHeightSpringValue"
+ "timeHeightVelocity"
+ "unlockAnimationMult"
- "Unexpected aspect ratio: %f"
- "distortAmount"
```
