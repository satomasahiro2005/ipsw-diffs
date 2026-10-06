## Passbook

> `/private/var/staged_system_apps/Passbook.app/Passbook`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xfaf4` | `0xfd10` | **`+0x21c`** |
| `__DATA_CONST.__const` | `0x8f8` | `0x920` | **`+0x28`** |
| `__TEXT.__auth_stubs` | `0x610` | `0x630` | **`+0x20`** |
| `__TEXT.__cstring` | `0x6d1` | `0x6e4` | **`+0x13`** |
| `__DATA_CONST.__auth_got` | `0x318` | `0x328` | **`+0x10`** |
| `__TEXT.__objc_methname` | `0x4632` | `0x463d` | **`+0xb`** |
| `__DATA_CONST.__got` | `0x900` | `0x908` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2c8` | `0x2d0` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1677.4.0.0.0
+1682.1.0.0.0

-  Functions: 196
-  Symbols:   397
-  CStrings:  765
+  Functions: 197
+  Symbols:   400
+  CStrings:  766
Symbols:
+ _PKPhysicalCardOrderReasonFromString
+ _PKURLActionPhysicalCardOrderReason
+ _PKURLSubactionRouteCreditPaymentPassLockUnlock
+ _objc_release_x2
- _PKURLActionShareActivateShare
CStrings:
+ "presentPhysicalCardReplacementForPassUniqueId:reason:"
+ "v16@?0@\"NSString\"8"
- "presentShareActivationWithShareIdentifier:"
```
