## uarppersonalizationd

> `/usr/libexec/uarppersonalizationd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__cfstring` | `0xfa0` | `0x1020` | **`+0x80`** |
| `__TEXT.__cstring` | `0xdae` | `0xe23` | **`+0x75`** |
| `__DATA_CONST.__const` | `0x520` | `0x548` | **`+0x28`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-1587.0.27.0.0
+1587.2.2.0.0

-  CStrings:  352
+  CStrings:  356
CStrings:
+ "com.apple.uarp.endpoint.assetavailable"
+ "com.apple.uarp.endpoint.assetavailable.subscriber"
+ "metrics"
+ "uarpTransportDomain"
```
