## SecurePairing

> `/System/Library/PrivateFrameworks/SecurePairing.framework/SecurePairing`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x7175c` | `0x722c4` | **`+0xb68`** |
| `__TEXT.__oslogstring` | `0xdc4` | `0xe64` | **`+0xa0`** |
| `__TEXT.__const` | `0xadcc` | `0xae3c` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x5ff0` | `0x6018` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x3a0` | `0x3bc` | **`+0x1c`** |
| `__AUTH_CONST.__auth_got` | `0xba0` | `0xbb8` | **`+0x18`** |
| `__TEXT.__eh_frame` | `0x447c` | `0x448c` | **`+0x10`** |
| `__TEXT.__swift5_reflstr` | `0x1054` | `0x1044` | **`-0x10`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-58.0.0.0.0
+59.0.0.0.0

-  Functions: 2573
-  Symbols:   1232
-  CStrings:  203
+  Functions: 2577
+  Symbols:   1234
+  CStrings:  205
Symbols:
+ _swift_unexpectedError
+ _symbolic _____ s8DurationV
+ _symbolic _____ySiG s23_ContiguousArrayStorageC
+ _type_layout_string s8DurationV
- _symbolic _____y_____GSg 13SecurePairing7MessageV AA05SigmaB8ProtocolV7PayloadO
- _type_layout_string 13SecurePairing0aB9DaemonXPCO10XPCRequestO24SigmaRequestTestPasscodeV15ResponseMessageV
CStrings:
+ "Option.audioPlaybackDelayMS is too short, using default value %s"
+ "Option.audioPlaybackDurationMS is too short, using default value %s"
+ "Session timeout set to %ss"
+ "scheduleTimeout(for:)"
- "Session timeout set to %lds"
- "scheduleTimeout(seconds:)"
```
