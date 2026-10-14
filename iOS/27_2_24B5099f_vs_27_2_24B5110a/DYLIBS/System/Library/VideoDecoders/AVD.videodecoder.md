## AVD.videodecoder

> `/System/Library/VideoDecoders/AVD.videodecoder`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x18f7d0` | `0x18f7e0` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x8b8` | `0x8c0` | **`+0x8`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-994.0.0.0.0
+995.0.0.0.0

-  Symbols:   3657
+  Symbols:   3658
Symbols:
+ _arc4random_buf
Functions:
~ _AppleAVDOpenConnection : 1256 -> 1268
~ _attachHistogramToIOSurface : 308 -> 312
CStrings:
+ "01:19:33"
+ "01:19:34"
+ "01:19:35"
+ "Oct 10 2026"
- "20:43:53"
- "20:43:54"
- "20:43:55"
- "Sep 27 2026"
```
