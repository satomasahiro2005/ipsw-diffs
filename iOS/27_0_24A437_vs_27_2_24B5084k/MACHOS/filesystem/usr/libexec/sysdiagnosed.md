## sysdiagnosed

> `/usr/libexec/sysdiagnosed`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6132c` | `0x614d4` | **`+0x1a8`** |
| `__DATA_CONST.__cfstring` | `0x11720` | `0x117c0` | **`+0xa0`** |
| `__TEXT.__cstring` | `0x10cc9` | `0x10d32` | **`+0x69`** |
| `__TEXT.__objc_methname` | `0xa78d` | `0xa7b4` | **`+0x27`** |
| `__TEXT.__objc_stubs` | `0x9400` | `0x9420` | **`+0x20`** |
| `__DATA.__objc_selrefs` | `0x2a00` | `0x2a08` | **`+0x8`** |
| `__TEXT.__const` | `0x1cc` | `0x1d4` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x3f6c` | `0x3f74` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x1198` | `0x11a0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-1598.0.6.0.0
+1598.40.4.0.0

-  Functions: 1775
+  Functions: 1776

-  CStrings:  4866
+  CStrings:  4872
Functions:
~ sub_100012304 : 1060 -> 1088
+ sub_1000169d4
CStrings:
+ "/private/var/db/com.apple.countryd/countryCodeCache.plist"
+ "/private/var/mobile/Library/SecureElementService/Ledger"
+ "Country"
+ "_copySecureElementServiceLogsContainer"
+ "defaultContactlessApp.log"
+ "endpoint.log"
+ "logs/Country"
- "/private/var/mobile/Library/SecureElementService/Ledger/endpoint.log"
```
