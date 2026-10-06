## OSAnalytics

> `/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xa1c0` | `0xa240` | **`+0x80`** |
| `__TEXT.__text` | `0x4b1e4` | `0x4b240` | **`+0x5c`** |
| `__DATA_CONST.__const` | `0x12d8` | `0x1320` | **`+0x48`** |
| `__TEXT.__cstring` | `0x930a` | `0x932a` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0xe88` | `0xe90` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xdf8` | `0xe00` | **`+0x8`** |

### Other Changes

```diff

-1056.2.1.0.0
+1056.40.5.0.0

-  Symbols:   2118
-  CStrings:  1859
+  Symbols:   2119
+  CStrings:  1863
Symbols:
+ _objc_release_x10
Functions:
~ _OSAIsFeedbackPromptingEnabled : 64 -> 60
~ -[OSAProxyConfiguration isFile:validForSubmission:reasonableSize:to:internalTypes:result:] : 1992 -> 2064
~ ___40-[OSASystemConfiguration sysVersionData]_block_invoke : 608 -> 692
~ -[OSASystemConfiguration isOnDeviceLogType:] : 196 -> 240
~ -[OSACrackShotReport saveWithOptions:] : 168 -> 320
~ _rtcsc_send_base : 864 -> 608
CStrings:
+ "%@-seed"
+ "Carrier"
+ "CarrierSeed"
+ "Seed"
+ "seed"
- "GM"
```
