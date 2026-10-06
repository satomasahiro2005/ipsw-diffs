## ControlCenterUI

> `/System/Library/PrivateFrameworks/ControlCenterUI.framework/ControlCenterUI`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__TEXT.__text` | `0xbaf24` | `0xbb00c` | **`+0xe8`** |
| `__TEXT.__oslogstring` | `0x43fb` | `0x445b` | **`+0x60`** |
| `__TEXT.__cstring` | `0x47f4` | `0x4824` | **`+0x30`** |
| `__AUTH_CONST.__cfstring` | `0x2f60` | `0x2f80` | **`+0x20`** |
| `__TEXT.__objc_methlist` | `0xb4e0` | `0xb4f0` | **`+0x10`** |
| `__DATA_CONST.__objc_selrefs` | `0x68e0` | `0x68e8` | **`+0x8`** |

### Other Changes

```diff

-701.101.0.0.0
+702.0.0.0.0

-  Functions: 5044
-  Symbols:   5615
-  CStrings:  850
+  Functions: 5045
+  Symbols:   5616
+  CStrings:  852
Symbols:
+ -[CCUIModuleAlertViewController _propagateUserVisibilityStatus:]
Functions:
+ -[CCUIModuleAlertViewController _propagateUserVisibilityStatus:]
~ -[CCUIModuleAlertViewController viewDidAppear:] : 100 -> 112
~ -[CCUIModuleAlertViewController viewWillDisappear:] : 92 -> 104
CStrings:
+ "[Appearance Propagation] ModuleAlert propagating userVisibilityStatus=%lu to container"
+ "com.apple.replaykit.controlcenter.screencapture"
```
