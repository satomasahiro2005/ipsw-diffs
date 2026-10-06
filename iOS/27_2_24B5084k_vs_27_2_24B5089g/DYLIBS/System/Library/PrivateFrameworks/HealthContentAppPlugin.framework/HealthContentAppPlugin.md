## HealthContentAppPlugin

> `/System/Library/PrivateFrameworks/HealthContentAppPlugin.framework/HealthContentAppPlugin`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x58a38` | `0x5c0f8` | **`+0x36c0`** |
| `__TEXT.__oslogstring` | `0xc78` | `0x1088` | **`+0x410`** |
| `__TEXT.__eh_frame` | `0x1d3c` | `0x1e7c` | **`+0x140`** |
| `__AUTH.__data` | `0x928` | `0x808` | **`-0x120`** |
| `__DATA_DIRTY.__data` | `0x338` | `0x3f8` | **`+0xc0`** |
| `__TEXT.__cstring` | `0xd5e` | `0xcbe` | **`-0xa0`** |
| `__TEXT.__swift5_reflstr` | `0x5b1` | `0x511` | **`-0xa0`** |
| `__TEXT.__swift5_fieldmd` | `0x640` | `0x5b4` | **`-0x8c`** |
| `__AUTH_CONST.__const` | `0xf00` | `0xe80` | **`-0x80`** |
| `__DATA.__bss` | `0x1e18` | `0x1d98` | **`-0x80`** |
| `__TEXT.__const` | `0x1a90` | `0x1a20` | **`-0x70`** |
| `__DATA.__data` | `0xf58` | `0xef0` | **`-0x68`** |
| `__AUTH.__objc_data` | `0x238` | `0x1e8` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `0x50` | `0xa0` | **`+0x50`** |
| `__TEXT.__constg_swiftt` | `0x7a0` | `0x750` | **`-0x50`** |
| `__AUTH_CONST.__auth_got` | `0x1630` | `0x1668` | **`+0x38`** |
| `__AUTH_CONST.__objc_const` | `0x920` | `0x940` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0x3c` | `0x28` | **`-0x14`** |
| `__TEXT.__swift5_typeref` | `0x958` | `0x946` | **`-0x12`** |
| `__TEXT.__unwind_info` | `0xf38` | `0xf48` | **`+0x10`** |
| `__DATA.__common` | `0x50` | `0x48` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x100` | `0x108` | **`+0x8`** |
| `__DATA_DIRTY.__common` | `0x8` | `0x10` | **`+0x8`** |
| `__TEXT.__swift5_types` | `0x78` | `0x70` | **`-0x8`** |
| `__TEXT.__swift5_capture` | `0x42c` | `0x428` | **`-0x4`** |
| `__TEXT.__swift5_proto` | `0x110` | `0x10c` | **`-0x4`** |
| `__TEXT.__swift_as_cont` | `0x164` | `0x168` | **`+0x4`** |

### Other Changes

```diff

-7027.1.36.2.7
+7027.1.45.2.4

-  Functions: 1222
-  Symbols:   471
-  CStrings:  127
+  Functions: 1209
+  Symbols:   463
+  CStrings:  141
Symbols:
+ _objc_retain_x28
+ _swift_retain_n
+ _symbolic SDySS_____G 14HealthPlatform14PluginFeedItemV
+ _symbolic _____ 14HealthPlatform28FileProtectionRetrySchedulerC
+ _symbolic _____ 15HealthContentUI16ImageLoadRequestV6SizingO
- ___swift_memcpy16_8
- _objc_retain_x24
- _swift_bridgeObjectRetain_n
- _swift_cvw_initEnumMetadataSinglePayloadWithLayoutString
- _swift_cvw_singlePayloadEnumGeneric_destructiveInjectEnumTag
- _swift_cvw_singlePayloadEnumGeneric_getEnumTag
- _swift_retain_x23
- _symbolic _____ 12CoreGraphics7CGFloatV
- _symbolic _____ 22HealthContentAppPlugin0aB19DatabaseInputSignalC11PollOutcome33_54155C184453964B476E725C659BD2E5LLO
- _symbolic _____ So6CGSizeV
- _symbolic _____SgXw 22HealthContentAppPlugin0aB19DatabaseInputSignalC
- _symbolic _____SgXwz_Xx 22HealthContentAppPlugin0aB19DatabaseInputSignalC
- _type_layout_string So6CGSizeV
CStrings:
+ "[%{public}s] Creating work plans"
+ "[%{public}s] Device unlocked; retrying."
+ "[%{public}s] Error fetching anchors: %{public}s"
+ "[%{public}s] Fetching anchors for criteria"
+ "[%{public}s] Finding associated data type rooms"
+ "[%{public}s] Incorrect criteria"
+ "[%{public}s] Made %ld blood pressure article feed item(s)"
+ "[%{public}s] Made %ld feed item(s)"
+ "[%{public}s] Made %ld movement chapter item(s)"
+ "[%{public}s] Made %ld spotlight feed item(s)"
+ "[%{public}s] Making blood pressure article feed items"
+ "[%{public}s] Making content room feed items"
+ "[%{public}s] Making movement chapter feed items"
+ "[%{public}s] Making spotlight feed items"
+ "[%{public}s] No content descriptor for category list experience %{public}s"
+ "[%{public}s] No content descriptor for category spotlight experience %{public}s"
+ "[%{public}s] No content descriptor for room list experience %{public}s"
+ "[%{public}s] No content descriptor for spotlight content %{public}s"
+ "[%{public}s] No tagged content found for MovementChapter %{public}s; chapter will be empty"
+ "[%{public}s] No tagged content found for blood pressure article"
+ "[%{public}s] Replacing feed with %{public}ld item(s)"
+ "[%{public}s] Running work plan: %s"
+ "[%{public}s] Updated anchors: %{public}s"
- "[%{public}s] %{public}s — Error fetching anchors: %{public}s"
- "[%{public}s] %{public}s — Updated anchors: %{public}s"
- "[%{public}s] %{public}s — anchors unchanged: %{public}s"
- "[%{public}s] %{public}s — observation stopped before the poll finished: %{public}s"
- "artifact imported"
- "beginObservation"
- "coalesced after "
- "content store reconnected"
- "unrecognized artifact state update"
```
