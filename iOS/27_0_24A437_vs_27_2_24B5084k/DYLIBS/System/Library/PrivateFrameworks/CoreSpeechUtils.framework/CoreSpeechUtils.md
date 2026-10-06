## CoreSpeechUtils

> `/System/Library/PrivateFrameworks/CoreSpeechUtils.framework/CoreSpeechUtils`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x39bd4` | `0x3aac0` | **`+0xeec`** |
| `__AUTH_CONST.__objc_const` | `0x2248` | `0x2398` | **`+0x150`** |
| `__TEXT.__const` | `0x2288` | `0x2368` | **`+0xe0`** |
| `__TEXT.__oslogstring` | `0x10ae` | `0x114e` | **`+0xa0`** |
| `__TEXT.__swift5_typeref` | `0x5b6` | `0x650` | **`+0x9a`** |
| `__AUTH_CONST.__const` | `0x2298` | `0x2328` | **`+0x90`** |
| `__DATA.__bss` | `0x1080` | `0x1100` | **`+0x80`** |
| `__DATA.__data` | `0x4e8` | `0x550` | **`+0x68`** |
| `__TEXT.__cstring` | `0x18c3` | `0x1923` | **`+0x60`** |
| `__TEXT.__swift5_fieldmd` | `0x1b5c` | `0x1b84` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xb98` | `0xbc0` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x484` | `0x4a4` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0xe94` | `0xeb0` | **`+0x1c`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a8` | `0x2c0` | **`+0x18`** |
| `__TEXT.__swift5_builtin` | `0x28` | `0x3c` | **`+0x14`** |
| `__TEXT.__swift5_reflstr` | `0x19fc` | `0x1a0c` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x778` | `0x780` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x178` | `0x180` | **`+0x8`** |
| `__TEXT.__swift5_mpenum` | `—` | `0x8` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0xac` | `0xb0` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x104` | `0x108` | **`+0x4`** |

### Other Changes

```diff

-3600.70.47.11.1
+3605.23.1.0.0

-  Functions: 2069
-  Symbols:   461
-  CStrings:  234
+  Functions: 2093
+  Symbols:   469
+  CStrings:  238
Symbols:
+ ___swift_memcpy41_8
+ _get_enum_tag_for_layout_string 15CoreSpeechUtils32SecureRemoteMicVoiceTriggerEventO
+ _swift_cvw_enumFn_getEnumTag
+ _swift_release_x22
+ _symbolic Say_____G20secureTriggerPayload______0abC6LengthAD9timeStampAD15sampleFrameTimeAD07triggerD6Framest s5UInt8V s6UInt64V
+ _symbolic _____ 15CoreSpeechUtils32SecureRemoteMicVoiceTriggerEventO
+ _symbolic _____18startHostTimeStamp_AA03endbcD0Sf5scoret s6UInt64V
+ _type_layout_string 15CoreSpeechUtils32SecureRemoteMicVoiceTriggerEventO
CStrings:
+ "Refusing to encode SecureRemoteMicVoiceTriggerEvent.activation: secureTriggerPayload has %ld bytes, secureTriggerPayloadLength %llu, expected at most %llu."
+ "inRequestSegmentLengthInSecs"
+ "inSpeakerSegmentThreshold"
+ "invocationUserThreshold"
```
