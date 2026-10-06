## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/TipsDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9e980` | `0xa0254` | **`+0x18d4`** |
| `__TEXT.__eh_frame` | `0x4b58` | `0x4cd8` | **`+0x180`** |
| `__TEXT.__cstring` | `0x42fc` | `0x428c` | **`-0x70`** |
| `__TEXT.__unwind_info` | `0x2cc8` | `0x2d08` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x954` | `0x988` | **`+0x34`** |
| `__TEXT.__constg_swiftt` | `0xe88` | `0xeac` | **`+0x24`** |
| `__AUTH_CONST.__auth_got` | `0x1240` | `0x1220` | **`-0x20`** |
| `__TEXT.__const` | `0x3218` | `0x3238` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2678` | `0x2690` | **`+0x18`** |
| `__TEXT.__swift5_reflstr` | `0x65e` | `0x66e` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xd18` | `0xd20` | **`+0x8`** |
| `__TEXT.__swift5_capture` | `0x748` | `0x740` | **`-0x8`** |
| `__TEXT.__swift5_typeref` | `0x117c` | `0x1182` | **`+0x6`** |
| `__TEXT.__swift_as_entry` | `0x13c` | `0x140` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x204` | `0x208` | **`+0x4`** |

### Other Changes

```diff

-855.0.0.0.0
+857.0.0.0.0

-  Functions: 3296
+  Functions: 3307

-  CStrings:  801
+  CStrings:  798
Symbols:
+ _symbolic _____ 10TipsDaemon15LookbackWindows33_54317CBD72E44AB0A8742735CDEDFE2ELLV
- _swift_release_x10
CStrings:
+ " eligible sessions for lookback"
+ " sessions eligible, processing oldest "
+ "Lookback backlog: "
+ "Lookback windows (s) — hour: "
- " sessions for lookback analysis"
- "Lookback multiplier: "
- "One day duration: "
- "One hour duration: "
- "One week duration: "
- "Successfully logged lookback event"
- "Threshold to process lookback events: "
```
