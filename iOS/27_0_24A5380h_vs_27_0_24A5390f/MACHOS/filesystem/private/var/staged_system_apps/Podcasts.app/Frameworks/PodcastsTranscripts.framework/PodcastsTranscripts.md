## PodcastsTranscripts

> `/private/var/staged_system_apps/Podcasts.app/Frameworks/PodcastsTranscripts.framework/PodcastsTranscripts`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x987ac` | `0x98c88` | **`+0x4dc`** |
| `__TEXT.__objc_methname` | `0x3d2f` | `0x3d8f` | **`+0x60`** |
| `__DATA_CONST.__const` | `0x4038` | `0x4088` | **`+0x50`** |
| `__TEXT.__objc_stubs` | `0x2580` | `0x25c0` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x100c` | `0x103c` | **`+0x30`** |
| `__DATA.__data` | `0x4278` | `0x4258` | **`-0x20`** |
| `__DATA.__objc_const` | `0x2b98` | `0x2bb8` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0x39d0` | `0x39b0` | **`-0x20`** |
| `__TEXT.__cstring` | `0xed2` | `0xef2` | **`+0x20`** |
| `__TEXT.__swift5_reflstr` | `0x1c03` | `0x1c23` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x5358` | `0x536c` | **`+0x14`** |
| `__DATA.__common` | `0xd8` | `0xc8` | **`-0x10`** |
| `__DATA.__objc_selrefs` | `0xce8` | `0xcf8` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x1cf0` | `0x1ce0` | **`-0x10`** |
| `__TEXT.__const` | `0x6d38` | `0x6d48` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0xd10` | `0xd20` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1ac0` | `0x1acc` | **`+0xc`** |
| `__DATA.__objc_data` | `0x11d8` | `0x11e0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2168` | `0x2170` | **`+0x8`** |

### Same-size Content Changes

- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-4027.100.75.0.0
+4027.100.80.0.0

-  Functions: 3136
-  Symbols:   1842
-  CStrings:  841
+  Functions: 3144
+  Symbols:   1845
+  CStrings:  846
Symbols:
+ _OBJC_CLASS_$_UIUpdateActionPhase
+ _OBJC_CLASS_$_UIUpdateLink
+ __swift_closure_destructor.78Tm
+ _objc_msgSend$addActionToPhase:handler:
+ _objc_msgSend$afterUpdateScheduled
+ _objc_msgSend$setEnabled:
+ _objc_msgSend$setRequiresContinuousUpdates:
+ _objc_msgSend$updateLinkForView:
+ _symbolic So12UIUpdateLinkCSg
+ _symbolic So12UIUpdateLinkCSgXw
- _NSRunLoopCommonModes
- _OBJC_CLASS_$_CADisplayLink
- __swift_closure_destructor.71Tm
- _objc_msgSend$addToRunLoop:forMode:
- _objc_msgSend$setPaused:
- _objc_msgSend$setPreferredFrameRateRange:
- _symbolic So13CADisplayLinkCSg
CStrings:
+ "$__lazy_storage_$_uiUpdateLink"
+ "NO_INTERNET_CONNECTION_MESSAGE"
+ "addActionToPhase:handler:"
+ "afterUpdateScheduled"
+ "setEnabled:"
+ "setRequiresContinuousUpdates:"
+ "uiUpdateLink"
+ "updateLinkForView:"
+ "v24@?0@\"UIUpdateLink\"8@\"UIUpdateInfo\"16"
- "addToRunLoop:forMode:"
- "displayLink"
- "setPaused:"
- "setPreferredFrameRateRange:"
```
