## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/SpotlightUIShared`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__eh_frame` | `0x8dfc` | `0x8c9c` | **`-0x160`** |
| `__TEXT.__text` | `0xe1d48` | `0xe1cd0` | **`-0x78`** |
| `__TEXT.__unwind_info` | `0x4200` | `0x41c8` | **`-0x38`** |
| `__AUTH_CONST.__objc_const` | `0x3af8` | `0x3ac8` | **`-0x30`** |
| `__TEXT.__const` | `0xa28c` | `0xa25c` | **`-0x30`** |
| `__TEXT.__swift5_reflstr` | `0x1c78` | `0x1ca8` | **`+0x30`** |
| `__TEXT.__oslogstring` | `0x1372` | `0x1352` | **`-0x20`** |
| `__TEXT.__objc_methlist` | `0xf18` | `0xf08` | **`-0x10`** |
| `__AUTH_CONST.__const` | `0x6e39` | `0x6e31` | **`-0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1610` | `0x1608` | **`-0x8`** |
| `__TEXT.__swift5_mpenum` | `0x38` | `0x34` | **`-0x4`** |

### Other Changes

```diff

-236.0.21.100.0
+236.0.21.104.0

-  Functions: 5199
+  Functions: 5206
Symbols:
+ ___swift_memcpy20_8
- ___swift_memcpy21_8
CStrings:
+ "[%s] response(qid:%llu len:%ld tier:%ld elev:%{bool}d priority:%{bool}d done:%{bool}d) → [%s]"
- "[%s] response(qid:%llu len:%ld siri:%{bool}d elev:%{bool}d results:%{bool}d done:%{bool}d priority:%{bool}d) → [%s]"
```
