## ThreadNetwork

> `/System/Library/Frameworks/ThreadNetwork.framework/ThreadNetwork`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xda20` | `0xdbcc` | **`+0x1ac`** |
| `__DATA_CONST.__objc_selrefs` | `0x7e8` | `0x7f8` | **`+0x10`** |

### Other Changes

```diff

-446.0.2.0.1
+446.0.4.0.0
Functions:
~ ___35-[THClient retrieveAllCredentials:]_block_invoke : 636 -> 712
~ ___57-[THClient retrieveCredentialsForBorderAgent:completion:]_block_invoke : 500 -> 576
~ ___59-[THClient retrieveCredentialsForExtendedPANID:completion:]_block_invoke : 404 -> 480
~ ___41-[THClient retrieveAllActiveCredentials:]_block_invoke : 636 -> 736
~ -[THClient handleActiveNearbyNetworksResponse:error:isInternal:completion:] : 672 -> 772
```
