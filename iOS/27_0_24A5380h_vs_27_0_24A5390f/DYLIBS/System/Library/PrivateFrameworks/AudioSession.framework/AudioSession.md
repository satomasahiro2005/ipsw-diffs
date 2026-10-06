## AudioSession

> `/System/Library/PrivateFrameworks/AudioSession.framework/AudioSession`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4dd58` | `0x4e010` | **`+0x2b8`** |
| `__TEXT.__oslogstring` | `0x472e` | `0x47f4` | **`+0xc6`** |
| `__AUTH_CONST.__cfstring` | `0x2440` | `0x2480` | **`+0x40`** |
| `__TEXT.__cstring` | `0x39bf` | `0x39df` | **`+0x20`** |
| `__TEXT.__gcc_except_tab` | `0x8e5c` | `0x8e70` | **`+0x14`** |

### Other Changes

```diff

-449.102.0.0.0
+449.105.0.0.0

-  Symbols:   3399
-  CStrings:  744
+  Symbols:   3400
+  CStrings:  750
Symbols:
+ _sysctlbyname
Functions:
~ +[AVAudioApplication(SPI) appleTVSupportsEnhanceDialogue] : 220 -> 440
~ +[AVAudioApplication(SPI) iosDeviceSupportsEnhanceDialogue] : 64 -> 292
~ +[AVAudioApplication(SPI) visionosDeviceSupportsEnhanceDialogue] : 32 -> 280
CStrings:
+ "%25s:%-5d EnhanceDialogue: appleTVSupportsEnhanceDialogue = %@"
+ "%25s:%-5d EnhanceDialogue: iosDeviceSupportsEnhanceDialogue = %@"
+ "%25s:%-5d EnhanceDialogue: visionosDeviceSupportsEnhanceDialogue = %@"
+ "NO"
+ "YES"
+ "hw.optional.arm.FEAT_SME"
```
