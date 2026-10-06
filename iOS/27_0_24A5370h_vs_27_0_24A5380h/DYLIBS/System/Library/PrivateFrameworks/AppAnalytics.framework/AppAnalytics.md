## AppAnalytics

> `/System/Library/PrivateFrameworks/AppAnalytics.framework/AppAnalytics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x14a3d4` | `0x14b990` | **`+0x15bc`** |
| `__DATA.__bss` | `0x9d00` | `0x9b80` | **`-0x180`** |
| `__DATA_DIRTY.__bss` | `0x5800` | `0x5980` | **`+0x180`** |
| `__DATA_DIRTY.__data` | `0x5ec8` | `0x6048` | **`+0x180`** |
| `__DATA.__data` | `0x16d0` | `0x15c0` | **`-0x110`** |
| `__TEXT.__swift5_capture` | `0x2938` | `0x2a20` | **`+0xe8`** |
| `__AUTH.__data` | `0x848` | `0x7b8` | **`-0x90`** |
| `__TEXT.__oslogstring` | `0x2c3f` | `0x2caf` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0xbe18` | `0xbe68` | **`+0x50`** |
| `__DATA.__common` | `0xa0` | `0x70` | **`-0x30`** |
| `__DATA_DIRTY.__common` | `0x150` | `0x180` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x2f97` | `0x2fa7` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x41cc` | `0x41d8` | **`+0xc`** |
| `__TEXT.__eh_frame` | `0x5b78` | `0x5b80` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x48e0` | `0x48e8` | **`+0x8`** |

### Other Changes

```diff

-570.0.0.0.0
+573.0.0.0.0

-  Functions: 6838
-  Symbols:   2139
-  CStrings:  504
+  Functions: 6839
+  Symbols:   2138
+  CStrings:  505
Symbols:
+ ___swift_closure_destructor.29Tm
- ___swift_closure_destructor.52Tm
- ___swift_closure_destructor.5Tm
CStrings:
+ "TrackingConsent: observing UIApplication.willEnterForegroundNotification for consent reconciliation"
```
