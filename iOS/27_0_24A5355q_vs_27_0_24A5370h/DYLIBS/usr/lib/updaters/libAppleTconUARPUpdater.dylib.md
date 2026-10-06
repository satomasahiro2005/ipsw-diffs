## libAppleTconUARPUpdater.dylib

> `/usr/lib/updaters/libAppleTconUARPUpdater.dylib`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0x6d27c` | `0x6d514` | **`+0x298`** |
| `__TEXT.__oslogstring` | `0x36c9` | `0x37a1` | **`+0xd8`** |
| `__TEXT.__cstring` | `0x73d7` | `0x7439` | **`+0x62`** |
| `__AUTH_CONST.__cfstring` | `0x5320` | `0x5340` | **`+0x20`** |
| `__DATA_CONST.__objc_selrefs` | `0x1ed0` | `0x1ee0` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1928` | `0x1938` | **`+0x10`** |
| `__TEXT.__objc_methlist` | `0x63e4` | `0x63ec` | **`+0x8`** |

### Other Changes

```diff

-1576.0.0.0.0
+1587.0.3.0.3

-  Functions: 2833
-  Symbols:   4625
-  CStrings:  1276
+  Functions: 2835
+  Symbols:   4627
+  CStrings:  1281
Symbols:
+ -[UARPEndpointLayer3(Layer2AssetCallbacks) assetAllHeadersAndMetaDataComplete:]
+ ___79-[UARPEndpointLayer3(Layer2AssetCallbacks) assetAllHeadersAndMetaDataComplete:]_block_invoke
CStrings:
+ "%s: Asset <%@> for Endpoint <%@>; payload index %lu has unexpected data length of %d"
+ "%s: Failed to query payload info for index %lu -> <%u> %s"
+ "-[UARPEndpointLayer3(Layer2AssetCallbacks) assetAllHeadersAndMetaDataComplete:]_block_invoke"
+ "All Headers And MetaData Complete for SuperBinary <%@> for Endpoint <%@>"
+ "HSML"
```
