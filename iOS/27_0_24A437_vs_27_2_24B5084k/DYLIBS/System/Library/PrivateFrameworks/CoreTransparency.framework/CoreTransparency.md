## CoreTransparency

> `/System/Library/PrivateFrameworks/CoreTransparency.framework/CoreTransparency`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4ebcc` | `0x4f7c4` | **`+0xbf8`** |
| `__TEXT.__cstring` | `0xede` | `0xfde` | **`+0x100`** |
| `__TEXT.__eh_frame` | `0x2434` | `0x23ec` | **`-0x48`** |
| `__TEXT.__const` | `0x7c04` | `0x7c34` | **`+0x30`** |
| `__TEXT.__swift5_reflstr` | `0x29c4` | `0x29e4` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1a3a` | `0x1a5a` | **`+0x20`** |
| `__TEXT.__swift5_builtin` | `0xdc` | `0xf0` | **`+0x14`** |
| `__TEXT.__swift5_fieldmd` | `0x1f28` | `0x1f34` | **`+0xc`** |
| `__AUTH_CONST.__auth_got` | `0x990` | `0x988` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x68` | `0x70` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1928` | `0x1920` | **`-0x8`** |

### Other Changes

```diff

-1766.0.60.0.0
+1766.40.47.0.0

-  Functions: 3052
+  Functions: 3051

-  CStrings:  105
+  CStrings:  109
Symbols:
+ _symbolic _____22remainingMergeWindowMs_t s6UInt64V
- _objc_release_x28
CStrings:
+ " remainingMergeWindowMs="
+ "verifyEvents: event postdates proof, not yet transparent eventId="
+ "verifyEvents: inside merge window, not yet transparent eventId="
+ "verifyEvents: merge window elapsed, event not transparent eventId="
```
