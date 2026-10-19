## OSAnalytics

> `/System/Library/PrivateFrameworks/OSAnalytics.framework/OSAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH_CONST.__cfstring` | `0xa240` | `0xa1c0` | **`-0x80`** |
| `__DATA_CONST.__const` | `0x1320` | `0x12d8` | **`-0x48`** |
| `__TEXT.__text` | `0x4b2d8` | `0x4b314` | **`+0x3c`** |
| `__TEXT.__cstring` | `0x932a` | `0x930a` | **`-0x20`** |
| `__AUTH_CONST.__auth_got` | `0xe90` | `0xe88` | **`-0x8`** |

### Other Changes

```diff

-  Symbols:   2119
-  CStrings:  1863
+  Symbols:   2118
+  CStrings:  1859
Symbols:
- _objc_release_x10
Functions:
~ _OSAIsFeedbackPromptingEnabled : 60 -> 64
~ -[OSAProxyConfiguration isFile:validForSubmission:reasonableSize:to:internalTypes:result:] : 2064 -> 1992
~ ___40-[OSASystemConfiguration sysVersionData]_block_invoke : 692 -> 608
~ -[OSASystemConfiguration isOnDeviceLogType:] : 240 -> 196
~ _rtcsc_send_base : 608 -> 864
CStrings:
+ "GM"
- "%@-seed"
- "Carrier"
- "CarrierSeed"
- "Seed"
- "seed"
```
