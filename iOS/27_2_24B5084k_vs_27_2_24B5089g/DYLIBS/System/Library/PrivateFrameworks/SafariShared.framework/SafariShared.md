## SafariShared

> `/System/Library/PrivateFrameworks/SafariShared.framework/SafariShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b3bb8` | `0x2b6720` | **`+0x2b68`** |
| `__AUTH_CONST.__auth_got` | `0x2bd0` | `0x2d70` | **`+0x1a0`** |
| `__TEXT.__swift5_capture` | `0x1010` | `0x1154` | **`+0x144`** |
| `__TEXT.__unwind_info` | `0xeeb8` | `0xefe0` | **`+0x128`** |
| `__TEXT.__const` | `0xa3734` | `0xa3854` | **`+0x120`** |
| `__DATA_CONST.__got` | `0x2028` | `0x2120` | **`+0xf8`** |
| `__AUTH_CONST.__const` | `0xb440` | `0xb4f0` | **`+0xb0`** |
| `__TEXT.__eh_frame` | `0x54d0` | `0x5580` | **`+0xb0`** |
| `__DATA_CONST.__const` | `0x165a8` | `0x16630` | **`+0x88`** |
| `__TEXT.__constg_swiftt` | `0x2144` | `0x21c0` | **`+0x7c`** |
| `__DATA.__data` | `0x5778` | `0x57c8` | **`+0x50`** |
| `__TEXT.__swift5_builtin` | `0x140` | `0x190` | **`+0x50`** |
| `__TEXT.__swift5_fieldmd` | `0x1884` | `0x18c4` | **`+0x40`** |
| `__TEXT.__swift5_typeref` | `0x368a` | `0x36ca` | **`+0x40`** |
| `__TEXT.__swift5_reflstr` | `0x1638` | `0x1668` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x15ce2` | `0x15cc2` | **`-0x20`** |
| `__DATA.__bss` | `0x7a40` | `0x7a50` | **`+0x10`** |
| `__TEXT.__swift5_types` | `0x194` | `0x1a0` | **`+0xc`** |
| `__AUTH.__data` | `0x17a0` | `0x1798` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x28` | `0x30` | **`+0x8`** |
| `__TEXT.__swift_as_cont` | `0x2ec` | `0x2f0` | **`+0x4`** |
| `__TEXT.__swift_as_entry` | `0x180` | `0x184` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x168` | `0x16c` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-625.2.4.1.0
+625.2.5.10.1

+  - /System/Library/PrivateFrameworks/UnilogSafariFeatureLibrary.framework/UnilogSafariFeatureLibrary

-  Functions: 14807
-  Symbols:   19344
+  Functions: 14790
+  Symbols:   19354
Symbols:
+ ___swift_closure_destructor.246Tm
+ _symbolic _____ 12SafariShared24WBSUsageRetentionVariantO
+ _symbolic _____ So30WBSUsageRetentionExtensionTypeV
+ _symbolic _____ So33WBSUsageRetentionAutoFillCategoryV
+ _symbolic _____ So34WBSUsageRetentionPrivacyReportKindV
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary0C5EventV12PayloadUnionO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary13ExtensionTypeO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary16AutoFillCategoryO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary17PrivacyReportTypeO
+ _symbolic _____Sg 26UnilogSafariFeatureLibrary7TriggerO
CStrings:
+ "8625.2.5.10.1"
+ "Donating feature usage: %{public}s/%{public}s%{public}s x%{public}ld"
+ "Donating settings snapshot: nonDefaultProfile=%{bool,public}d iCloudTabs=%{bool,public}d sync=%{bool,public}d extensions=%{bool,public}d"
+ "Pruned donated feature events since %{public}s."
- "8625.2.4.1"
- "Pending feature usage donation: %{public}s/%{public}s%{public}s x%{public}ld"
- "Pending prune of donated feature events since %{public}s."
- "Pending settings snapshot donation: nonDefaultProfile=%{bool,public}d iCloudTabs=%{bool,public}d sync=%{bool,public}d extensions=%{bool,public}d"
```
