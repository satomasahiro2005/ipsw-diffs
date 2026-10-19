## LinkPresentation

> `/System/Library/Frameworks/LinkPresentation.framework/LinkPresentation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x10eb04` | `0x10ebb4` | **`+0xb0`** |
| `__TEXT.__oslogstring` | `0x3b8b` | `0x3bdb` | **`+0x50`** |
| `__AUTH_CONST.__objc_const` | `0x2de00` | `0x2de20` | **`+0x20`** |
| `__AUTH_CONST.__auth_got` | `0x10e8` | `0x10d8` | **`-0x10`** |
| `__DATA_CONST.__got` | `0xf10` | `0xf18` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x1804` | `0x1808` | **`+0x4`** |

### Same-size Content Changes

- `__TEXT.__cstring`

### Other Changes

```diff

-  Symbols:   11731
-  CStrings:  2317
+  Symbols:   11730
+  CStrings:  2318
Symbols:
+ _OBJC_IVAR_$_LPAnimatedImageTranscoder._bufferSize
- _CVPixelBufferGetHeight
- _CVPixelBufferGetWidth
Functions:
~ -[LPAnimatedImageTranscoder encodeNextFrame] : 780 -> 956
CStrings:
+ "LPAnimatedImageTranscoder<%d>: failed, frame %zu is %gx%g, but the first frame is %gx%g"
```
