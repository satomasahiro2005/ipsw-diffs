## SiriRemembers

> `/System/Library/PrivateFrameworks/SiriRemembers.framework/SiriRemembers`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb522c` | `0xb6c44` | **`+0x1a18`** |
| `__TEXT.__oslogstring` | `0x3f25` | `0x4165` | **`+0x240`** |
| `__AUTH_CONST.__const` | `0x7428` | `0x7648` | **`+0x220`** |
| `__AUTH_CONST.__objc_const` | `0x1468` | `0x1540` | **`+0xd8`** |
| `__AUTH.__data` | `0x4c8` | `0x570` | **`+0xa8`** |
| `__TEXT.__cstring` | `0x33d1` | `0x3461` | **`+0x90`** |
| `__TEXT.__const` | `0x9b54` | `0x9bc4` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0xc60` | `0xccc` | **`+0x6c`** |
| `__TEXT.__constg_swiftt` | `0x203c` | `0x209c` | **`+0x60`** |
| `__TEXT.__unwind_info` | `0x2df8` | `0x2e50` | **`+0x58`** |
| `__DATA.__data` | `0x1510` | `0x1550` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x25c0` | `0x25f8` | **`+0x38`** |
| `__TEXT.__swift5_typeref` | `0x28c1` | `0x28f9` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x718` | `0x748` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x17e8` | `0x1810` | **`+0x28`** |
| `__TEXT.__eh_frame` | `0x4d40` | `0x4d68` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x12c2` | `0x12d2` | **`+0x10`** |
| `__DATA_CONST.__objc_classlist` | `0xa8` | `0xb0` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x2b4` | `0x2bc` | **`+0x8`** |

### Other Changes

```diff

-3605.12.1.0.0
+3605.13.1.0.0

+  - /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices

-  Functions: 5133
-  Symbols:   1625
-  CStrings:  548
+  Functions: 5189
+  Symbols:   1639
+  CStrings:  555
Symbols:
+ _CFNotificationCenterAddObserver
+ _CFNotificationCenterGetDarwinNotifyCenter
+ _CFNotificationCenterRemoveObserver
+ _NSStringFromAFSiriOrchestrationMode
+ _NSStringFromAFSiriUnavailabilityReasons
+ _OBJC_CLASS_$_AFSiriAvailability
+ __DATA__TtC13SiriRemembersP33_9FF6230672138D50B412B1ABD10EC6DE20CapabilitiesObserver
+ __IVARS__TtC13SiriRemembersP33_9FF6230672138D50B412B1ABD10EC6DE20CapabilitiesObserver
+ __METACLASS_DATA__TtC13SiriRemembersP33_9FF6230672138D50B412B1ABD10EC6DE20CapabilitiesObserver
+ _symbolic SbSgIgl_
+ _symbolic _____ 13SiriRemembers0aB20TranscriptForwardingO
+ _symbolic _____ 13SiriRemembers20CapabilitiesObserver33_9FF6230672138D50B412B1ABD10EC6DELLC
+ _symbolic _____XDXMT 13SiriRemembers20CapabilitiesObserver33_9FF6230672138D50B412B1ABD10EC6DELLC
+ _symbolic _____ySbSgG 13SiriRemembers6AtomicC
CStrings:
+ "SiriRemembersDonationFromAppIntentsListener: ignored event since Siri is not orchestrating on Linwood"
+ "TranscriptForwarding: AFSiriAvailability.fromPreferences() is nil, reading from app.intents (context=%{public}s)"
+ "TranscriptForwarding: allowTranscriptDonationForward is off, reading from app.intents (context=%{public}s)"
+ "TranscriptForwarding: isEnabled=%{bool}d, context=%{public}s, desiredOrchestrationMode=%{public}s, isAvailable=%{bool}d, siriLocale=%{public}s, unavailabilityReasons=%{public}s, missingLinwoodCapabilities=%{public}s"
+ "capabilitiesDidChange"
+ "com.apple.SiriRemembers.TranscriptForwarding"
+ "com.apple.siri.orchestration.capabilities.didChange"
```
