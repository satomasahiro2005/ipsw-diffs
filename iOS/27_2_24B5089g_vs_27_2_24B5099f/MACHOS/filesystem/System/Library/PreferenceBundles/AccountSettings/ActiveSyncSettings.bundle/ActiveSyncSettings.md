## ActiveSyncSettings

> `/System/Library/PreferenceBundles/AccountSettings/ActiveSyncSettings.bundle/ActiveSyncSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__objc_stubs` | `0x5360` | `0x5300` | **`-0x60`** |
| `__TEXT.__objc_methname` | `0x5e69` | `0x5e0f` | **`-0x5a`** |
| `__TEXT.__cstring` | `0x135a` | `0x1305` | **`-0x55`** |
| `__DATA_CONST.__const` | `0x498` | `0x458` | **`-0x40`** |
| `__DATA.__objc_selrefs` | `0x19e0` | `0x19c0` | **`-0x20`** |
| `__DATA_CONST.__cfstring` | `0x17c0` | `0x17a0` | **`-0x20`** |
| `__TEXT.__objc_methtype` | `0xc35` | `0xc16` | **`-0x1f`** |
| `__TEXT.__auth_stubs` | `0x5c0` | `0x5d0` | **`+0x10`** |
| `__DATA_CONST.__auth_got` | `0x2f0` | `0x2f8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0x4e8` | `0x4e0` | **`-0x8`** |
| `__TEXT.__objc_methlist` | `0x1aac` | `0x1aa4` | **`-0x8`** |
| `__TEXT.__unwind_info` | `0x578` | `0x570` | **`-0x8`** |
| `__TEXT.__text` | `0x1a89c` | `0x1a898` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-2079.200.31.0.0
+2079.200.41.0.0

-  Functions: 502
+  Functions: 500

-  CStrings:  1412
+  CStrings:  1405
Symbols:
+ _CFEqual
- _OBJC_CLASS_$_CertUITrustManager
CStrings:
+ "copySMIMEEncryptionPolicyForAddress:"
- "_handleTrustFromIdentity:handler:"
- "actionForSMIMETrust:sender:"
- "addSMIMETrust:sender:"
- "com.apple.mobilemail.smime"
- "initWithAccessGroup:"
- "mf_uncommentedAddress"
- "v32@0:8^{__SecIdentity=}16@?24"
- "v32@?0^{__SecTrust=}8@\"CertUITrustManager\"16@\"NSString\"24"
```
