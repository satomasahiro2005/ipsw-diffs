## AVKitSettings

> `/System/Library/PreferenceBundles/AVKitSettings.bundle/AVKitSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x345a4` | `0x35c38` | **`+0x1694`** |
| `__TEXT.__eh_frame` | `0x32bc` | `0x3114` | **`-0x1a8`** |
| `__TEXT.__swift5_reflstr` | `0x466` | `0x526` | **`+0xc0`** |
| `__AUTH.__data` | `0x568` | `0x620` | **`+0xb8`** |
| `__AUTH_CONST.__objc_const` | `0x7e0` | `0x880` | **`+0xa0`** |
| `__TEXT.__constg_swiftt` | `0x66c` | `0x6f4` | **`+0x88`** |
| `__TEXT.__swift5_typeref` | `0x939` | `0x987` | **`+0x4e`** |
| `__TEXT.__unwind_info` | `0xf80` | `0xf38` | **`-0x48`** |
| `__TEXT.__const` | `0x11b8` | `0x11f8` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x3a0` | `0x3d0` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x7f0` | `0x810` | **`+0x20`** |
| `__TEXT.__swift5_capture` | `0x7fc` | `0x814` | **`+0x18`** |
| `__AUTH_CONST.__const` | `0x1220` | `0x1210` | **`-0x10`** |
| `__DATA.__data` | `0x450` | `0x460` | **`+0x10`** |
| `__TEXT.__cstring` | `0x497` | `0x487` | **`-0x10`** |
| `__TEXT.__swift_as_entry` | `0x158` | `0x15c` | **`+0x4`** |

### Other Changes

```diff

-1360.69.1.0.0
+1360.75.1.3.0

-  Functions: 873
-  Symbols:   430
+  Functions: 888
+  Symbols:   436
Symbols:
+ ___swift_closure_destructor.250Tm
+ ___unnamed_5
+ _symbolic SDySS_____G s6UInt64V
+ _symbolic SDySSyyYaYbcG
+ _symbolic ScP
+ _symbolic ScTyyt_____G s5NeverO
+ _symbolic _____ySS_____G s18_DictionaryStorageC s6UInt64V
+ _symbolic _____ySSyyYaYbcG s18_DictionaryStorageC
- ___swift_closure_destructor.237Tm
- ___unnamed_4
CStrings:
+ "[%s] .AVInputContextCanSetInputGainDidChange received: canSetInputGain: %{bool}d"
+ "computePickedRoute(skipNotify:)"
- "[%s] .AVInputContextCanSetInputGainDidChange received"
- "updatePickedRoutesIfNeeded(skipNotify:)"
```
