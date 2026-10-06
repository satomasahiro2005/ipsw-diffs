## GameController

> `/System/Library/Frameworks/GameController.framework/GameController`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf8acc` | `0xf8bfc` | **`+0x130`** |
| `__TEXT.__oslogstring` | `0x8248` | `0x8318` | **`+0xd0`** |
| `__TEXT.__gcc_except_tab` | `0x3630` | `0x3680` | **`+0x50`** |
| `__AUTH_CONST.__cfstring` | `0xad00` | `0xad40` | **`+0x40`** |
| `__TEXT.__cstring` | `0x9af1` | `0x9b31` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0xf234` | `0xf24c` | **`+0x18`** |
| `__TEXT.__const` | `0x22ec` | `0x22fc` | **`+0x10`** |
| `__AUTH_CONST.__auth_got` | `0xee0` | `0xee8` | **`+0x8`** |

### Other Changes

```diff

-14.0.14.0.0
+14.0.17.0.0

-  Functions: 7406
-  Symbols:   14231
-  CStrings:  2364
+  Functions: 7410
+  Symbols:   14234
+  CStrings:  2370
Symbols:
+ -[GCSpatialAccessory debugDescription]
+ -[GCSpatialAccessory description]
+ _swift_retain_x23
CStrings:
+ "<GCSpatialAccessory %p '%@'>"
+ "<GCSpatialAccessory %p '%@'> %@"
+ "Active system buttons: %@"
+ "[%@] #NOTE Dealloc called with active buttonHandle."
+ "[%@] Applying light color %@ (was %@) with active client %@, active application (pid %d)"
+ "[%@] Light change from client %@ (pid %d): %@"
```
