## RemoteTextInput

> `/System/Library/PrivateFrameworks/RemoteTextInput.framework/RemoteTextInput`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__AUTH.__objc_data` | `0x50` | `0x3c0` | **`+0x370`** |
| `__DATA_DIRTY.__objc_data` | `0xa00` | `0x690` | **`-0x370`** |
| `__TEXT.__text` | `0x20da8` | `0x20f4c` | **`+0x1a4`** |
| `__AUTH_CONST.__cfstring` | `0x2de0` | `0x2e20` | **`+0x40`** |
| `__TEXT.__cstring` | `0x2ff5` | `0x3028` | **`+0x33`** |
| `__AUTH_CONST.__objc_const` | `0x6938` | `0x6968` | **`+0x30`** |
| `__TEXT.__objc_methlist` | `0x2bac` | `0x2bc4` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x1978` | `0x1988` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x940` | `0x948` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x32c` | `0x330` | **`+0x4`** |

### Other Changes

```diff

-178.0.0.0.0
+179.0.0.0.0

-  Functions: 1021
-  Symbols:   1845
-  CStrings:  523
+  Functions: 1023
+  Symbols:   1848
+  CStrings:  525
Symbols:
+ -[RTIDocumentState setUnobscuredContentRect:]
+ -[RTIDocumentState unobscuredContentRect]
+ _OBJC_IVAR_$_RTIDocumentState._unobscuredContentRect
CStrings:
+ "; unobscuredContentRect = %@"
+ "unobscuredContentRect"
```
