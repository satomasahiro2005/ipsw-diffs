## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Rapport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xd9160` | `0xd96a8` | **`+0x548`** |
| `__AUTH.__objc_data` | `0x1000` | `0x1280` | **`+0x280`** |
| `__DATA_DIRTY.__objc_data` | `0x1598` | `0x1318` | **`-0x280`** |
| `__TEXT.__cstring` | `0x1463c` | `0x145dc` | **`-0x60`** |
| `__AUTH_CONST.__objc_const` | `0x11268` | `0x11298` | **`+0x30`** |
| `__AUTH.__data` | `0x510` | `0x538` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x2610` | `0x25e8` | **`-0x28`** |
| `__AUTH_CONST.__auth_got` | `0x1150` | `0x1130` | **`-0x20`** |
| `__DATA_CONST.__got` | `0x4b0` | `0x4d0` | **`+0x20`** |
| `__DATA_DIRTY.__data` | `0x5a8` | `0x588` | **`-0x20`** |
| `__TEXT.__oslogstring` | `0x236d` | `0x238d` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x44b0` | `0x44c8` | **`+0x18`** |
| `__TEXT.__objc_methlist` | `0x9ef0` | `0x9f08` | **`+0x18`** |
| `__DATA.__bss` | `0x2ea0` | `0x2e90` | **`-0x10`** |
| `__DATA_DIRTY.__bss` | `0xb4` | `0xc4` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x2790` | `0x2798` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2e68` | `0x2e70` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x10e8` | `0x10ec` | **`+0x4`** |
| `__TEXT.__gcc_except_tab` | `0x1444` | `0x1448` | **`+0x4`** |

### Other Changes

```diff

-743.100.4.0.0
+745.100.4.0.0

-  Functions: 5734
-  Symbols:   6737
-  CStrings:  3017
+  Functions: 5733
+  Symbols:   6738
+  CStrings:  3016
Symbols:
+ -[RPSiriSession _sendSiriAudioEventWithMediaData:packetDescriptions:linearGain:]
+ -[RPSiriSession isVoiceTrigger]
+ -[RPSiriSession sendAudioPackets:linearGain:]
+ -[RPSiriSession setIsVoiceTrigger:]
+ _OBJC_CLASS_$_NSMutableData
+ _OBJC_IVAR_$_RPSiriSession._isVoiceTrigger
+ _RPOptionSiriIsVoiceTrigger
+ ___45-[RPSiriSession sendAudioPackets:linearGain:]_block_invoke
+ ___block_descriptor_60_e8_32s40s48s_e5_v8?0ls32l8s40l8s48l8
+ ___block_descriptor_72_e8_32s40s48r56r64r_e32_Q16?0"NSObject<OS_nw_framer>"8lr48l8r56l8r64l8s32l8s40l8
+ ___swift_closure_destructor.143Tm
+ ___swift_closure_destructor.175Tm
+ ___swift_closure_destructor.236Tm
+ ___swift_closure_destructor.249Tm
- -[RPSiriSession _sendAudioBuffer:linearGain:]
- -[RPSiriSession sendAudioBuffer:linearGain:]
- ___44-[RPSiriSession sendAudioBuffer:linearGain:]_block_invoke
- ___block_descriptor_56_e8_32s40s_e5_v8?0ls32l8s40l8
- ___block_descriptor_64_e8_32s40s48r56r_e32_Q16?0"NSObject<OS_nw_framer>"8lr48l8r56l8s32l8s40l8
- ___swift_closure_destructor.145Tm
- ___swift_closure_destructor.177Tm
- ___swift_closure_destructor.238Tm
- ___swift_closure_destructor.251Tm
- _nw_framer_connection_state_copy_object_value
- _nw_framer_connection_state_set_object_value
- _swift_retain_x21
- _swift_retain_x27
CStrings:
+ "-[RPSiriSession _sendSiriAudioEventWithMediaData:packetDescriptions:linearGain:]"
+ "Enabling FitnessPairing"
+ "FindNearbyLocalFindableAccessoryExtendedRange"
+ "Send Siri audio: %lu bytes, %lu packets, gain %f"
+ "_isVT"
- "-[RPSiriSession _sendAudioBuffer:linearGain:]"
- "-[RPSiriSession voiceControllerAudioCallback:forStream:buffer:]_block_invoke"
- "Send Siri audio: TS 0x%016llX, %d bytes, %d packets, %d channels, gain %f"
- "Send Siri audio: TS 0x%016llX, %d bytes, %d packets, %d channels, gain %f\n"
- "started"
- "true"
```
