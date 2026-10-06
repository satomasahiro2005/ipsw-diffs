## HearingTest

> `/System/Library/PrivateFrameworks/HearingTest.framework/HearingTest`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc388` | `0xdcaa0` | **`+0x718`** |
| `__TEXT.__oslogstring` | `0x8951` | `0x8a11` | **`+0xc0`** |
| `__AUTH_CONST.__const` | `0xcf94` | `0xd034` | **`+0xa0`** |
| `__TEXT.__swift5_capture` | `0x29cc` | `0x2a1c` | **`+0x50`** |
| `__TEXT.__const` | `0x5200` | `0x5210` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1d68` | `0x1d60` | **`-0x8`** |

### Other Changes

```diff

-400.39.0.0.0
+400.40.0.0.0

-  Functions: 3876
+  Functions: 3880

-  CStrings:  814
+  CStrings:  816
Symbols:
+ ___swift_closure_destructor.309Tm
- ___swift_closure_destructor.303Tm
CStrings:
+ "[%{public}s] setupConnectedDiscovery ignoring non-AACP device lost: %{private}s id: %{private}s"
+ "[%{public}s] setupConnectedDiscovery ignoring non-AACP device: %{private}s id: %{private}s"
```
