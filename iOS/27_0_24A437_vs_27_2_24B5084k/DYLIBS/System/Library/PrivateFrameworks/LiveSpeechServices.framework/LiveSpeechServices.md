## LiveSpeechServices

> `/System/Library/PrivateFrameworks/LiveSpeechServices.framework/LiveSpeechServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5928` | `0x62e4` | **`+0x9bc`** |
| `__TEXT.__oslogstring` | `0x3b6` | `0x556` | **`+0x1a0`** |
| `__AUTH_CONST.__const` | `0x720` | `0x7e8` | **`+0xc8`** |
| `__TEXT.__eh_frame` | `0x160` | `0x1d0` | **`+0x70`** |
| `__TEXT.__objc_methlist` | `0x374` | `0x3bc` | **`+0x48`** |
| `__TEXT.__swift5_reflstr` | `0x115` | `0x155` | **`+0x40`** |
| `__TEXT.__swift5_capture` | `0xfc` | `0x12c` | **`+0x30`** |
| `__TEXT.__unwind_info` | `0x290` | `0x2c0` | **`+0x30`** |
| `__TEXT.__swift5_fieldmd` | `0x12c` | `0x150` | **`+0x24`** |
| `__AUTH_CONST.__objc_const` | `0x438` | `0x458` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x3a0` | `0x3b0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1d8` | `0x1e8` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x70` | `0x80` | **`+0x10`** |
| `__TEXT.__const` | `0x618` | `0x628` | **`+0x10`** |
| `__DATA_DIRTY.__objc_data` | `0x190` | `0x198` | **`+0x8`** |

### Other Changes

```diff

-3240.9.0.0.0
+3245.7.1.0.0

-  Functions: 242
-  Symbols:   246
-  CStrings:  29
+  Functions: 261
+  Symbols:   249
+  CStrings:  38
Symbols:
+ +[LiveSpeechServicesObjc startChatterboxAndReturnError:]
+ +[LiveSpeechServicesObjc stopChatterboxAndReturnError:]
+ _AXDeviceSupportsChatterbox
CStrings:
+ "Already running Chatterbox, skip"
+ "Can't stop Chatterbox, not running"
+ "Chatterbox not supported, skip"
+ "Client received Chatterbox start success callback"
+ "Client received Chatterbox stop success callback"
+ "Client requesting Chatterbox start"
+ "Client requesting Chatterbox stop"
+ "Failed to start Chatterbox: %@"
+ "Failed to stop Chatterbox: %@"
```
