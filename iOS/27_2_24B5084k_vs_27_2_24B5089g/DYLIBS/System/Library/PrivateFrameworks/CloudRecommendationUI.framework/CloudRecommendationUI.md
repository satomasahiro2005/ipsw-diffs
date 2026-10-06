## CloudRecommendationUI

> `/System/Library/PrivateFrameworks/CloudRecommendationUI.framework/CloudRecommendationUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xaaa20` | `0xad4ec` | **`+0x2acc`** |
| `__TEXT.__eh_frame` | `0x4a78` | `0x4b98` | **`+0x120`** |
| `__TEXT.__oslogstring` | `0x2953` | `0x2a73` | **`+0x120`** |
| `__TEXT.__unwind_info` | `0x2680` | `0x2700` | **`+0x80`** |
| `__TEXT.__cstring` | `0x2054` | `0x20b4` | **`+0x60`** |
| `__TEXT.__const` | `0x72e4` | `0x7334` | **`+0x50`** |
| `__AUTH.__data` | `0x2f28` | `0x2f68` | **`+0x40`** |
| `__TEXT.__constg_swiftt` | `0x2830` | `0x2860` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1c24` | `0x1c54` | **`+0x30`** |
| `__TEXT.__swift5_typeref` | `0x8de4` | `0x8e06` | **`+0x22`** |
| `__AUTH_CONST.__objc_const` | `0x4f88` | `0x4fa8` | **`+0x20`** |
| `__DATA.__data` | `0x24d0` | `0x24f0` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x16d8` | `0x16f0` | **`+0x18`** |
| `__DATA.__bss` | `0x6868` | `0x6878` | **`+0x10`** |
| `__DATA_CONST.__const` | `0x1c0` | `0x1d0` | **`+0x10`** |
| `__TEXT.__swift5_capture` | `0x1330` | `0x1340` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0x1a14` | `0x1a20` | **`+0xc`** |
| `__DATA_CONST.__got` | `0xb48` | `0xb50` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0xb78` | `0xb80` | **`+0x8`** |

### Other Changes

```diff

-301.24.1.3.0
+301.24.1.4.0

-  Functions: 3090
-  Symbols:   1631
-  CStrings:  414
+  Functions: 3112
+  Symbols:   1636
+  CStrings:  419
Symbols:
+ _CFPreferencesCopyValue
+ _CFPreferencesSetValue
+ _CFPreferencesSynchronize
+ ___swift_closure_destructor.301Tm
+ ___swift_closure_destructor.325Tm
+ _kCFPreferencesAnyUser
+ _kCFPreferencesCurrentHost
+ _symbolic _____yShySSGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yShySSG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
- _OBJC_CLASS_$_NSUserDefaults
- ___swift_closure_destructor.298Tm
- ___swift_closure_destructor.322Tm
- ___swift_closure_destructor.428Tm
CStrings:
+ "%s Client filter bypass is set. Force rendering %ld dropped client donated recommendations: %s"
+ "%s No server rule for forced client card %s. Completing it on device with the donor supplied copy."
+ "CLIENT_DONATED_DEBUG"
+ "Client Donated (Internal)"
+ "Could not fetch client donated recommendations from the plugin loader %@"
+ "assembleRecommendationSection(shouldSendDisplayedStatus:shouldRefreshBreakout:droppedClientRecommendations:)"
- "assembleRecommendationSection(shouldSendDisplayedStatus:shouldRefreshBreakout:)"
```
