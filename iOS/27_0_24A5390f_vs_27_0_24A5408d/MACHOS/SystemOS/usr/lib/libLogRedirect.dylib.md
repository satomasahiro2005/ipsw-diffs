## libLogRedirect.dylib

> `/usr/lib/libLogRedirect.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__cstring` | `0x4b9` | `0x4ed` | **`+0x34`** |
| `__TEXT.__text` | `0x24b0` | `0x24cc` | **`+0x1c`** |

### Same-size Content Changes

- `__AUTH_CONST.__interpose`
- `__DATA_CONST.__const`
- `__TEXT.__const`
- `__TEXT.__init_offsets`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-64578.53.2.0.0
+64578.57.1.0.0

-  CStrings:  65
+  CStrings:  66
Functions:
~ _LogPredicate_Evaluate : 640 -> 668
CStrings:
+ "/System/Library/Frameworks/CoreFoundation.framework"
```
