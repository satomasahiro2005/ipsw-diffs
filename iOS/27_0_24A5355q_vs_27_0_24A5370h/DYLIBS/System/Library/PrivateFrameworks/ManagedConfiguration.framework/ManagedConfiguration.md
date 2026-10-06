## ManagedConfiguration

> `/System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xf5794` | `0xf5478` | **`-0x31c`** |
| `__TEXT.__unwind_info` | `0x3218` | `0x3240` | **`+0x28`** |
| `__TEXT.__cstring` | `0x185a0` | `0x185c4` | **`+0x24`** |
| `__AUTH_CONST.__cfstring` | `0x194a0` | `0x194c0` | **`+0x20`** |
| `__DATA_CONST.__const` | `0x4db0` | `0x4db8` | **`+0x8`** |

### Other Changes

```diff

-2479.0.0.0.0
+2482.0.0.0.0

-  Functions: 5785
+  Functions: 5782

-  CStrings:  4589
+  CStrings:  4590
Symbols:
+ _MCFeatureSiriReduceSensitiveContentForced
- _OUTLINED_FUNCTION_101
CStrings:
+ "%s:%spid:%d,%s:%s%s%s%s%s%u:%s cccurve25519 failed: small-order point used%s\n"
+ "forceReduceSensitiveContent"
+ "generate_wrapping_key_curve25519"
- "ACMCredential - ACMCredentialDataPKITokenValidated"
- "ACMCredential - ACMCredentialDataPKITokenValidated2"
```
