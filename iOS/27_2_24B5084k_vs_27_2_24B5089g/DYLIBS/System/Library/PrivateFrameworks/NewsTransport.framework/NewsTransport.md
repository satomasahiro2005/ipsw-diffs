## NewsTransport

> `/System/Library/PrivateFrameworks/NewsTransport.framework/NewsTransport`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2aff90` | `0x2b0104` | **`+0x174`** |
| `__DATA.__data` | `0x60` | `—` | **`-0x60`** |
| `__DATA_DIRTY.__data` | `—` | `0x60` | **`+0x60`** |
| `__AUTH_CONST.__objc_const` | `0x4e358` | `0x4e398` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x37dac` | `0x37dd4` | **`+0x28`** |
| `__AUTH_CONST.__cfstring` | `0x161c0` | `0x161e0` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x116b8` | `0x116d0` | **`+0x18`** |
| `__TEXT.__cstring` | `0x1202a` | `0x12038` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0x4098` | `0x409c` | **`+0x4`** |

### Other Changes

```diff

-5960.0.0.0.0
+5962.0.0.0.0

-  Functions: 19077
-  Symbols:   26342
-  CStrings:  2846
+  Functions: 19080
+  Symbols:   26346
+  CStrings:  2847
Symbols:
+ -[NTPBReadingHistoryItem dislikedDate]
+ -[NTPBReadingHistoryItem hasDislikedDate]
+ -[NTPBReadingHistoryItem setDislikedDate:]
+ OBJC_IVAR_$_NTPBReadingHistoryItem._dislikedDate
CStrings:
+ "disliked_date"
```
