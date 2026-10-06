## SecureTransactionService

> `/System/Library/PrivateFrameworks/SecureTransactionService.framework/SecureTransactionService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x348f8` | `0x351dc` | **`+0x8e4`** |
| `__TEXT.__oslogstring` | `0x5ac` | `0x66e` | **`+0xc2`** |
| `__AUTH.__objc_data` | `0x1360` | `0x1310` | **`-0x50`** |
| `__DATA_DIRTY.__objc_data` | `—` | `0x50` | **`+0x50`** |
| `__DATA_CONST.__const` | `0xb30` | `0xb58` | **`+0x28`** |
| `__DATA_CONST.__got` | `0x248` | `0x258` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0xbc8` | `0xbb8` | **`-0x10`** |
| `__AUTH_CONST.__auth_got` | `0x4a0` | `0x4a8` | **`+0x8`** |
| `__DATA_CONST.__objc_selrefs` | `0x1698` | `0x16a0` | **`+0x8`** |

### Other Changes

```diff

-6.0.10.0.0
+6.0.11.0.0

-  Symbols:   302
-  CStrings:  776
+  Symbols:   303
+  CStrings:  784
Symbols:
+ _os_signpost_id_generate
CStrings:
+ "STSResultFeatureNotSupported"
+ "error"
+ "handler activation failure"
+ "handler does not exist"
+ "handler invalid"
+ "releaseCredential:withAuthorization:"
+ "startTransactionWithAuthorization:"
+ "weakSelf released"
```
