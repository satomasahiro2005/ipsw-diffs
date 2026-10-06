## CircleJoinRequested

> `/System/Library/Frameworks/Security.framework/CircleJoinRequested/CircleJoinRequested`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5318` | `0x53a4` | **`+0x8c`** |
| `__TEXT.__oslogstring` | `0xb0c` | `0xb4d` | **`+0x41`** |
| `__TEXT.__auth_stubs` | `0x5a0` | `0x5b0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2d8` | `0x2e0` | **`+0x8`** |
| `__TEXT.__const` | `0xb0` | `0xa8` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__TEXT.__cstring`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-62460.0.55.0.1
+62460.2.1.0.0

-  Symbols:   145
-  CStrings:  301
+  Symbols:   146
+  CStrings:  302
Symbols:
+ _SOSCCIsSOSTrustAndSyncingEnabledCachedValue
Functions:
~ sub_100002000 : 6448 -> 6588
CStrings:
+ "Enter your password in iCloud settings."
+ "SOS is currently not supported or enabled; exiting when possible"
- "Enter your password in iCloud Settings."
```
