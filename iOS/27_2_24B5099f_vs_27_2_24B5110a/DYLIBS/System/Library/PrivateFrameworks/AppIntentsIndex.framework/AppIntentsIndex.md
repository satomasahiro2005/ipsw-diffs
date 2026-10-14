## AppIntentsIndex

> `/System/Library/PrivateFrameworks/AppIntentsIndex.framework/AppIntentsIndex`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xec31c` | `0xec9b8` | **`+0x69c`** |
| `__TEXT.__eh_frame` | `0x9d2c` | `0x9d84` | **`+0x58`** |
| `__TEXT.__oslogstring` | `0x1d46` | `0x1d96` | **`+0x50`** |
| `__TEXT.__cstring` | `0x25fd` | `0x261d` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x36f8` | `0x3718` | **`+0x20`** |
| `__DATA.__data` | `0x1050` | `0x1060` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x948` | `0x958` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x660` | `0x670` | **`+0x10`** |
| `__DATA_DIRTY.__data` | `0x2ae8` | `0x2af8` | **`+0x10`** |
| `__TEXT.__const` | `0x995c` | `0x996c` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0x1760` | `0x1768` | **`+0x8`** |

### Other Changes

```diff

-301.1.15.0.0
+301.1.16.0.0

-  Functions: 4995
-  Symbols:   1638
-  CStrings:  384
+  Functions: 5001
+  Symbols:   1640
+  CStrings:  385
Symbols:
+ _NSCocoaErrorDomain
+ _NSDebugDescriptionErrorKey
CStrings:
+ "Domain is tearing down"
+ "[%{public}s] Completed AppShortcut interpolation, marking as processed"
+ "[%{public}s] Received indication that the system is restarting: %{public}@"
- "[%s] Completed AppShortcut interpolation, marking as processed"
- "[%s] Failed %@"
```
