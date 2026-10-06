## Siri

> `/Applications/Siri.app/Siri`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf0fa4` | `0xf24b4` | **`+0x1510`** |
| `__TEXT.__cstring` | `0x2455d` | `0x2481d` | **`+0x2c0`** |
| `__TEXT.__objc_methname` | `0x2b95f` | `0x2bb7f` | **`+0x220`** |
| `__TEXT.__objc_stubs` | `0x1b6a0` | `0x1b860` | **`+0x1c0`** |
| `__TEXT.__oslogstring` | `0xdb84` | `0xdc34` | **`+0xb0`** |
| `__TEXT.__const` | `0x30a4` | `0x3134` | **`+0x90`** |
| `__DATA_CONST.__const` | `0x4da8` | `0x4e30` | **`+0x88`** |
| `__TEXT.__objc_methlist` | `0xe400` | `0xe480` | **`+0x80`** |
| `__DATA.__objc_selrefs` | `0x9048` | `0x90b8` | **`+0x70`** |
| `__TEXT.__swift5_capture` | `0x6bc` | `0x710` | **`+0x54`** |
| `__DATA.__objc_const` | `0x10e68` | `0x10eb8` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1308` | `0x1348` | **`+0x40`** |
| `__TEXT.__unwind_info` | `0x3948` | `0x3988` | **`+0x40`** |
| `__TEXT.__auth_stubs` | `0x3030` | `0x3060` | **`+0x30`** |
| `__TEXT.__constg_swiftt` | `0x254c` | `0x2578` | **`+0x2c`** |
| `__TEXT.__swift5_typeref` | `0x2632` | `0x265c` | **`+0x2a`** |
| `__DATA.__data` | `0x47d0` | `0x47f0` | **`+0x20`** |
| `__TEXT.__objc_classname` | `0x1fc3` | `0x1fa3` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0xaf91` | `0xafb1` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1a41` | `0x1a61` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x1828` | `0x1840` | **`+0x18`** |
| `__DATA.__common` | `0x380` | `0x370` | **`-0x10`** |
| `__DATA.__objc_data` | `0x4bc8` | `0x4bd8` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x11c` | `0x120` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__objc_stublist`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__eh_frame`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.55.37.11.4
+3605.22.2.0.0

-  Functions: 5195
-  Symbols:   1862
-  CStrings:  9061
+  Functions: 5209
+  Symbols:   1865
+  CStrings:  9087
Symbols:
+ _objc_retain_x10
+ _swift_isEscapingClosureAtFileLocation
+ _swift_retain_x25
CStrings:
+ " because it does not match presented notification "
+ "#PreprocessNotification Discarding preprocessed response for "
+ "#carplay #autodismiss: follow-up question detected, holding interrupted audio while attending"
+ "#carplay #autodismiss: not resuming interrupted audio, follow-up question pending"
+ "#carplay #autodismiss: resuming interrupted audio while attending, ignoring premptivelyResumeMedia"
+ "%s #dismissal Close Assistant while presenting Visual Intelligence Camera; clearing Siri results only to preserve Tamale"
+ "%s #keyboardInvalidation: Invalidating keyboard window immediately"
+ "-[SRAppDelegate invalidateKeyboardWindow]"
+ "-[SRSiriViewController _performCloseAssistantDismissalWithReason:]"
+ ". A fresh read will drive the response."
+ "_activeKeyboardWindow"
+ "_directionalAccessoryEdgeInsets"
+ "_hideKeyboardIfNeeded"
+ "_performCloseAssistantDismissalWithReason:"
+ "_scrollViewAccessoryInsetsDidChange:"
+ "bulletin"
+ "bulletinID"
+ "constant"
+ "constraintGreaterThanOrEqualToAnchor:"
+ "constraintLessThanOrEqualToAnchor:"
+ "currentRequestBulletinID"
+ "heldPreprocessedResponse"
+ "invalidateKeyboardWindow"
+ "pendingFollowUpQuestion"
+ "shouldResumeInterruptedAudioPlayback(forAttendingState:)"
+ "siriDidDetectFollowUpQuestion"
+ "siriDidDetectFollowUpQuestion()"
+ "siriWillBeginTearDown"
+ "startAutoRecording"
+ "stopAutoRecording"
- "preprocessedAddViews"
- "preprocessedSayIt"
- "preprocessedStreamChunk"
- "reportConcernButtonEnabled"
```
