## IOMobileFramebuffer

> `/System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3b744` | `0x3b768` | **`+0x24`** |
| `__TEXT.__cstring` | `0x9786` | `0x9793` | **`+0xd`** |

### Other Changes

```diff

-700.50.104.1.0
+700.50.108.0.0
Functions:
~ __ZN22DisplayDataBlockParser16set_ptuc_rr_lutsEv : 240 -> 276
CStrings:
+ "Parser e: failed to set PTUC TLS RR LUT dbv_nits=%d, attempt %u/%u\n"
- "Parser e: failed to set PTUC TLS RR LUT brightness %d\n"
```
