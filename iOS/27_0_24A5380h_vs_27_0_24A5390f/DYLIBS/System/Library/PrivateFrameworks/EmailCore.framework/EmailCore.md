## EmailCore

> `/System/Library/PrivateFrameworks/EmailCore.framework/EmailCore`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x5ba44` | `0x5bac8` | **`+0x84`** |
| `__TEXT.__gcc_except_tab` | `0x71d4` | `0x71e8` | **`+0x14`** |
| `__DATA_CONST.__objc_selrefs` | `0x2a40` | `0x2a50` | **`+0x10`** |
| `__DATA_CONST.__got` | `0x6a0` | `0x6a8` | **`+0x8`** |
| `__TEXT.__objc_methlist` | `0x50b0` | `0x50b8` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2a78` | `0x2a80` | **`+0x8`** |

### Other Changes

```diff

-3895.100.17.2.1
+3897.100.8.2.5

-  Functions: 2042
+  Functions: 2043
Symbols:
+ -[ECEmailAddress isOrIsSubdomainOf:]
+ GCC_except_table70
+ GCC_except_table72
+ _OBJC_CLASS_$_EFNetworkDomainUtilities
- GCC_except_table49
- GCC_except_table68
- GCC_except_table71
- GCC_except_table73
Functions:
- ___63-[NSString(ECEmailAddressQuoting) ecemailaddress_uniquedDomain]_block_invoke.260
+ -[ECEmailAddress isOrIsSubdomainOf:]
+ ___63-[NSString(ECEmailAddressQuoting) ecemailaddress_uniquedDomain]_block_invoke.262
```
