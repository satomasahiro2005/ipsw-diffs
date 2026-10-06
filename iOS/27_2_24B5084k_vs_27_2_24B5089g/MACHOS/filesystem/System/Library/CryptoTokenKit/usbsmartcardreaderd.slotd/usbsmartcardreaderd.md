## usbsmartcardreaderd

> `/System/Library/CryptoTokenKit/usbsmartcardreaderd.slotd/usbsmartcardreaderd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x176b4` | `0x17854` | **`+0x1a0`** |
| `__TEXT.__oslogstring` | `0x1a69` | `0x1aac` | **`+0x43`** |
| `__TEXT.__objc_stubs` | `0x3660` | `0x36a0` | **`+0x40`** |
| `__TEXT.__objc_methname` | `0x2a06` | `0x2a38` | **`+0x32`** |
| `__DATA.__objc_const` | `0x3348` | `0x3370` | **`+0x28`** |
| `__TEXT.__objc_methlist` | `0x1a94` | `0x1abc` | **`+0x28`** |
| `__DATA.__objc_selrefs` | `0xf40` | `0xf50` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x680` | `0x690` | **`+0x10`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`

### Other Changes

```diff

-878.40.2.0.0
+878.40.4.0.0

-  Functions: 740
+  Functions: 743

-  CStrings:  1281
+  CStrings:  1284
CStrings:
+ "Ignoring RFU bChainParameter=0x%02x from non-extended-level reader"
+ "chainableTransmitter"
+ "supportsExtendedAPDUExchange"
```
