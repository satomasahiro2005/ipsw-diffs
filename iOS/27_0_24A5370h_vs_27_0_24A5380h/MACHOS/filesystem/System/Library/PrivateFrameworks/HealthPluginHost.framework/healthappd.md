## healthappd

> `/System/Library/PrivateFrameworks/HealthPluginHost.framework/healthappd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x311c0` | `0x317d0` | **`+0x610`** |
| `__TEXT.__oslogstring` | `0x1f31` | `0x2001` | **`+0xd0`** |
| `__TEXT.__auth_stubs` | `0x2360` | `0x2380` | **`+0x20`** |
| `__DATA_CONST.__auth_got` | `0x11b8` | `0x11c8` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6c0` | `0x6b0` | **`-0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__TEXT.__objc_methlist`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-7027.0.60.2.2
+7027.0.64.0.0

-  Functions: 707
+  Functions: 706

-  CStrings:  400
+  CStrings:  402
Symbols:
+ _$s14HealthPlatform21GenerationWorkRequestV11environment24pluginIdentifierSetToRun16generationPhases23commitUrgentTransaction04makecD5Block010completionR0022notStartedCancellationR0AcA26FeedItemContextEnvironmentO_AA06PluginhI0OShyAA0C5PhaseOGSbAA0cD0_pACYbcySbYbcyyYbctcfC
+ _$s14HealthPlatform21GenerationWorkRequestV15completionBlockyySbYbcvg
+ _$s14HealthPlatform21GenerationWorkRequestV15completionBlockyySbYbcvs
- _$s14HealthPlatform21GenerationWorkRequestV15completionBlockyyYbcvg
- _$s14HealthPlatform21GenerationWorkRequestV15completionBlockyyYbcvs
- _swift_willThrowTypedImpl
CStrings:
+ "[%{public}s]: Background generation completed/cancelled, and is completion from coalesced work, so skipping feed population"
+ "[%{public}s]: DAS background was part of coalesced work, skip populating feed"
```
