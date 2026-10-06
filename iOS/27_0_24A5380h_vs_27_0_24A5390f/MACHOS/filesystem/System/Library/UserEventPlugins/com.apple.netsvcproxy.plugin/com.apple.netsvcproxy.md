## com.apple.netsvcproxy

> `/System/Library/UserEventPlugins/com.apple.netsvcproxy.plugin/com.apple.netsvcproxy`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x9ff4` | `0xa30c` | **`+0x318`** |
| `__TEXT.__objc_methname` | `0x2944` | `0x2a36` | **`+0xf2`** |
| `__TEXT.__objc_stubs` | `0x1c20` | `0x1cc0` | **`+0xa0`** |
| `__DATA.__objc_const` | `0xfa8` | `0x1008` | **`+0x60`** |
| `__TEXT.__oslogstring` | `0xb2b` | `0xb72` | **`+0x47`** |
| `__TEXT.__objc_methlist` | `0xac0` | `0xb00` | **`+0x40`** |
| `__DATA.__objc_selrefs` | `0x970` | `0x998` | **`+0x28`** |
| `__DATA.__const` | `0x670` | `0x690` | **`+0x20`** |
| `__TEXT.__cstring` | `0xf92` | `0xfa7` | **`+0x15`** |
| `__DATA.__objc_ivar` | `0x110` | `0x118` | **`+0x8`** |
| `__TEXT.__unwind_info` | `0x2b0` | `0x2b8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__cfstring`
- `__DATA.__data`
- `__DATA.__got`
- `__DATA.__objc_arraydata`
- `__DATA.__objc_arrayobj`
- `__DATA.__objc_classlist`
- `__DATA.__objc_data`
- `__DATA.__objc_protolist`
- `__DATA.__objc_superrefs`
- `__TEXT.__gcc_except_tab`

### Other Changes

```diff

-976.0.0.0.0
+980.0.0.0.0

-  Functions: 308
+  Functions: 315

-  CStrings:  757
+  CStrings:  769
CStrings:
+ "Failed to create token aggregation timer"
+ "T@\"NSDate\",&,V_tokenAggregationDate"
+ "T@\"NSTimer\",&,V_tokenAggregationTimer"
+ "TokenAggregationDate"
+ "_tokenAggregationDate"
+ "_tokenAggregationTimer"
+ "setTokenAggregationDate:"
+ "setTokenAggregationInterval:"
+ "setTokenAggregationTimer:"
+ "token aggregation timer fired"
+ "tokenAggregationDate"
+ "tokenAggregationTimer"
```
