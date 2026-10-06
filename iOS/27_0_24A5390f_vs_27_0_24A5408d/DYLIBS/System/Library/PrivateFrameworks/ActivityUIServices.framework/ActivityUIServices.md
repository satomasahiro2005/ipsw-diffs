## ActivityUIServices

> `/System/Library/PrivateFrameworks/ActivityUIServices.framework/ActivityUIServices`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x65470` | `0x65aa0` | **`+0x630`** |
| `__TEXT.__oslogstring` | `0x1bb8` | `0x1cf8` | **`+0x140`** |
| `__AUTH.__objc_data` | `0x6670` | `0x66f0` | **`+0x80`** |
| `__TEXT.__objc_methlist` | `0x3118` | `0x3130` | **`+0x18`** |
| `__TEXT.__swift5_typeref` | `0x18ab` | `0x18c3` | **`+0x18`** |
| `__DATA.__data` | `0x1a88` | `0x1a98` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x1548` | `0x1558` | **`+0x10`** |
| `__TEXT.__const` | `0x4610` | `0x4620` | **`+0x10`** |
| `__TEXT.__constg_swiftt` | `0x2818` | `0x2828` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1f28` | `0x1f30` | **`+0x8`** |

### Other Changes

```diff

-311.0.0.0.0
+312.0.0.0.0

-  Functions: 3512
-  Symbols:   1992
-  CStrings:  268
+  Functions: 3517
+  Symbols:   1995
+  CStrings:  270
Symbols:
+ -[ACUISActivityHostViewController invalidateMetrics]
+ ___swift_closure_destructor.242Tm
+ _symbolic So8UIWindowCSg
+ _symbolic _____Sg So6CGSizeV
- ___swift_closure_destructor.245Tm
CStrings:
+ "[%{public}s] Reseting content size (resolvedMetrics=%{public}s)"
+ "[%{public}s] Updating metrics request (sending to renderer): lockScreen=%{public}s"
+ "[%{public}s] invalidateMetrics — re-querying metrics provider + resetting content size (window: %{public}s)"
+ "[%{public}s] resetContentSize resolved final requestedFrameSize=%{public}s (resolvedMetrics.size=%{public}s, current preferred=%{public}s)"
- "[%{public}s] Reseting content size"
- "[%{public}s] Updating metrics request"
```
