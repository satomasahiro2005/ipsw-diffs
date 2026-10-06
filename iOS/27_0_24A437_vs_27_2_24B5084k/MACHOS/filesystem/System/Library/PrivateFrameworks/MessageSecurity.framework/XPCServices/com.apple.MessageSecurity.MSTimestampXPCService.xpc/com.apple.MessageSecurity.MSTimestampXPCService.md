## com.apple.MessageSecurity.MSTimestampXPCService

> `/System/Library/PrivateFrameworks/MessageSecurity.framework/XPCServices/com.apple.MessageSecurity.MSTimestampXPCService.xpc/com.apple.MessageSecurity.MSTimestampXPCService`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0x1e0` | `0x200` | **`+0x20`** |
| `__TEXT.__text` | `0x23bc` | `0x23dc` | **`+0x20`** |
| `__TEXT.__cstring` | `0x4c4` | `0x4e0` | **`+0x1c`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-341.0.17.0.0
+341.40.7.0.0

-  CStrings:  126
+  CStrings:  127
Functions:
~ sub_100000d28 : 532 -> 564
CStrings:
+ "https://quartz.cs.apple.com/tsa-platform-ecdsa-p256-sha256"
+ "https://quartz.cs.apple.com/tsa-platform-mldsa87-rsa3072-pss-sha512"
+ "https://quartz.cs.apple.com/tsa-platform-rsa2048-pkcs15-sha256"
+ "quartz.cs.apple.com"
- "https://quartz-test.cs.apple.com/api/v0/timestamp/tsa-mldsa87-rsa3072-pss-sha512"
- "https://quartz-test.cs.apple.com/api/v0/timestamp/tsa-rsa2048-pkcs15-sha256"
- "quartz-test.cs.apple.com"
```
