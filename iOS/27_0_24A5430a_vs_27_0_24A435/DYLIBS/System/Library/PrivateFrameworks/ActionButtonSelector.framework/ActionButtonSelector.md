## ActionButtonSelector

> `/System/Library/PrivateFrameworks/ActionButtonSelector.framework/ActionButtonSelector`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xe830` | `0xeb7c` | **`+0x34c`** |
| `__AUTH_CONST.__cfstring` | `0xce0` | `0xe00` | **`+0x120`** |
| `__TEXT.__cstring` | `0x701` | `0x7ba` | **`+0xb9`** |
| `__TEXT.__const` | `0x3e0` | `0x428` | **`+0x48`** |
| `__AUTH_CONST.__const` | `0x1e0` | `0x200` | **`+0x20`** |
| `__DATA.__bss` | `0x88` | `0x98` | **`+0x10`** |

### Other Changes

```diff

-  Functions: 330
-  Symbols:   835
-  CStrings:  137
+  Functions: 334
+  Symbols:   840
+  CStrings:  146
Symbols:
+ _ABDeviceIsV6x
+ _ABDeviceIsV6x.onceToken
+ _ABDeviceIsV6x.sIsDevice
+ _OUTLINED_FUNCTION_5
+ ___ABDeviceIsV6x_block_invoke
+ _objc_retain_x28
- _objc_retain_x27
Functions:
~ -[ABDeviceSceneViewController _renderWithTargetTimestamp:duration:renderInputs:] : 776 -> 784
~ ___59+[ABDeviceSceneModelNodeMap thisDeviceModelNodeIdentifiers]_block_invoke : 692 -> 840
~ _ABLoadDeviceSceneModel : 4776 -> 4808
~ _ABDeviceSceneButtonModelSetColor : 952 -> 960
~ _ABButtonOffsetFromDeviceCenter : 116 -> 152
~ ___ABDefaultZoomedInSceneParams_block_invoke : 580 -> 588
~ _ABDeviceModelResourceName : 412 -> 460
+ _ABDeviceIsD23
+ ___ABDeviceIsV6x_block_invoke
~ ___deviceSuffix_block_invoke : 804 -> 984
+ _OUTLINED_FUNCTION_5
~ -[ABDeviceDisplayView initWithFrame:] : 1176 -> 1228
~ -[ABDeviceDisplayView _transitionIslandToInert] : 224 -> 244
+ _ABDeviceModelResourceName.cold.6
CStrings:
+ "Action_Button_glow_modifier-V63-V64-V64S"
+ "KNbLXlpCjPscObD"
+ "V63"
+ "V64"
+ "ZliNpWiNbBDBaKg"
+ "bXHPcKpMKMdmEtM"
+ "fPvQtqWYeirBdJi"
+ "iPhone18_Pro_e-sim_Silver_FPO_CONFIDENTIAL-V63-V64-V64S"
+ "qbXAaRuUrFOMHIV"
```
