## MobileContainerManager

> `/System/Library/PrivateFrameworks/MobileContainerManager.framework/MobileContainerManager`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__const` | `0x330` | `0x328` | **`-0x8`** |
| `__TEXT.__text` | `0x2cdc` | `0x2cd4` | **`-0x8`** |

### Other Changes

```diff

-826.0.0.0.1
+833.0.0.0.0
Functions:
~ ___MCMGetMCMContainerClassForContainerClass_block_invoke : 116 -> 112
~ -[MCMContainerManager(Internal) _containersWithClass:temporary:error:] : 1060 -> 1064
~ -[MCMContainerManager deleteContainers:withCompletion:] : 592 -> 584
```
