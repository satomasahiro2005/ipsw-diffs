## libMobileGestalt.dylib

> `/usr/lib/libMobileGestalt.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6b1c0` | `0x6b328` | **`+0x168`** |
| `__TEXT.__oslogstring` | `0x3fb0` | `0x4039` | **`+0x89`** |
| `__TEXT.__cstring` | `0x1778d` | `0x1780d` | **`+0x80`** |
| `__AUTH_CONST.__cfstring` | `0x13120` | `0x13160` | **`+0x40`** |

### Other Changes

```diff

-1622.0.4.0.0
+1622.0.5.0.0

-  Functions: 3605
+  Functions: 3608

-  CStrings:  3850
+  CStrings:  3852
CStrings:
+ "9CA001C7-B295-4C9F-B71A-8E1703492CEF"
+ "Screen canvas size is in incorrect format; bailing from orientation check"
+ "Screen canvas size was NULL; bailing from orientation check"
+ "copyAvailableDisplayZoomSizes: Changed landscape to portrait for (%d, %d)"
- "07622B10-6B5F-4A9D-848F-8D2A5DE1CF56"
- "copyAvailableDisplayZoomSizes: Changed landscape to portrait for %dx%d"
```
