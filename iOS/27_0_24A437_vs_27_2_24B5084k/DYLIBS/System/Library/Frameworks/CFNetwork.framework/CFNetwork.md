## CFNetwork

> `/System/Library/Frameworks/CFNetwork.framework/CFNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x2567f0` | `0x25692c` | **`+0x13c`** |
| `__TEXT.__oslogstring` | `0xf9c9` | `0xfa2d` | **`+0x64`** |
| `__TEXT.__const` | `0xc9c2c` | `0xc9c1c` | **`-0x10`** |

### Other Changes

```diff

-3896.100.1.2.1
+3896.200.31.0.0

-  CStrings:  4753
+  CStrings:  4754
Symbols:
+ GCC_except_table5513
+ GCC_except_table5519
+ GCC_except_table5520
+ GCC_except_table5523
+ GCC_except_table5524
+ GCC_except_table5528
+ GCC_except_table5533
+ GCC_except_table5538
+ ___block_descriptor_52_e8_32c40_ZTSNSt3__110shared_ptrI12HTTPProtocolEE_e127_v48?0^{__CFHTTPMessage=}8I16^{__CFString=}20i28{SmartBlockWithArgs<const _CFURLCredential *, bool>=^v^{__shared_weak_count}}32l
- GCC_except_table5515
- GCC_except_table5521
- GCC_except_table5522
- GCC_except_table5525
- GCC_except_table5526
- GCC_except_table5536
- GCC_except_table5539
- GCC_except_table5540
- ___block_descriptor_56_e8_40c40_ZTSNSt3__110shared_ptrI12HTTPProtocolEE_e127_v48?0^{__CFHTTPMessage=}8I16^{__CFString=}20i28{SmartBlockWithArgs<const _CFURLCredential *, bool>=^v^{__shared_weak_count}}32l
CStrings:
+ "%{public}@ system activity assertion did not revert sleep (attempt %d/3, result = %d)"
+ "Connection %llu received H2 GOAWAY with error code: %u message: %.*s"
- "Connection %llu received H2 GOAWAY with error code: %u"
```
