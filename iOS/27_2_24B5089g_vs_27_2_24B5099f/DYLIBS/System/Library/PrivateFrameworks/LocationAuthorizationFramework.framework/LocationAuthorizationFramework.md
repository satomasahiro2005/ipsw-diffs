## LocationAuthorizationFramework

> `/System/Library/PrivateFrameworks/LocationAuthorizationFramework.framework/LocationAuthorizationFramework`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x67c44` | `0x68240` | **`+0x5fc`** |
| `__TEXT.__oslogstring` | `0x7432` | `0x76fa` | **`+0x2c8`** |
| `__TEXT.__eh_frame` | `0x16dc` | `0x1708` | **`+0x2c`** |
| `__TEXT.__objc_methlist` | `0x1358` | `0x1380` | **`+0x28`** |
| `__AUTH_CONST.__const` | `0x1968` | `0x1988` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x1678` | `0x1698` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0xef8` | `0xf10` | **`+0x18`** |
| `__DATA_DIRTY.__bss` | `0x800` | `0x810` | **`+0x10`** |

### Other Changes

```diff

-3186.0.17.0.1
+3186.0.21.0.0

-  Functions: 1926
+  Functions: 1931

-  CStrings:  589
+  CStrings:  595
CStrings:
+ "#AuthorizationDatabase - denying unquarantining for known invalid identity"
+ "#Warning #ClientResolution the passed keyPath is quarantined. Resolving to #nullCKP"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase #Quarantine marking client quarantined at migration\", \"client\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase -  unquarantining client\", \"client\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#AuthorizationDatabase - denying unquarantining for known invalid identity\", \"invalidIdentity\":%{public, location:escape_only}@}"
+ "{\"msg%{public}.0s\":\"#Warning #ClientResolution the passed keyPath is quarantined. Resolving to #nullCKP\", \"InputCKP\":%{public, location:escape_only}@}"
```
