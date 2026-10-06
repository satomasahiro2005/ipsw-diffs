## NanoFaceGallery

> `/System/Library/PrivateFrameworks/NanoFaceGallery.framework/NanoFaceGallery`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xdc314` | `0xdebbc` | **`+0x28a8`** |
| `__TEXT.__eh_frame` | `0x7230` | `0x7458` | **`+0x228`** |
| `__TEXT.__oslogstring` | `0x18e3` | `0x1a13` | **`+0x130`** |
| `__TEXT.__const` | `0x9ef4` | `0x9fc4` | **`+0xd0`** |
| `__TEXT.__unwind_info` | `0x3548` | `0x35d0` | **`+0x88`** |
| `__AUTH_CONST.__objc_const` | `0x28f8` | `0x2958` | **`+0x60`** |
| `__AUTH_CONST.__const` | `0x6168` | `0x61b8` | **`+0x50`** |
| `__TEXT.__swift5_reflstr` | `0x184d` | `0x188d` | **`+0x40`** |
| `__TEXT.__swift5_fieldmd` | `0x25d0` | `0x260c` | **`+0x3c`** |
| `__TEXT.__swift5_capture` | `0xdd0` | `0xdf4` | **`+0x24`** |
| `__DATA.__bss` | `0xb150` | `0xb170` | **`+0x20`** |
| `__DATA.__data` | `0x29d0` | `0x29f0` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0x6c8` | `0x6e0` | **`+0x18`** |
| `__AUTH.__data` | `0x14d0` | `0x14e0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1950` | `0x1960` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x6c8` | `0x6d8` | **`+0x10`** |
| `__TEXT.__swift_as_cont` | `0x520` | `0x530` | **`+0x10`** |
| `__DATA_CONST.__got` | `0xab0` | `0xab8` | **`+0x8`** |
| `__TEXT.__swift5_typeref` | `0x9c96` | `0x9c9e` | **`+0x8`** |
| `__TEXT.__swift_as_entry` | `0x244` | `0x248` | **`+0x4`** |
| `__TEXT.__swift_as_ret` | `0x20c` | `0x210` | **`+0x4`** |

### Other Changes

```diff

-2483.512.0.0.0
+2483.523.0.4.0

-  Functions: 4143
-  Symbols:   1888
-  CStrings:  328
+  Functions: 4177
+  Symbols:   1889
+  CStrings:  333
Symbols:
+ ___swift_closure_destructor.31Tm
+ _symbolic B1
+ _symbolic _____Sg 15NanoFaceGallery07CuratedC0V
+ _symbolic _____Sg 15NanoFaceGallery16FallbackSnapshotV6SourceO
+ _symbolic _____XDXMT 15NanoFaceGallery0C7ManagerC
- ___swift_closure_destructor.14Tm
- _symbolic G0R1_
- _symbolic G1R1_
- _symbolic _____yxq_G 15NanoFaceGallery24ReplicatedSnapshotWriterC
CStrings:
+ "Sending gallery refresh message failed %@"
+ "Sending gallery refresh message on active device change…"
+ "Using FALLBACK (local) snapshot for %s — replicated snapshot unavailable…"
+ "Using PRIMARY (replicated) snapshot for %s…"
+ "image backing file for %s at %s (exists=%{bool}d)…"
```
