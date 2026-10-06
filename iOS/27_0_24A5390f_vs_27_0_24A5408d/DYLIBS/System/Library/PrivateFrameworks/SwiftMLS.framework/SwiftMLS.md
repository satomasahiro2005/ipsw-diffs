## SwiftMLS

> `/System/Library/PrivateFrameworks/SwiftMLS.framework/SwiftMLS`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2b6b88` | `0x2b7074` | **`+0x4ec`** |
| `__TEXT.__oslogstring` | `0x6788` | `0x67ff` | **`+0x77`** |
| `__TEXT.__swift_as_cont` | `0x1614` | `0x161c` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xa638` | `0xa640` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x630` | `0x634` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0xc38` | `0xc3c` | **`+0x4`** |

### Other Changes

```diff

-341.0.16.0.0
+341.0.17.0.0

-  Functions: 10687
+  Functions: 10690

-  CStrings:  837
+  CStrings:  838
CStrings:
+ "%s: all committed group metadata keys are present, no request needed"
+ "%s: failed to verify subject key against commitment, will request group metadata keys { error: %@ }"
+ "%s: missing continuity token, will request group metadata keys"
+ "%s: missing icon key, will request group metadata keys"
+ "%s: subject key missing or does not match commitment, will request group metadata keys"
- "%s: new era: all committed group metadata keys are present, no request needed"
- "%s: new era: missing continuity token, will request group metadata keys"
- "%s: new era: missing icon key, will request group metadata keys"
- "%s: new era: missing subject key, will request group metadata keys"
```
