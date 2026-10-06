## MailAccountSettings

> `/System/Library/PreferenceBundles/AccountSettings/MailAccountSettings.bundle/MailAccountSettings`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x78474` | `0x785c8` | **`+0x154`** |
| `__TEXT.__gcc_except_tab` | `0x11d54` | `0x11d8c` | **`+0x38`** |
| `__TEXT.__objc_methtype` | `0x2bb8` | `0x2b91` | **`-0x27`** |
| `__TEXT.__objc_methname` | `0xd907` | `0xd8e5` | **`-0x22`** |
| `__DATA_CONST.__cfstring` | `0x5c80` | `0x5c60` | **`-0x20`** |
| `__TEXT.__objc_stubs` | `0xa1a0` | `0xa180` | **`-0x20`** |
| `__TEXT.__cstring` | `0x4d75` | `0x4d5a` | **`-0x1b`** |
| `__DATA.__objc_selrefs` | `0x38b8` | `0x38a8` | **`-0x10`** |
| `__TEXT.__auth_stubs` | `0x760` | `0x770` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x62d8` | `0x62c8` | **`-0x10`** |
| `__DATA.__objc_const` | `0xada8` | `0xada0` | **`-0x8`** |
| `__DATA_CONST.__auth_got` | `0x3c0` | `0x3c8` | **`+0x8`** |
| `__DATA_CONST.__got` | `0xa08` | `0xa00` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-3901.200.41.0.0
+3901.200.66.2.1

-  CStrings:  3600
+  CStrings:  3596
Symbols:
+ _CFEqual
- _OBJC_CLASS_$_CertUITrustManager
Functions:
~ sub_a708 : 2268 -> 2000
~ sub_14994 -> sub_14888 : 280 -> 300
~ sub_14cd4 -> sub_14bdc : 404 -> 992
CStrings:
+ "copySMIMEEncryptionPolicyForAddress:"
- "Q32@0:8@\"RUIObjectModel\"16@\"RUIPage\"24"
- "actionForSMIMETrust:sender:"
- "addSMIMETrust:sender:"
- "com.apple.mobilemail.smime"
- "initWithAccessGroup:"
```
