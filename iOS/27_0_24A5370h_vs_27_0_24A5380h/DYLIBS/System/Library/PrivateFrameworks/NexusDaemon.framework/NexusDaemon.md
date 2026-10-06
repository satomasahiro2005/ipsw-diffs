## NexusDaemon

> `/System/Library/PrivateFrameworks/NexusDaemon.framework/NexusDaemon`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x72768` | `0x73c30` | **`+0x14c8`** |
| `__TEXT.__oslogstring` | `0x2851` | `0x2930` | **`+0xdf`** |
| `__TEXT.__eh_frame` | `0xe90` | `0xf00` | **`+0x70`** |
| `__TEXT.__const` | `0xe28` | `0xe68` | **`+0x40`** |
| `__TEXT.__cstring` | `0x137a` | `0x13aa` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x1a88` | `0x1aa8` | **`+0x20`** |
| `__TEXT.__swift5_typeref` | `0x1070` | `0x1055` | **`-0x1b`** |
| `__DATA.__data` | `0xc38` | `0xc50` | **`+0x18`** |
| `__AUTH_CONST.__auth_got` | `0xdc0` | `0xdd0` | **`+0x10`** |
| `__DATA.__common` | `0x178` | `0x168` | **`-0x10`** |
| `__TEXT.__swift5_reflstr` | `0xf31` | `0xf41` | **`+0x10`** |
| `__TEXT.__swift5_fieldmd` | `0xb2c` | `0xb38` | **`+0xc`** |
| `__AUTH.__data` | `0xb98` | `0xba0` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0xb60` | `0xb58` | **`-0x8`** |

### Other Changes

```diff

-900.37.0.0.0
+900.48.0.0.0

-  Functions: 1058
-  Symbols:   595
-  CStrings:  340
+  Functions: 1056
+  Symbols:   594
+  CStrings:  344
Symbols:
+ ___swift_closure_destructor.15Tm
+ ___swift_closure_destructor.7Tm
+ _swift_unknownObjectWeakAssign
- ___swift_closure_destructor.13Tm
- ___swift_closure_destructor.41Tm
- ___swift_closure_destructor.9Tm
- _symbolic _____3key______5valuetSg 10Foundation4UUIDV 11NexusDaemon08NXServerD0C
CStrings:
+ "### Report operation start failed: name=%s, uuid=%s, no XPC connection"
+ "### Report operation update failed: uuid=%s, no XPC connection"
+ "Add subscriber: id=%s, ids=%s, needsNetwork=%{bool}d, operations=%s, request=%s"
+ "No XPC connection"
+ "ServerStart: mode=%s, needsNetwork=%{bool}d, requests=[%s], operations=[%s], client=%s"
+ "needsNetwork"
- "Add subscriber: id=%s, ids=%s, operations=%s, request=%s"
- "ServerStart: mode=%s, requests=[%s], operations=[%s], client=%s"
```
