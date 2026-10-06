## AccessibilityReaderData

> `/System/Library/PrivateFrameworks/AccessibilityReaderData.framework/AccessibilityReaderData`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1800dc` | `0x1806f0` | **`+0x614`** |
| `__TEXT.__oslogstring` | `0x426f` | `0x430f` | **`+0xa0`** |
| `__TEXT.__eh_frame` | `0x63dc` | `0x645c` | **`+0x80`** |
| `__TEXT.__unwind_info` | `0x4330` | `0x4358` | **`+0x28`** |

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Functions: 6828
+  Functions: 6834

-  CStrings:  592
+  CStrings:  594
CStrings:
+ "ContentCleanup: cancelContentCleaning — inFlight=%{bool}d cleanedPages=%ld"
+ "ContentCleanup: page[%ld] cleanup cancelled — discarding error %@"
```
