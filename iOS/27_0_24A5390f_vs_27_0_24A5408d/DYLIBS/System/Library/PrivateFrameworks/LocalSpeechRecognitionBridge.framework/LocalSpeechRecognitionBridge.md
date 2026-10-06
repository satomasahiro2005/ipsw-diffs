## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/LocalSpeechRecognitionBridge`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1db4c` | `0x1dd64` | **`+0x218`** |
| `__TEXT.__oslogstring` | `0x2d14` | `0x2d90` | **`+0x7c`** |
| `__TEXT.__cstring` | `0x4acc` | `0x4b44` | **`+0x78`** |
| `__AUTH_CONST.__objc_const` | `0x3e68` | `0x3ec8` | **`+0x60`** |
| `__AUTH_CONST.__cfstring` | `0x1ac0` | `0x1b00` | **`+0x40`** |
| `__DATA_CONST.__objc_selrefs` | `0x1318` | `0x1350` | **`+0x38`** |
| `__TEXT.__objc_methlist` | `0x256c` | `0x25a4` | **`+0x38`** |
| `__TEXT.__unwind_info` | `0x720` | `0x738` | **`+0x18`** |
| `__DATA.__objc_ivar` | `0x2d0` | `0x2d8` | **`+0x8`** |

### Other Changes

```diff

-3600.70.32.0.0
+3600.70.47.0.0

-  Functions: 749
-  Symbols:   1501
-  CStrings:  611
+  Functions: 754
+  Symbols:   1508
+  CStrings:  615
Symbols:
+ -[LBAudioStreamInfo initWithAudioRecordType:audioRecordDeviceId:recordRoute:audioFormat:streamIdentifier:originatingDeviceType:originatingDeviceSupportsAlwaysListeningHeySiri:originatingDeviceInvocationType:]
+ -[LBAudioStreamInfo originatingDeviceInvocationType]
+ -[LBAudioStreamInfo originatingDeviceSupportsAlwaysListeningHeySiri]
+ -[LBAudioStreamInfo setOriginatingDeviceInvocationType:]
+ -[LBAudioStreamInfo setOriginatingDeviceSupportsAlwaysListeningHeySiri:]
+ GCC_except_table314
+ GCC_except_table328
+ GCC_except_table451
+ GCC_except_table455
+ GCC_except_table461
+ GCC_except_table468
+ GCC_except_table561
+ GCC_except_table677
+ GCC_except_table722
+ _OBJC_IVAR_$_LBAudioStreamInfo._originatingDeviceInvocationType
+ _OBJC_IVAR_$_LBAudioStreamInfo._originatingDeviceSupportsAlwaysListeningHeySiri
- GCC_except_table309
- GCC_except_table323
- GCC_except_table446
- GCC_except_table450
- GCC_except_table456
- GCC_except_table463
- GCC_except_table556
- GCC_except_table672
- GCC_except_table707
CStrings:
+ "%s Failed to decode `originatingDeviceInvocationType`"
+ "%s Failed to decode `originatingDeviceSupportsAlwaysListeningHeySiri`"
+ "LBAudioStreamInfo:::originatingDeviceInvocationType"
+ "LBAudioStreamInfo:::originatingDeviceSupportsAlwaysListeningHeySiri"
```
