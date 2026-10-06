## AppleThunderboltSAT

> `/System/Library/Extensions/AppleThunderboltSAT.kext/AppleThunderboltSAT`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT_EXEC.__text` | `0x26ed4` | `0x26e48` | **`-0x8c`** |
| `__TEXT.__cstring` | `0x11736` | `0x11741` | **`+0xb`** |
| `__DATA.__common` | `0x601` | `0x5f9` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`

### Other Changes

```diff

-120.0.0.502.1
-  Functions: 641
-  Symbols:   1268
-  CStrings:  1066
+121.0.0.0.0
+  Functions: 640
+  Symbols:   1267
+  CStrings:  1064
Symbols:
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_802
+ __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_876
- __ZL31getDefaultClientDataQueueLengthv
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_822
- __ZZN23AppleThunderboltSATPort13sendDirectiveERK15sat_directive_tE20kalloc_type_view_886
CStrings:
+ "1.0.105"
+ "121"
+ "19:54:07"
+ "AppleThunderboltSATGlobals() sat-vsa is %s"
+ "LinkDevice: routerID %d portID %d - remote ring mask is invalid, looks like VSA mode is not active on the capturing side (sat-vsa=0 or unsupported build)"
+ "SATLinkDevice::start - VSA mode disabled (sat-vsa=0 boot-arg set), skipping initialization\n"
+ "SATLinkDevice<%p>::activateInternal WARNING: remote ring mask is invalid - looks like VSA mode is not active on the capturing side (sat-vsa=0 or unsupported build). routerID %d, portID %d, remote_tx_mask=%u, remote_rx_mask=%u"
+ "Sep 13 2026"
- "1.0.104"
- "120.0.0.502.1"
- "20:44:28"
- "AppleThunderboltSATGlobals() sat-vsa is enabled"
- "LinkDevice: routerID %d portID %d - remote ring mask is invalid, looks like sat-vsa=1 boot-arg missing on the capturing side"
- "SATLinkDevice::start - VSA mode disabled (sat-vsa boot-arg not set), skipping initialization\n"
- "SATLinkDevice<%p>::activateInternal WARNING: looks like sat-vsa=1 boot-arg missing on the capturing side. routerID %d, portID %d, remote_tx_mask=%u, remote_rx_mask=%u"
- "Sep  9 2026"
- "default data queue len is 10"
- "default data queue len is 4096"
```
