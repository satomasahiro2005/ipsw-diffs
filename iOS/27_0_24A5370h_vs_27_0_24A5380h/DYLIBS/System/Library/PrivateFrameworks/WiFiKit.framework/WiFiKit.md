## WiFiKit

> `/System/Library/PrivateFrameworks/WiFiKit.framework/WiFiKit`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xa4928` | `0xa49a8` | **`+0x80`** |
| `__TEXT.__cstring` | `0xc1ab` | `0xc1bb` | **`+0x10`** |
| `__TEXT.__gcc_except_tab` | `0x225c` | `0x2268` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x1ef0` | `0x1ee8` | **`-0x8`** |

### Other Changes

```diff

-1205.59.4.1.0
+1205.63.4.1.0
Functions:
~ -[WFNetworkListController _updateViewControllerScanResults] : 264 -> 116
~ ___59-[WFNetworkListController _updateViewControllerScanResults]_block_invoke : 4120 -> 4260
~ ___63-[WFNetworkListController _associationDidFinish:error:network:]_block_invoke : 2468 -> 2604
~ ___63-[WFGasQueryController resolveProfileForNetwork:handler:force:]_block_invoke_3 : 164 -> 172
~ _WFBase64Encode : 544 -> 536
CStrings:
+ "-[WFNetworkListController _associationDidFinish:error:network:]_block_invoke"
- "-[WFNetworkListController _updateViewControllerScanResults]"
```
