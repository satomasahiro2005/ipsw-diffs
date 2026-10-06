## VisualAlert

> `/System/Library/PrivateFrameworks/VisualAlert.framework/VisualAlert`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xb138` | `0xb2b4` | **`+0x17c`** |
| `__TEXT.__cstring` | `0x1b99` | `0x1bd7` | **`+0x3e`** |
| `__DATA_CONST.__const` | `0x3c8` | `0x3a0` | **`-0x28`** |
| `__AUTH_CONST.__cfstring` | `0x1540` | `0x1560` | **`+0x20`** |

### Other Changes

```diff

-3245.8.2.0.0
+3245.8.4.2.0

-  Symbols:   503
-  CStrings:  206
+  Symbols:   502
+  CStrings:  207
Symbols:
+ -[AXVisualAlertManager _processNextVisualAlertComponentForPattern:]
+ ___67-[AXVisualAlertManager _processNextVisualAlertComponentForPattern:]_block_invoke
+ ___67-[AXVisualAlertManager _processNextVisualAlertComponentForPattern:]_block_invoke_2
+ ___block_descriptor_64_e8_32s40s48w_e5_v8?0ls32l8w48l8s40l8
- -[AXVisualAlertManager _processNextVisualAlertComponent]
- ___56-[AXVisualAlertManager _processNextVisualAlertComponent]_block_invoke
- ___56-[AXVisualAlertManager _processNextVisualAlertComponent]_block_invoke_2
- ___block_descriptor_40_e8_32w_e5_v8?0lw32l8
- ___block_descriptor_56_e8_32s40w_e5_v8?0ls32l8w40l8
Functions:
~ -[AXVisualAlertManager _beginVisualAlertForType:repeat:skipAutomaticStopOnUserInteraction:bundleId:] : 4436 -> 4460
~ -[AXVisualAlertManager _processNextVisualAlertComponent] -> -[AXVisualAlertManager _processNextVisualAlertComponentForPattern:] : 880 -> 1192
~ ___56-[AXVisualAlertManager _processNextVisualAlertComponent]_block_invoke -> ___67-[AXVisualAlertManager _processNextVisualAlertComponentForPattern:]_block_invoke : 180 -> 208
~ ___56-[AXVisualAlertManager _processNextVisualAlertComponent]_block_invoke_2 -> ___67-[AXVisualAlertManager _processNextVisualAlertComponentForPattern:]_block_invoke_2 : 64 -> 80
CStrings:
+ "Skipping stale visual alert component; active pattern changed"
```
