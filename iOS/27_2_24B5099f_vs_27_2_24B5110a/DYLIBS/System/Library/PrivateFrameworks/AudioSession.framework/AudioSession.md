## AudioSession

> `/System/Library/PrivateFrameworks/AudioSession.framework/AudioSession`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4f098` | `0x4f168` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x9010` | `0x9038` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x2280` | `0x22a0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x3a4f` | `0x3a61` | **`+0x12`** |
| `__DATA_CONST.__objc_selrefs` | `0x1680` | `0x1688` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x2364` | `0x236c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2fa0` | `0x2fa8` | **`+0x8`** |

### Other Changes

```diff

-449.204.0.0.0
+449.207.0.0.0

-  Functions: 1761
-  Symbols:   3434
-  CStrings:  752
+  Functions: 1762
+  Symbols:   3436
+  CStrings:  753
Symbols:
+ +[AVAudioApplication(SPI) homeAccessorySupportsEnhanceDialogue]
+ GCC_except_table200
+ GCC_except_table91
+ _MGGetSInt32Answer
- GCC_except_table101
- GCC_except_table145
Functions:
~ +[AVAudioApplication(SPI) currentRouteSupportsEnhanceDialogue:] : 1300 -> 1464
+ +[AVAudioApplication(SPI) homeAccessorySupportsEnhanceDialogue]
CStrings:
+ "DeviceClassNumber"
```
