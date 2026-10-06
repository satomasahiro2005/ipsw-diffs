## AudioFlowDelegatePlugin

> `/System/Library/Assistant/FlowDelegatePlugins/AudioFlowDelegatePlugin.bundle/AudioFlowDelegatePlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2cc660` | `0x2d0620` | **`+0x3fc0`** |
| `__TEXT.__oslogstring` | `0x245bc` | `0x247bc` | **`+0x200`** |
| `__DATA_CONST.__const` | `0xfd00` | `0xfe30` | **`+0x130`** |
| `__TEXT.__swift5_capture` | `0x6314` | `0x63b0` | **`+0x9c`** |
| `__TEXT.__swift5_typeref` | `0x472a` | `0x47a4` | **`+0x7a`** |
| `__TEXT.__const` | `0xc09a` | `0xc10a` | **`+0x70`** |
| `__DATA.__objc_const` | `0x9dd0` | `0x9e10` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x3660` | `0x3688` | **`+0x28`** |
| `__TEXT.__swift5_reflstr` | `0x422b` | `0x424b` | **`+0x20`** |
| `__TEXT.__constg_swiftt` | `0x5b80` | `0x5b98` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0x6f20` | `0x6f10` | **`-0x10`** |
| `__TEXT.__eh_frame` | `0x36a8` | `0x36b8` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x3f8d` | `0x3f9d` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x3888` | `0x3898` | **`+0x10`** |
| `__TEXT.__swift5_proto` | `0x6fc` | `0x708` | **`+0xc`** |
| `__DATA_CONST.__auth_got` | `0x3798` | `0x3790` | **`-0x8`** |
| `__DATA_CONST.__auth_ptr` | `0x1ab8` | `0x1ac0` | **`+0x8`** |
| `__TEXT.__swift5_protos` | `0x6c` | `0x70` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`

### Other Changes

```diff

-3600.33.17.0.0
+3605.20.1.0.0

-  Functions: 6040
+  Functions: 6051

-  CStrings:  2971
+  CStrings:  2977
CStrings:
+ "AmbiguousPlayFlow#execute self deallocated prematurely during SiriForAirPlayFlow setup, completing"
+ "Parse#getSiriKitIntent Constructing INAddMediaIntent from addMediaSiriKitFallback"
+ "Parse#getSiriKitIntent Constructing INPlayMediaIntent from playMediaSiriKitFallback"
+ "Parse#getSiriKitIntent Constructing INUpdateMediaAffinityIntent from updateMediaAffinitySiriKitFallback"
+ "ResponseFactory+Utilities#effectiveResponseMode forcing .voiceOnly for SFA Now Playing (was %s)"
+ "deviceState"
```
