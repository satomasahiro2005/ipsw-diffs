## CoreAIDelegates

> `/System/Library/SubFrameworks/CoreAIDelegates.framework/CoreAIDelegates`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x393cc` | `0x3b300` | **`+0x1f34`** |
| `__TEXT.__cstring` | `0x176d` | `0x18fd` | **`+0x190`** |
| `__TEXT.__eh_frame` | `0x18f0` | `0x19d0` | **`+0xe0`** |
| `__AUTH.__objc_data` | `0xa0` | `0xf0` | **`+0x50`** |
| `__TEXT.__const` | `0x1de4` | `0x1e24` | **`+0x40`** |
| `__AUTH_CONST.__const` | `0x26c8` | `0x26f0` | **`+0x28`** |
| `__DATA.__data` | `0x718` | `0x740` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xab8` | `0xae0` | **`+0x28`** |
| `__DATA.__common` | `0xb8` | `0xd8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x660` | `0x67c` | **`+0x1c`** |
| `__AUTH.__data` | `0x448` | `0x460` | **`+0x18`** |
| `__TEXT.__swift5_fieldmd` | `0x848` | `0x860` | **`+0x18`** |
| `__TEXT.__constg_swiftt` | `0x534` | `0x548` | **`+0x14`** |
| `__AUTH_CONST.__auth_got` | `0xce0` | `0xce8` | **`+0x8`** |
| `__AUTH_CONST.__objc_const` | `0x238` | `0x230` | **`-0x8`** |

### Same-size Content Changes

- `__TEXT.__swift5_reflstr`

### Other Changes

```diff

-3600.83.2.11.1
+3605.5.4.0.0

-  Functions: 862
+  Functions: 870

-  CStrings:  168
+  CStrings:  173
Symbols:
+ _objc_retain_x24
+ _swift_retain_x25
- _swift_retain_x26
- _swift_unexpectedError
CStrings:
+ "Could not settle policy discrepancy, unable to resolve non-purgeable cache destination"
+ "Could not settle policy discrepancy, unable to resolve non-purgeable cached asset"
+ "Failed to create cache directory "
+ "Failed to resolve cache directory"
+ "Failed to resolve cache directory, asked for non-purgeable cache but directory was nil"
+ "Incurred error creating AIModelCache with default directories: "
- "Failed to create cache directory"
```
