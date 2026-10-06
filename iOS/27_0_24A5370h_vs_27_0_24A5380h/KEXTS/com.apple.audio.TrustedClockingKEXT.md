## com.apple.audio.TrustedClockingKEXT

> `com.apple.audio.TrustedClockingKEXT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x31ae` | `0x3203` | **`+0x55`** |
| `__TEXT_EXEC.__text` | `0xc2f4` | `0xc30c` | **`+0x18`** |
| `__DATA_CONST.__const` | `0x18d0` | `0x18e0` | **`+0x10`** |

### Other Changes

```diff

-92.30.0.0.0
-  Functions: 446
+93.1.0.0.0
+  Functions: 447

-  CStrings:  139
+  CStrings:  140
CStrings:
+ "TrustedClockingWorkloopContext::init - Invalid kernel primitive for use case ID: %u\n"
```
