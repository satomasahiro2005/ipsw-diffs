## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/PlatformSSOCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x974e0` | `0x976dc` | **`+0x1fc`** |
| `__TEXT.__const` | `0x1954` | `0x19ac` | **`+0x58`** |
| `__AUTH_CONST.__objc_const` | `0x14c98` | `0x14cc8` | **`+0x30`** |
| `__DATA.__data` | `0x1200` | `0x1228` | **`+0x28`** |
| `__TEXT.__cstring` | `0xad0a` | `0xad28` | **`+0x1e`** |
| `__TEXT.__objc_methlist` | `0x6260` | `0x6278` | **`+0x18`** |
| `__DATA_CONST.__objc_selrefs` | `0x2cd8` | `0x2ce8` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x2168` | `0x2170` | **`+0x8`** |
| `__DATA.__objc_ivar` | `0x648` | `0x64c` | **`+0x4`** |

### Other Changes

```diff

-643.0.21.0.0
+643.0.33.0.0

-  Functions: 3838
-  Symbols:   5811
-  CStrings:  1758
+  Functions: 3843
+  Symbols:   5826
+  CStrings:  1759
Symbols:
+ -[PODeviceConfiguration extensionTeamIdentifier]
+ -[PODeviceConfiguration setExtensionTeamIdentifier:]
+ _OBJC_IVAR_$_PODeviceConfiguration._extensionTeamIdentifier
+ ___der_key_last_mesa_auth
+ ___der_key_last_mesa_unlock
+ ___der_key_last_passcode_auth
+ ___der_key_last_passcode_unlock
+ ___der_key_sks_heap_stats
+ _aks_get_convenience_bio_state
+ _aks_get_sks_heap_stats
+ _der_key_last_mesa_auth
+ _der_key_last_mesa_unlock
+ _der_key_last_passcode_auth
+ _der_key_last_passcode_unlock
+ _der_key_sks_heap_stats
CStrings:
+ "aks_get_convenience_bio_state"
```
