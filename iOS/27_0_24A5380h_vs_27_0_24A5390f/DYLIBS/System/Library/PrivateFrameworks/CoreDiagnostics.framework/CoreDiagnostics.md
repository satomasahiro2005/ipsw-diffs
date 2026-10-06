## CoreDiagnostics

> `/System/Library/PrivateFrameworks/CoreDiagnostics.framework/CoreDiagnostics`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72604` | `0x72720` | **`+0x11c`** |
| `__AUTH_CONST.__cfstring` | `0x55e0` | `0x5620` | **`+0x40`** |
| `__TEXT.__cstring` | `0x68aa` | `0x68da` | **`+0x30`** |
| `__AUTH_CONST.__auth_got` | `0x1148` | `0x1140` | **`-0x8`** |

### Other Changes

```diff

-80.0.0.0.0
+81.0.0.0.0

-  Symbols:   1446
-  CStrings:  1083
+  Symbols:   1445
+  CStrings:  1085
Symbols:
- _objc_retain_x27
Functions:
~ +[ReportViewerObjC transformURL:template:options:] : 2396 -> 2680
CStrings:
+ "Unable to read log stream: %@"
+ "unknown error"
```
