## FaceTimeMessageStore

> `/System/Library/PrivateFrameworks/FaceTimeMessageStore.framework/FaceTimeMessageStore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1b5b24` | `0x1bc018` | **`+0x64f4`** |
| `__TEXT.__oslogstring` | `0xa60b` | `0xabfb` | **`+0x5f0`** |
| `__TEXT.__eh_frame` | `0x1089c` | `0x10d34` | **`+0x498`** |
| `__AUTH_CONST.__const` | `0xd8c8` | `0xdb90` | **`+0x2c8`** |
| `__TEXT.__unwind_info` | `0x72f8` | `0x7470` | **`+0x178`** |
| `__TEXT.__swift5_typeref` | `0x577a` | `0x58b0` | **`+0x136`** |
| `__TEXT.__const` | `0x12ce0` | `0x12df0` | **`+0x110`** |
| `__TEXT.__swift5_capture` | `0x2e50` | `0x2f5c` | **`+0x10c`** |
| `__TEXT.__constg_swiftt` | `0x4b30` | `0x4bc0` | **`+0x90`** |
| `__AUTH_CONST.__objc_const` | `0x59f8` | `0x5998` | **`-0x60`** |
| `__TEXT.__swift_as_cont` | `0x9ec` | `0xa38` | **`+0x4c`** |
| `__DATA_DIRTY.__data` | `0x5570` | `0x55b0` | **`+0x40`** |
| `__DATA.__common` | `0x108` | `0x140` | **`+0x38`** |
| `__TEXT.__swift_as_entry` | `0x528` | `0x55c` | **`+0x34`** |
| `__DATA.__data` | `0x1fc0` | `0x1ff0` | **`+0x30`** |
| `__TEXT.__swift_as_ret` | `0x558` | `0x584` | **`+0x2c`** |
| `__AUTH_CONST.__auth_got` | `0x1af8` | `0x1b18` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x277d` | `0x275d` | **`-0x20`** |
| `__DATA.__bss` | `0x123e0` | `0x123f0` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x3c60` | `0x3c58` | **`-0x8`** |
| `__TEXT.__swift5_proto` | `0xf98` | `0xf9c` | **`+0x4`** |
| `__TEXT.__swift5_protos` | `0xdc` | `0xe0` | **`+0x4`** |

### Other Changes

```diff

-1626.200.65.0.0
+1626.200.84.0.0

-  Functions: 11480
-  Symbols:   2982
-  CStrings:  942
+  Functions: 11608
+  Symbols:   2996
+  CStrings:  954
Symbols:
+ ___swift_closure_destructor.123Tm
+ ___swift_closure_destructor.157Tm
+ ___swift_closure_destructor.230Tm
+ ___swift_closure_destructor.365Tm
+ ___swift_closure_destructor.47Tm
+ ___swift_closure_destructor.511Tm
+ ___swift_closure_destructor.59Tm
+ ___swift_closure_destructor.67Tm
+ ___swift_memcpy168_8
+ _flat unique s5Clock_px8DurationsAAPRts_XP
+ _swift_release_x11
+ _swift_task_future_wait_throwing
+ _symbolic $s20FaceTimeMessageStore27VoicemailSpamVerdictReadingP
+ _symbolic 8Duration_____Qyd__ s5ClockP
+ _symbolic SDy_____ScTySb12isSuppressed_Sb9succeededt_____GG 20FaceTimeMessageStore0C15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
+ _symbolic Say_____3old_AA3newtG 20FaceTimeMessageStore0C0C
+ _symbolic Say_____3old_AA3newtG______pIeghHrzo_ 20FaceTimeMessageStore0C0C s5ErrorP
+ _symbolic Say_____G 11CallHistory06RecentA0V
+ _symbolic Sb12isSuppressed_Sb9succeededt
+ _symbolic Sb12isSuppressed_Sb9succeededtIeAgHr_
+ _symbolic ScTySb12isSuppressed_Sb9succeededt_____G s5NeverO
+ _symbolic SccySay_____3old_AA3newtG______pG 20FaceTimeMessageStore0C0C s5ErrorP
+ _symbolic _____3key_ScTySb12isSuppressed_Sb9succeededt_____G5valuet 20FaceTimeMessageStore0C15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
+ _symbolic _____3old_AA3newt 20FaceTimeMessageStore0C0C
+ _symbolic _____Iegr_ 20FaceTimeMessageStore19TranscriptionStatusO
+ _symbolic __________Xj ls5Clock_px8DurationRts_XPXGMq sABV
+ _symbolic _____y_____3old_AB3newtG s23_ContiguousArrayStorageC 20FaceTimeMessageStore0F0C
+ _symbolic _____y_____ScTySb12isSuppressed_Sb9succeededt_____GG s17_NativeDictionaryV 20FaceTimeMessageStore0E15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
+ _symbolic _____y_____ScTySb12isSuppressed_Sb9succeededt_____GG s18_DictionaryStorageC 20FaceTimeMessageStore0E15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
- ___swift_closure_destructor.196Tm
- ___swift_closure_destructor.244Tm
- ___swift_closure_destructor.378Tm
- ___swift_closure_destructor.514Tm
- ___swift_closure_destructor.54Tm
- ___swift_closure_destructor.62Tm
- ___swift_memcpy128_8
- _symbolic SDy_____ScTySb6isSpam_Sb9succeededt_____GG 20FaceTimeMessageStore0C15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
- _symbolic Sb6isSpam_Sb9succeededt
- _symbolic Sb6isSpam_Sb9succeededtIeAgHr_
- _symbolic ScTySb6isSpam_Sb9succeededt_____G s5NeverO
- _symbolic _____3key_ScTySb6isSpam_Sb9succeededt_____G5valuet 20FaceTimeMessageStore0C15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
- _symbolic __________Ieghgr_ 20FaceTimeMessageStore0C0C AA11HistoryItemO
- _symbolic _____y_____ScTySb6isSpam_Sb9succeededt_____GG s17_NativeDictionaryV 20FaceTimeMessageStore0E15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
- _symbolic _____y_____ScTySb6isSpam_Sb9succeededt_____GG s18_DictionaryStorageC 20FaceTimeMessageStore0E15SpamCoordinatorC13ResolutionKey33_03A8709C4202228E68510E89261D91A3LLV s5NeverO
CStrings:
+ "Dropping pending record(s) that vanished: %{public}s"
+ "Dropping pending record(s) that were trashed: %{public}s"
+ "Finished %{public}s inference for message with recordUUID %{public}s: classification=%{public}s"
+ "Joining the in-flight arrival hold for message with recordUUID %{public}s"
+ "Not reporting %{public}s for message with recordUUID %{public}s because voicemail spam arbitration is disabled"
+ "Not running %{public}s inference for message with recordUUID %{public}s because voicemail spam arbitration is disabled"
+ "Not starting arrival inference for message with recordUUID %{public}s because transcription hasn't finished yet (transcriptionStatus=%{public}s)"
+ "Not suppressing the message with recordUUID %{public}s because of a recent emergency call"
+ "Not suppressing the message with recordUUID %{public}s; the recent-emergency-call check failed, erring safe and leaving it pending for retry: %{public}@"
+ "Removing the notification for the message with recordUUID %{public}s because the user reported it as spam"
+ "Resolved %{public}s verdict for message with recordUUID %{public}s: isSpam=%{bool,public}d authoritative=%{bool,public}d transcriptionStatus=%{public}s path=%{public}s"
+ "Resolved the spam verdict for the voicemail with recordUUID %{public}s isSuppressed %{bool,public}d"
+ "Retrying arrival resolution for %{public}s after transcript became available"
+ "Running %{public}s inference for %{public}ld of %{public}ld pending message(s)"
+ "Skipping %{public}s inference because no pending message has aged past its own delayed window yet"
+ "Skipping %{public}s inference for message with recordUUID %{public}s because transcription hasn't finished yet (transcriptionStatus=%{public}s)"
+ "Waiting for the in-flight arrival resolution for message with recordUUID %{public}s before running %{public}s inference"
- "Dropping %{public}ld pending record(s) that are gone or trashed"
- "Finished %{public}s inference for message with recordUUID %{public}s"
- "Resolved the spam verdict for the voicemail with recordUUID %{public}s isSpam %{bool,public}d"
- "Running delayed inference for %{public}ld of %{public}ld pending message(s)"
- "Skipping delayed inference because no message is pending"
```
