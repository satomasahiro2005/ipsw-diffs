## ManagedAppsCore

> `/System/Library/PrivateFrameworks/ManagedAppsCore.framework/ManagedAppsCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x80e8c` | `0x8195c` | **`+0xad0`** |
| `__TEXT.__oslogstring` | `0x17e2` | `0x1852` | **`+0x70`** |
| `__AUTH_CONST.__const` | `0x1cb8` | `0x1d08` | **`+0x50`** |
| `__TEXT.__eh_frame` | `0x4b44` | `0x4b6c` | **`+0x28`** |
| `__TEXT.__swift5_capture` | `0x650` | `0x670` | **`+0x20`** |
| `__DATA_CONST.__got` | `0x488` | `0x470` | **`-0x18`** |
| `__TEXT.__unwind_info` | `0x1988` | `0x1980` | **`-0x8`** |

### Other Changes

```diff

-111.0.0.0.0
+113.0.2.0.0

-  Functions: 2105
-  Symbols:   713
-  CStrings:  245
+  Functions: 2106
+  Symbols:   714
+  CStrings:  247
Symbols:
+ ___swift_closure_destructor.169Tm
+ ___swift_closure_destructor.177Tm
+ ___swift_closure_destructor.190Tm
+ ___swift_closure_destructor.66Tm
- ___swift_closure_destructor.178Tm
- ___swift_closure_destructor.191Tm
- ___swift_closure_destructor.67Tm
CStrings:
+ "%{public}s - Failed to resolve assets: %{public}s"
+ "%{public}s - recordID: %{public}s"
```
