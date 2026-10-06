## AppleMediaServicesUIKitInternal

> `/System/Library/PrivateFrameworks/AppleMediaServicesUIKitInternal.framework/AppleMediaServicesUIKitInternal`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe4b68` | `0xea340` | **`+0x57d8`** |
| `__TEXT.__swift5_typeref` | `0xd35e` | `0xf002` | **`+0x1ca4`** |
| `__TEXT.__const` | `0x9374` | `0x95f4` | **`+0x280`** |
| `__DATA.__data` | `0x1ef8` | `0x2118` | **`+0x220`** |
| `__TEXT.__eh_frame` | `0x4564` | `0x4744` | **`+0x1e0`** |
| `__AUTH_CONST.__const` | `0x44e8` | `0x46a0` | **`+0x1b8`** |
| `__TEXT.__oslogstring` | `0x1e24` | `0x1ca4` | **`-0x180`** |
| `__TEXT.__unwind_info` | `0x2968` | `0x2ac0` | **`+0x158`** |
| `__TEXT.__cstring` | `0x1d12` | `0x1e42` | **`+0x130`** |
| `__AUTH_CONST.__auth_got` | `0x1d58` | `0x1e40` | **`+0xe8`** |
| `__TEXT.__constg_swiftt` | `0x325c` | `0x3344` | **`+0xe8`** |
| `__TEXT.__swift5_capture` | `0xefc` | `0xfd4` | **`+0xd8`** |
| `__AUTH_CONST.__objc_const` | `0x12d0` | `0x13a0` | **`+0xd0`** |
| `__TEXT.__swift5_reflstr` | `0x1abb` | `0x1b6b` | **`+0xb0`** |
| `__AUTH.__data` | `0xf68` | `0x1000` | **`+0x98`** |
| `__TEXT.__swift5_fieldmd` | `0x1fe0` | `0x2078` | **`+0x98`** |
| `__DATA.__bss` | `0x40b0` | `0x4130` | **`+0x80`** |
| `__DATA_DIRTY.__data` | `0x2a60` | `0x2a10` | **`-0x50`** |
| `__TEXT.__swift_as_cont` | `0x348` | `0x384` | **`+0x3c`** |
| `__DATA_CONST.__got` | `0xd18` | `0xd50` | **`+0x38`** |
| `__DATA_CONST.__objc_selrefs` | `0x528` | `0x538` | **`+0x10`** |
| `__TEXT.__swift_as_entry` | `0x108` | `0x114` | **`+0xc`** |
| `__DATA_CONST.__objc_classlist` | `0x88` | `0x90` | **`+0x8`** |
| `__TEXT.__swift5_proto` | `0x2c0` | `0x2c4` | **`+0x4`** |
| `__TEXT.__swift5_types` | `0x224` | `0x228` | **`+0x4`** |

### Other Changes

```diff

-2.0.26.0.0
+2.0.29.0.0

+  - /System/Library/Frameworks/Security.framework/Security

-  Functions: 3706
-  Symbols:   265
-  CStrings:  281
+  Functions: 3804
+  Symbols:   271
+  CStrings:  280
Symbols:
+ _AAUIProfilePictureStoreDidChangeNotification
+ _OBJC_CLASS_$_AAUIProfilePictureStore
+ _OBJC_CLASS_$_NSOperationQueue
+ _SecTaskCopyValueForEntitlement
+ _SecTaskCreateFromSelf
+ _objc_release_x9
+ _swift_initStaticObject
- _OBJC_CLASS_$_AMSAuthenticateTask
CStrings:
+ ", so don't fetch again"
+ "Account image not-found date "
+ "Active account fetched: "
+ "Contradictory frame constraints specified."
+ "Failed to create bag: "
+ "Record account image not-found date "
+ "com.apple.appleaccount.identity.read"
+ "error in account image fetch: "
- "Account image not-found date %s is within TTL %f, so don't fetch again"
- "Active account fetched: %s"
- "Failed to create bag: %@"
- "Monogram Text: %s"
- "Record account image not-found date %s"
- "Running silent AMSAuthenticateTask inline"
- "error in account fetch: %@"
- "error in account image fetch: %@"
- "handleAuthenticateRequest: %@"
```
