## MCCFoundation

> `/System/Library/PrivateFrameworks/MCCFoundation.framework/MCCFoundation`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x1fa44` | `0x1fcf4` | **`+0x2b0`** |
| `__TEXT.__oslogstring` | `0x378` | `0x418` | **`+0xa0`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a0` | `0x2d8` | **`+0x38`** |

### Other Changes

```diff

-2027.1.1.0.0
+2027.1.2.0.0

-  Functions: 769
-  Symbols:   2613
-  CStrings:  69
+  Functions: 770
+  Symbols:   2616
+  CStrings:  70
Symbols:
+ _$s13MCCFoundation20MCCNetworkControllerV18makeDefaultSessionSo12NSURLSessionCyFZ
+ _OBJC_CLASS_$_NSURLSession
+ _OBJC_CLASS_$_NSURLSessionConfiguration
CStrings:
+ "MCCNetworkController was given a session with a disk-backed URLCache attached; authenticated requests must not be cached. Falling back to a safe session."
```
