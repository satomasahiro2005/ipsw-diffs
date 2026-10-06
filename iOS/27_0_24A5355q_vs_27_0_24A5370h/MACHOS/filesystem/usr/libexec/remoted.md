## remoted

> `/usr/libexec/remoted`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x3d41c` | `0x3d274` | **`-0x1a8`** |
| `__TEXT.__oslogstring` | `0x842c` | `0x84b3` | **`+0x87`** |
| `__DATA.__objc_const` | `0x2840` | `0x2810` | **`-0x30`** |
| `__TEXT.__objc_methlist` | `0x1578` | `0x1560` | **`-0x18`** |
| `__TEXT.__objc_methname` | `0x2543` | `0x254c` | **`+0x9`** |
| `__DATA.__objc_ivar` | `0x220` | `0x21c` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`

### Other Changes

```diff

-243.0.0.0.0
+245.0.1.502.2

-  CStrings:  1767
+  CStrings:  1769
CStrings:
+ "replacePeerConnection: failed to get address from endpoint"
+ "replacePeerConnection:endpoint:"
+ "replacePeerSocket: network_copy_socket_remote_address_in6: %{darwin.errno}d"
- "replacePeerConnection:"
```
