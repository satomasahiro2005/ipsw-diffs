## TrackingAvoidance

> `/System/Library/PrivateFrameworks/TrackingAvoidance.framework/TrackingAvoidance`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x4aa4c` | `0x4afb0` | **`+0x564`** |
| `__TEXT.__oslogstring` | `0x708e` | `0x731d` | **`+0x28f`** |
| `__AUTH_CONST.__cfstring` | `0x4a40` | `0x4a80` | **`+0x40`** |
| `__TEXT.__cstring` | `0x3011` | `0x304f` | **`+0x3e`** |
| `__TEXT.__objc_methlist` | `0x4b3c` | `0x4b74` | **`+0x38`** |
| `__AUTH_CONST.__auth_got` | `0x2f8` | `0x328` | **`+0x30`** |
| `__AUTH_CONST.__objc_const` | `0x9110` | `0x9138` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0xe0` | `0x100` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x2340` | `0x2360` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0xe80` | `0xe98` | **`+0x18`** |
| `__DATA.__bss` | `—` | `0x10` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x3c0` | `0x3d0` | **`+0x10`** |
| `__DATA.__objc_ivar` | `0x684` | `0x688` | **`+0x4`** |

### Other Changes

```diff

-107.0.22.0.0
+107.0.25.0.0

-  Functions: 1618
-  Symbols:   2869
-  CStrings:  949
+  Functions: 1624
+  Symbols:   2885
+  CStrings:  960
Symbols:
+ -[TADefaults dateForKey:defaultValue:]
+ -[TADefaultsAccessor initialize]
+ -[TADefaultsSystemUtils dataWithContentsOfURL:options:error:]
+ _CFBooleanGetTypeID
+ _CFBooleanGetValue
+ _CFGetTypeID
+ _CFPropertyListCreateWithData
+ _CFRelease
+ _MGCopyAnswer
+ _NSCocoaErrorDomain
+ _OBJC_IVAR_$_TADefaultsAccessor._profileSettings
+ _TAIsInternalInstall
+ _TAIsInternalInstall.onceToken
+ _TAIsInternalInstall.sIsInternalInstall
+ ___TAIsInternalInstall_block_invoke
+ _kCFAllocatorDefault
CStrings:
+ "//private/var/Managed Preferences/%@/%@.plist"
+ "I"
+ "InternalBuild"
+ "{\"msg%{public}.0s\":\"#ta #defaults failed to deserialize managed defaults from file\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults failed to read file\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults found no file containing managed defaults\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults initialization finished\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults initialization started\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults loaded managed defaults from file\", \"file\":\"%{public}s\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults must initialize accessor before reading\"}"
+ "{\"msg%{public}.0s\":\"#ta #defaults must only be initialized once\"}"
```
