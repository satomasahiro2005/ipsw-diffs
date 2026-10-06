## gputoolsserviced

> `/usr/libexec/gputoolsserviced`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x33048` | `0x33584` | **`+0x53c`** |
| `__TEXT.__objc_methname` | `0x7770` | `0x7829` | **`+0xb9`** |
| `__TEXT.__objc_stubs` | `0x55e0` | `0x5680` | **`+0xa0`** |
| `__DATA.__objc_const` | `0x6e90` | `0x6f00` | **`+0x70`** |
| `__TEXT.__cstring` | `0x4689` | `0x46e2` | **`+0x59`** |
| `__DATA_CONST.__cfstring` | `0x33c0` | `0x3400` | **`+0x40`** |
| `__TEXT.__objc_methlist` | `0x35fc` | `0x363c` | **`+0x40`** |
| `__TEXT.__oslogstring` | `0x18ec` | `0x1928` | **`+0x3c`** |
| `__DATA.__objc_selrefs` | `0x1dc0` | `0x1de8` | **`+0x28`** |
| `__DATA_CONST.__const` | `0xb80` | `0xba8` | **`+0x28`** |
| `__TEXT.__unwind_info` | `0xa18` | `0xa30` | **`+0x18`** |
| `__TEXT.__auth_stubs` | `0xf30` | `0xf20` | **`-0x10`** |
| `__DATA.__objc_ivar` | `0x440` | `0x448` | **`+0x8`** |
| `__DATA_CONST.__auth_got` | `0x7a0` | `0x798` | **`-0x8`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`

### Other Changes

```diff

-2027.0.37.0.0
+2027.0.44.0.0

-  Functions: 1171
-  Symbols:   329
-  CStrings:  2090
+  Functions: 1180
+  Symbols:   328
+  CStrings:  2100
Symbols:
- _objc_retain_x28
CStrings:
+ "<%@: protocolName=%@ protocolMethods=%@ servicePort=%llu platform=%u deviceUDID=%@ version=%llu accessLevel=%llu>"
+ "Rejecting untrusted message to restricted service port %llu"
+ "TB,N,V_originatorUntrusted"
+ "TQ,N,V_accessLevel"
+ "_accessLevel"
+ "_originatorUntrusted"
+ "accessLevel"
+ "accessLevelForPort:"
+ "originatorUntrusted"
+ "patchMessage:toConnection:"
+ "setAccessLevel:"
+ "setOriginatorUntrusted:"
- "<%@: protocolName=%@ protocolMethods=%@ servicePort=%llu platform=%u deviceUDID=%@ version=%llu>"
- "patchMessage:"
```
