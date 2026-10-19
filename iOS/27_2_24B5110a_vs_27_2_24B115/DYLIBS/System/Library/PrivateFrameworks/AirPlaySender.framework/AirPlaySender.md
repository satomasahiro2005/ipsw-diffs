## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/AirPlaySender`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x24857c` | `0x248854` | **`+0x2d8`** |
| `__AUTH_CONST.__cfstring` | `0x14aa0` | `0x14ac0` | **`+0x20`** |
| `__TEXT.__cstring` | `0x901d6` | `0x901f4` | **`+0x1e`** |
| `__DATA_CONST.__const` | `0x77e8` | `0x77f8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x23d0` | `0x23d8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x5990` | `0x5988` | **`-0x8`** |

### Other Changes

```diff

-  Functions: 11508
-  Symbols:   8721
-  CStrings:  11689
+  Functions: 11505
+  Symbols:   8723
+  CStrings:  11690
Symbols:
+ _APSGetSurroundRoleFromClusterMemberID
+ _APSIsHomeTheaterSurroundEnabled
+ _kAPEndpointDescriptionProperty_SurroundRole
+ _kAPEndpointProperty_SurroundRole
+ _kAPSEndpointStreamAudioHoseRegistrarRegistrationOption_SurroundRole
- _APSEndpointStreamAudioHoseRegistrarRegisterProtocolDriverHoseLegacy
- _APSKeyHolderCreateEncryptionKeysForStream
- _audioStream_preWarmNANDataSession
CStrings:
+ "OSStatus bufferedAudioEngine_createLatencyManagerEndpointOptions(FigEndpointStreamAudioEngineRef, APSAudioProtocolDriverHoseControlRef, APSSurroundRole, CFDictionaryRef *)"
+ "SurroundRole"
- "OSStatus bufferedAudioEngine_createLatencyManagerEndpointOptions(FigEndpointStreamAudioEngineRef, APSAudioProtocolDriverHoseControlRef, CFDictionaryRef *)"
```
