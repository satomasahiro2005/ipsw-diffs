## uarpd

> `/usr/libexec/uarpd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa4384` | `0xa4190` | **`-0x1f4`** |
| `__TEXT.__gcc_except_tab` | `0x1c4` | `0x1ec` | **`+0x28`** |
| `__DATA.__objc_const` | `0x108f0` | `0x10910` | **`+0x20`** |
| `__TEXT.__auth_stubs` | `0xa70` | `0xa90` | **`+0x20`** |
| `__TEXT.__unwind_info` | `0x23f0` | `0x2410` | **`+0x20`** |
| `__TEXT.__objc_methname` | `0xf557` | `0xf56a` | **`+0x13`** |
| `__DATA_CONST.__auth_got` | `0x548` | `0x558` | **`+0x10`** |
| `__TEXT.__cstring` | `0xb0ce` | `0xb0dc` | **`+0xe`** |
| `__DATA.__objc_ivar` | `0xb70` | `0xb74` | **`+0x4`** |
| `__TEXT.__objc_methtype` | `0x2acd` | `0x2ad1` | **`+0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-1587.2.2.0.0
+1587.2.3.0.0

-  Functions: 3977
-  Symbols:   237
-  CStrings:  5002
+  Functions: 3979
+  Symbols:   239
+  CStrings:  5004
Symbols:
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
CStrings:
+ "-[UARPEndpointLayer3 directConfiguration]_block_invoke"
+ "_kInternalQueueKey"
+ "r^v"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xb31"
- "-[UARPEndpointLayer3 directConfiguration]"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa31"
```
